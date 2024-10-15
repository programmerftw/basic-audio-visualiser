# Audio Visualizer

This is a simple web-based audio visualizer that processes an audio file uploaded by the user and displays its frequency data as a dynamic bar chart on an HTML canvas.

## Features

- Upload and analyze an audio file (MP3, WAV, etc.)
- Visualize frequency data using bars on a canvas element
- Dynamic, real-time frequency analysis of the audio data

## How It Works

1. **Audio File Input**: The user selects an audio file through an `<input>` element.
2. **File Processing**: The file is read as an `ArrayBuffer` using the `FileReader` API.
3. **Audio Decoding**: The `ArrayBuffer` is decoded using the Web Audio API (`AudioContext`), which processes the audio data.
4. **Visualization**: The decoded audio is visualized as frequency data on an HTML canvas using an `AnalyserNode` from the Web Audio API.

## How to Use

1. Clone or download this repository.
2. Create an HTML file with the following elements:
   - An `<input>` field to upload audio files.
   - A `<canvas>` element for displaying the visualized audio frequencies.
   
3. Include the provided JavaScript code to process and visualize the audio.
