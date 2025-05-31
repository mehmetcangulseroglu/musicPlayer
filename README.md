# Java Audio Player

A simple console-based audio player written in Java that can play audio files in WAV, AU, and AIFF formats.

## Features

- Play audio files (WAV, AU, AIFF formats)
- Interactive console menu with the following options:
  - **P** - Play audio
  - **S** - Stop audio
  - **R** - Reset audio to beginning
  - **Q** - Quit application

## Requirements

- Java 8 or higher
- Audio file in supported format (WAV, AU, AIFF)

## Setup

1. Compile the Java file:
   ```bash
   javac Main.java
   ```

2. Place your audio file in the same directory as the compiled class and name it `plane-sound-from-distance-hq-247602.wav` (or modify the file path in the code)

3. Run the application:
   ```bash
   java Main
   ```

## Supported Audio Formats

- WAV (.wav)
- AU (.au) 
- AIFF (.aiff)

**Note:** MP3 files are not supported. You can convert MP3 files to WAV format using online converters or audio editing software.

## Usage

1. Run the program
2. Use the menu options:
   - Press `P` and Enter to play the audio
   - Press `S` and Enter to stop the audio
   - Press `R` and Enter to reset the audio to the beginning
   - Press `Q` and Enter to quit the application

## Error Handling

The application handles the following error scenarios:
- File not found
- Unsupported audio file format
- Audio resource unavailable
- General I/O errors

## File Structure

```
project-directory/
├── Main.java
└── plane-sound-from-distance-hq-247602.wav
```

## Notes

- The audio file should be placed in the same directory as the Java source file to avoid specifying additional file paths
- The program uses Java's built-in audio capabilities through the `javax.sound.sampled` package
- The application will continue running until you select the quit option (Q)
