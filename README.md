# Dubbing and Translation Automation Project
## Overview
This project aims to automate the process of dubbing and translating video content. It takes input in the form of original audio in a specific language and outputs synchronized video with dubbed audio in the target language. The workflow involves converting audio to text, translating the text, and synchronizing the translated audio with the original video.

## Features
- Automatic Speech Recognition (ASR): Utilizes ASR to convert audio content into text.
- Translation: Translates the text from the original language to the target language using machine translation services.
- Audio Synchronization: Syncs the translated audio with the original video.
- Adaptive Learning: Allows users to provide feedback and improve the accuracy of translations through adaptive learning mechanisms.
- Multi-Language Support: Supports multiple languages for both input and output.


# Key Components
- Speech Recognition Module: Converts audio files to text using speech recognition libraries.
- Translation Service: Utilizes machine translation APIs to translate text between languages.
- Video Editing Module: Syncs translated audio with the original video using video editing tools.
- User Interface: Provides a user-friendly interface for inputting original and target languages, and controlling the dubbing process.
- Adaptive Learning Algorithm: Implements a feedback mechanism to improve translation accuracy over time.


## Usage
Clone the repository to your local machine.
Install the required dependencies listed in the requirements.txt file.
Run the main script, dubbing_automation.py, and follow the prompts to input the original and target languages.
Monitor the progress of the dubbing process and provide feedback when prompted for adaptive learning.


#### This project take video as input,thus particular input seperate into video and audio . 
#### This audio is split into smaller chunks and then translate into different languague
#### At the end of the program translated chunks are merged into single audio
#### The final output of the program video with translated audio
[README.md](https://github.com/Gowthamragk/Polyglot-Dubbing-Engine/files/14850294/README.md)
