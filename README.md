# Speech-to-Speech Translator

This project is an interactive speech-to-speech translator that can translate from Portuguese to English or from English to Portuguese. It allows the user to choose the input language (Portuguese or English), i.e., the first spoken language, uses speech recognition to transcribe the speech, and translates it into the other language (Portuguese or English). It also uses text-to-speech synthesis to play the translated output.

## Installation

Before running the algorithm, make sure to install the required Python libraries using pip:

```bash
pip install SpeechRecognition
pip install googletrans==3.1.0a0
pip install pyttsx3
````
<br>

## How to Use
1. Run the script in a Python environment.
2. The script will prompt you to choose the input language:
> * Type 1 for Portuguese
> * Type 2 for English
3. Speak a phrase in the selected language into the microphone.
4. The script will translate the input and play the translated output using the appropriate voice for the chosen language.

<br>

## Troubleshooting
* If the script fails to recognize or translate the speech, ensure that your microphone is properly connected and functional.

* Check your internet connection since the script relies on Google Translate services for translation.

* If you encounter any issues or have questions, feel free to reach out and provide feedback.
