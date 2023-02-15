# Openai Whisper (Unofficial)

This is a Node.js app that transcribes audio files using openai whisper.

## Installation
To install the app and its dependencies, run:

```js
npm install openai-whisper
```

## Usage
To transcribe an audio file
```js
const { transcribeAudioFile } = require('./asr');

const filePath = '/path/to/audio/file.mp3';

transcribeAudioFile(filePath)
  .then(transcription => {
    console.log(transcription);
  })
  .catch(error => {
    console.error(error);
  });

```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

# Developed by [amosayomide05](https://github.com/amosayomide05)
