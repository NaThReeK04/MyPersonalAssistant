# Jarvis Voice Assistant

## Overview
This is a simple **voice assistant** built using Python that listens to user commands and performs various tasks such as playing YouTube videos, telling the current time, providing Wikipedia summaries, and telling jokes. It uses **Speech Recognition, Text-to-Speech, Wikipedia API, and PyWhatKit** to execute commands.

## Features
- **Play YouTube videos** by saying "Jarvis, play [song name]".
- **Get the current time** by asking "Jarvis, what time is it?".
- **Fetch Wikipedia summaries** by asking "Jarvis, who is [person's name]?".
- **Tell a joke** by saying "Jarvis, tell me a joke".
- **Handles unrecognized commands** gracefully.

## Requirements
Ensure you have Python installed and then install the required dependencies using:
```bash
pip install speechrecognition pyttsx3 pywhatkit wikipedia pyjokes
```

## How It Works
1. The script listens for voice input using `speech_recognition`.
2. If the command contains "Jarvis", it processes the request.
3. Based on the detected command:
   - If "play" is found, it plays a YouTube video.
   - If "time" is found, it tells the current time.
   - If "who" is found, it fetches Wikipedia info.
   - If "joke" is found, it tells a joke.
4. If the command is not recognized, it asks the user to repeat.
5. The program runs in a continuous loop, waiting for user commands.

## Usage
Run the script using:
```bash
python jarvis.py
```
Then, speak a command like:
- **"Jarvis, play Shape of You"** → Plays the song on YouTube.
- **"Jarvis, what time is it?"** → Tells the current time.
- **"Jarvis, who is Elon Musk?"** → Provides a Wikipedia summary.
- **"Jarvis, tell me a joke"** → Says a random joke.

## Future Improvements
- Add more voice commands.
- Improve speech recognition accuracy.
- Integrate with smart home devices.
- Add natural language processing for better responses.

## Author
Developed by **Keerthan Ghodiwal**

## License
This project is open-source and available under the MIT License.

