# Text-to-Voice Converter

A lightweight browser-based text-to-speech application built with **HTML, CSS, JavaScript, and the Web Speech API**.

Users can type text, choose one of the voices available in their browser or operating system, and listen to the text as synthesized speech.

## Live Demo

https://sankalp-gupta1.github.io/Text-to-Voice-Converter/

## Features

- Text input for speech generation
- Browser voice selection
- Automatic loading of available system voices
- Multi-language / accent support based on installed voices
- Responsive interface
- No backend required
- No external text-to-speech API required

## How It Works

```text
User enters text
      │
      ▼
Select browser/system voice
      │
      ▼
SpeechSynthesisUtterance
      │
      ▼
Browser Speech Synthesis Engine
      │
      ▼
Audio playback
```

## Tech Stack

- HTML5
- CSS3
- JavaScript
- Web Speech API
- GitHub Pages

## Project Structure

```text
Text-to-Voice-Converter/
├── index.html
├── styles.css
├── script.js
├── img/
└── README.md
```

## Run Locally

Clone the repository:

```bash
git clone https://github.com/Sankalp-gupta1/Text-to-Voice-Converter.git
cd Text-to-Voice-Converter
```

Open `index.html` in a modern browser.

You can also use a local static server such as VS Code Live Server.

## Usage

1. Enter text in the text area.
2. Select a voice from the dropdown.
3. Click the speech/play button.
4. The browser reads the text using the selected voice.

## Browser Support

Voice availability depends on the browser and operating system because the application uses the device's built-in speech synthesis voices.

## Author

**Sankalp Gupta**

GitHub: https://github.com/Sankalp-gupta1
