# reCAPTCHA Solver Using OpenAI and Selenium

## Overview
This Python script automates the process of solving audio-based reCAPTCHAs. It utilizes Selenium for web automation and OpenAI's API for audio transcription.

## Features
- Automates interaction with reCAPTCHA on web pages.
- Utilizes OpenAI's Whisper model for accurate audio transcription.

## Prerequisites
- Python 3.x
- Selenium
- OpenAI API Key
- WebDriver Manager

## Installation
1. Install the required Python libraries:
   ```bash
   pip install selenium webdriver_manager requests openai
   ```
2. Obtain an OpenAI API key and set it in the script.

## Usage
Run the script to automatically navigate to a webpage with reCAPTCHA and solve it:
```bash
python recaptcha_solver.py
```

## Configuration
- Ensure the OpenAI API key is correctly set in the script.
- Modify the target URL as needed within the script.
- Change TITLE if you have another browser language.

## Disclaimer
This script is for educational purposes only. Automated CAPTCHA solving may violate the Terms of Service of some websites. Use responsibly.
