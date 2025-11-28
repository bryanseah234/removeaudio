# Remove Audio Code

A Python script to batch remove audio from video files using FFmpeg.

## Description

This project provides a simple command-line tool to strip audio tracks from video files. It recursively scans a specified directory and removes audio from all supported video files (MP4, AVI, MOV), creating new files with the "noaudio_" prefix while preserving the original files.

## Features

- Batch processing of multiple video files in a directory
- Supports MP4, AVI, and MOV video formats
- Preserves original video files (creates new files with "noaudio_" prefix)
- Uses FFmpeg for fast, lossless audio removal

## Technologies Used

- Python 3
- FFmpeg (external dependency)
- subprocess module for FFmpeg integration

## Installation

```bash
# Clone the repository
git clone https://github.com/bryanseah234/remove-audio-code.git

# Navigate to project directory
cd remove-audio-code

# Make sure FFmpeg is installed on your system
# On Ubuntu/Debian:
sudo apt install ffmpeg

# On macOS (using Homebrew):
brew install ffmpeg

# On Windows:
# Download from https://ffmpeg.org/download.html and add to PATH
```

## Usage

```bash
# Run the script
python noaudio.py
```

1. When prompted, enter the directory path containing your video files
2. The script will scan for MP4, AVI, and MOV files
3. New files with removed audio will be created with the "noaudio_" prefix

**Note:** Directory paths with spaces may cause issues due to command-line parsing limitations.

## Demo

No live demo available - this is a command-line tool.

## Disclaimer

- FOR EDUCATIONAL PURPOSES ONLY
- USE AT YOUR OWN DISCRETION

## License

MIT License

---

**Author:** <a href="https://github.com/bryanseah234">bryanseah234</a>
