# multi-language-speech-recognition-system-
Voice to Text Converter with GUI
This is a Python program that converts voice input into text using the Google Speech Recognition API. It also includes a Graphical User Interface (GUI) using the Tkinter library.

Prerequisites
Before running the program, make sure you have the following installed:

Python 3.x: This program uses Python 3.x as the programming language.
Tkinter: This is a standard Python library for creating GUI applications.
SpeechRecognition: This is a Python library for performing speech recognition tasks.
Pyttsx3: This is a Python library for text-to-speech conversion.
You can install the required libraries using the following commands:
pip install tkinter
pip install SpeechRecognition
pip install pyttsx3

Usage
Run the voice_to_text.py file in your Python environment.
The program will display a GUI window with two buttons: "Start Recording" and "Stop Recording".
Click the "Start Recording" button to start recording audio input.
Speak into the microphone to provide voice input.
The program will convert the voice input into text using the Google Speech Recognition API and display the detected text in the GUI window.
The detected text will also be saved in a text file with a timestamp in the filename.
You can click the "Stop Recording" button to stop recording audio input.
Features
Records voice input using the microphone.
Converts voice input into text using the Google Speech Recognition API.
Supports English and Hindi languages for voice input.
Displays the detected text in a GUI window.
Saves the detected text in a text file with a timestamp in the filename.
Provides text-to-speech output for the detected text.
Customization
You can change the language for voice input by modifying the lang variable in the code. Currently, it is set to 'en-Us' for English language. You can change it to 'hi-IN' for Hindi language.
You can customize the GUI window appearance by modifying the fnt1 and fnt2 variables, which define the font sizes for different elements in the GUI.
You can add or modify the list of punctuations in the list_of_punctuations dictionary to suit your needs.
Contributing


Acknowledgements
SpeechRecognition - Python library for performing speech recognition tasks.
Pyttsx3 - Python library for text-to-speech conversion.
Tkinter - Python standard library for creating GUI applications.
