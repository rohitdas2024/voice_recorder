# Voice Recorder 

## Overview

This Python script demonstrates a simple audio recording application using the PyAudio library. It captures audio from the default microphone, continuously records it in chunks, and saves the recording as a WAV file.

## Dependencies

- Python 3.x
- PyAudio library
- Wave library

Install PyAudio and Wave using the following command:

```
pip install pyaudio
pip install wave

```
## Dependencies

Run the script audio_recorder.py.
The script will record audio continuously until manually interrupted (Ctrl+C).
The recorded audio will be saved as "recording.wav" in the same directory as the script.

## Configuration

The script uses default settings for audio input (16-bit PCM, mono channel, 44100 Hz sample rate).
Adjust the frames_per_buffer parameter in the script to modify the chunk size for recording.

## File Output

The recorded audio is saved as a WAV file named "recording.wav" in the script's directory.

## Termination

The script can be terminated at any time by using the keyboard interrupt (Ctrl+C).

## Notes

Ensure that the PyAudio library is installed before running the script.
