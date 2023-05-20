# youtube-transcript-axios

### This is a fork of youtube-transcript package which replaces phin with axios. Phin causes issue in react-native as react-native doesn't include nodejs standard library

[![npm version](https://badge.fury.io/js/youtube-transcript.svg)](https://badge.fury.io/js/youtube-transcript)

I wanted to extract a transcript from a youtube video but there was only a python script so I created this to do it in node.
This package use unofficial YTB API so it can be broken over the time if no update appears.

## Installation

```bash
$ npm i youtube-transcript-axios
```

or

```bash
$ yarn add youtube-transcript-axios
```

## Usage

```js
import { YoutubeTranscript } from 'youtube-transcript-axios';

YoutubeTranscript.fetchTranscript('videoId or URL').then(console.log);
```

### Methods

- fetchTranscript(videoId: string [,options: TranscriptConfig]): Promise<TranscriptResponse[]>;

## License

**[MIT](LICENSE)** Licensed
