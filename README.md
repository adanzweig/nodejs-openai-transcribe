# OpenAI Transcription Service

A Node.js application that utilizes the OpenAI API to transcribe audio files.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine.

### Prerequisites

- Node.js and npm installed on your machine.
- An OpenAI API key.

### Installation

1. Clone the repository:
```bash
git clone https://github.com/adanzweig/nodejs-openai-transcribe.git
```

2. Navigate to the project directory:
```bash
cd nodejs-openai-transcribe
```

3. Install the dependencies:
```bash
npm install
```

4. Create a `.env` file in the root directory and add your OpenAI API key:
```bash
OPENAI_API_KEY=your_api_key_here
```

### Usage

1. To transcribe an audio file named `sound_9.mp3` (or any other file), simply run:
```bash
node index.js
```

## Built With

- [OpenAI](https://beta.openai.com/docs/) - The AI API used for transcription.
- [dotenv](https://www.npmjs.com/package/dotenv) - Module to load environment variables from a `.env` file.
- [fs](https://nodejs.org/api/fs.html) - Node.js built-in File System module.

## Contributing

Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code of conduct, and the process for submitting pull requests to us.

## Issues

If you encounter any issues or have feature suggestions, please report them [here](https://github.com/adanzweig/nodejs-openai-transcribe/issues).

## Author

- **adanjz** - [adanzweig](https://github.com/adanzweig)