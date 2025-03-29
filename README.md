# meta-tools - Productivity Tool Suite

## Project Overview

meta-tools is a lightweight, browser-based productivity tool suite designed to help streamline your workflow. The core of the application is built on a simple HTTP server that hosts various productivity tools.

## Features

### Transcription Tool
- **Audio File Upload**: Drag and drop or select audio files for transcription
- **Format Support**: Compatible with common audio formats (mp3, wav, m4a, etc.)
- **Interactive UI**: Clean, intuitive interface with real-time status updates
- **Copy to Clipboard**: One-click copying of transcription results

## Installation Instructions

### Setup Steps

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/meta-tools.git
   cd meta-tools
   ```

2. Install dependencies:
   ```
   npm install
   ```

3. That's it! No build process required.

## Usage Guide

### Starting the Server

Start the HTTP server by running:
```
npm start run
```

This will launch the http-server on port 8080 (or the next available port if 8080 is in use).

### Accessing the Tools

Once the server is running, you can access:
- Main page: http://localhost:8080
- Transcription tool: http://localhost:8080/transcription/

### Using the Transcription Tool

1. Navigate to http://localhost:8080/transcription/
2. Drag and drop an audio file onto the upload area (or click to browse)
3. Wait for the transcription process to complete
4. View the transcribed text in the result area
5. Use the "Copy to Clipboard" button to easily copy the transcription

> **Note**: The current implementation includes a simulated transcription process. To enable actual transcription functionality, you'll need to integrate with a speech-to-text service.

## Directory Structure

```
meta-tools/
├── package.json         # Project configuration and dependencies
├── README.md            # Project documentation
├── index.html           # Main application entry point
└── transcription/       # Transcription tool directory
    └── index.html       # Transcription tool interface
```

## License

MIT

