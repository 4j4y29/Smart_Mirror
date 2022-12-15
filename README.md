# Smart-Mirror
Code used to develop a smart mirror with AI capabilities.

## Capabilities
⭐ Facial recognition<br>
⭐ Speech-to-text<br>
⭐ Text processing<br>
⭐ Text-to-speech<br>
⭐ Task performance<br>


## Libraries & Python Script
- OpenCV for facial recognition
- Amazon Transcribe for speech-to-text capabilities
- Python script for streamlining speech-to-text and text processing
- Uses gTTS Python library for text-to-speech

## Requirements
- requires an Amazon account
- requires IAM user with programmatic access to Transcribe service
- several Python libraries
- Raspberry Pi 

## Usage
```bash
bash final.sh
```
Calls `main.py` script in infinite loop to allow user to quit out of the Python script with the "Quit" command. Allows for other users to authenticate to the mirror. 
