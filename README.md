# GENERATE ELAN

This package reads all the audio files in one or more directories and generates an ELAN file for each audio file in the corresponding directory.

## Installing

You can install this package by running the following command from PyPi:

```bash
pip install generate-elan
```

## How to use

Generate ELAN files (with `.eaf` extension) from of audio files from directories:

```bash
python -m generate_elan -d DIRECTORY [DIRECTORY ...]
```

You can also specify some options:

```bash
-d, --directory DIRECTORY [DIRECTORY ...]
                        Directory containing audio files
-e, --extension EXTENSION
                        Audio extension (default: .wav)
```
