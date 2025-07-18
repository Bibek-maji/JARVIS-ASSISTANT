# JARVIS-ASSISTANT

Jarvis is a simple voice-controlled virtual assistant built with Python. It listens for voice commands, responds to greetings, and can perform actions like opening websites or playing music from a custom library. The assistant uses speech recognition and text-to-speech to interact with users in real time.

🚀 Features:-

Wake-word activation ("Jarvis")

Responds with text-to-speech using pyttsx3

Supports the following voice commands:

"open google" – Opens Google

"open facebook" – Opens Facebook

"open youtube" – Opens YouTube

also open the desktop applications by "open" command

also close the current window by "close" command

"how are you" – Jarvis responds with a friendly message

"play [song name]" – Plays music from a user-defined musicLibrary dictionary

Real-time speech recognition using SpeechRecognition and Google Web Speech API

Ambient noise adjustment for better recognition accuracy



🛠️ Requirements
Python 3.6+

SpeechRecognition

PyAudio

pyttsx3

pyautogui

musicLibrary.py (Custom module containing a dictionary of song names and their URLs)
