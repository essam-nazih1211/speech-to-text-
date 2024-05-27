# Speech-to-Text Python Project

This project uses the `SpeechRecognition` library to convert speech to text using the Google Web Speech API. The program captures audio input from the user's microphone and transcribes it into text.

## Features

- Captures audio from the user's microphone.
- Uses the Google Web Speech API for speech recognition.
- Handles common errors such as unrecognized speech and request failures.

## Requirements

- Python 3.6 or higher
- `SpeechRecognition` library

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/essam-nazih1211/speech-to-text.git
   cd speech-to-text
   ```

2. **Install the required package:**
   ```bash
   pip install SpeechRecognition
   ```

## Usage

To run the speech-to-text program, simply execute the `speech_to_text.py` file:

```bash
python speech_to_text.py
```

### How It Works

1. The program initializes a `Recognizer` object from the `SpeechRecognition` library.
2. It then captures audio input from the user's microphone.
3. The captured audio is sent to the Google Web Speech API for transcription.
4. The transcribed text is printed to the console.

### Handling Errors

- If the speech is not recognized, the program will print: "Speech Recognition could not understand audio".
- If there is an issue with the API request, the program will print an error message detailing the issue.

## Contributing

If you want to contribute to this project, please fork the repository and create a pull request with your changes.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

## Contact

If you have any questions or feedback, feel free to open an issue in the repository or contact me directly.

---

### Example Output

```
Say something...
Transcription: Hello, how are you?
```

This README file provides all necessary information for setting up and using the speech-to-text project, making it easy to share and collaborate on GitHub.
