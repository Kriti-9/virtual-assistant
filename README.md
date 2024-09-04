
# Voice Assistant

This Python-based voice assistant leverages various libraries to interact with the user through speech recognition and text-to-speech technologies. It performs multiple tasks, including searching the web, playing music, managing notes, and more. 

## Features

- **Greeting & Personalization**: Greets the user and remembers names for both the assistant and the user.
- **Time Inquiry**: Provides current time in a user-friendly format.
- **Web Search**: Searches Google and YouTube for specified terms.
- **Stock Price Lookup**: Retrieves stock prices from Google.
- **Music & Media**: Plays music on Spotify, opens Instagram, Twitter, and other sites.
- **Weather Report**: Fetches and reads out the weather conditions.
- **Screenshots**: Captures and saves screenshots of the screen.
- **Games & Fun**: Includes games like Rock-Paper-Scissors and Coin Toss.
- **Calculator**: Performs basic arithmetic operations.
- **Wikipedia Definitions**: Searches for definitions on Wikipedia.
- **Note-taking**: Opens Google Keep for note-taking.
- **Email**: Opens Gmail to check emails.

## Libraries Used

- `speech_recognition`: For recognizing and converting speech to text.
- `playsound`: For playing audio files.
- `gtts`: For converting text to speech.
- `pyttsx3`: For text-to-speech conversion.
- `pyautogui`: For taking screenshots.
- `PIL`: For handling image files.
- `bs4`: For web scraping.
- `urllib.request`: For making HTTP requests.
- `webbrowser`: For opening URLs in a web browser.
- `random`: For generating random choices in games.
- `time`: For handling time-related tasks.
- `os`: For file management.

## Installation

Make sure to install the required libraries using pip:

```bash
pip install SpeechRecognition playsound gtts pyttsx3 pyautogui pillow beautifulsoup4 urllib3
```

## How to Use

1. **Run the Script**: Execute the main Python script to start the voice assistant.
2. **Interact with the Assistant**: Speak commands or queries into the microphone.
3. **Available Commands**:
   - Greeting: "Hey", "Hi", "Hello"
   - Get Time: "What's the time?"
   - Search Google: "Search for [term]"
   - Play Music: "Play music for [song]"
   - Weather: "What's the weather like?"
   - Take Screenshot: "Take a screenshot"
   - Games: "Play rock-paper-scissors" or "Toss a coin"
   - Definitions: "Definition of [term]"
   - And more!

## Notes

- Ensure your microphone and speakers are properly set up for optimal performance.
- Some functionalities, like taking screenshots and saving files, require specific paths or configurations in the script.

## Example Commands

- "Hey, how are you?"
- "What's the time?"
- "Search for Python programming"
- "Play music for No Suprises"
- "What's the weather like today?"
- "Take a screenshot"
- "Definition of Python"
