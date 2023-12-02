# Audio Recorder using PyAudio

## Overview

This Python script demonstrates a simple audio recording application using the PyAudio library. It captures audio from the default microphone, continuously records it in chunks, and saves the recording as a WAV file.

## Dependencies

- Python 3.x
- PyAudio library

Install PyAudio using the following command:

```bash
pip install pyaudio

## Usage

Run the script audio_recorder.py.
The script will record audio continuously until manually interrupted (Ctrl+C).
The recorded audio will be saved as "recording.wav" in the same directory as the script.
Configuration

The script uses default settings for audio input (16-bit PCM, mono channel, 44100 Hz sample rate).
Adjust the frames_per_buffer parameter in the script to modify the chunk size for recording.
File Output

The recorded audio is saved as a WAV file named "recording.wav" in the script's directory.

Termination

The script can be terminated at any time by using the keyboard interrupt (Ctrl+C).

Notes

This is a basic example and may require additional error handling and input validation for production use.
Ensure that the PyAudio library is installed before running the script.
