# AI Voice Translator

This repository uses `PyAudio`, `langdetect`, and `googletrans` to generate translated audio. 

## Installation

To get started, you'll need Python 3.7 or newer. To install pyaudio, use the commands below.

## on MacOS using [Homebrew](https://brew.sh/)
    brew install portaudio
    pip install pyaudio

## Usage

The following command will prompt the text "Speak something...", in which you can speak into the mic.

    python3 translate.py

It will recognize the voice, and interpret what was received in terminal. Thehn, it produces an outputed translated in spanish or english (depending on which language was spoken).

## License

This script is open-source and licensed under the MIT License. For more details, check the [LICENSE](LICENSE) file.
