# Automated Chat Responder Bot

## Overview
This project is a Python script that automates chat interactions by:
- Selecting and copying text from a chat application using mouse movements.
- Using the OpenAI API to generate witty, personalized responses.
- Pasting and sending the generated responses back into the chat.

## Features
- **Automated UI Interaction**: Uses `pyautogui` to simulate mouse clicks, drags, and keyboard actions.
- **Clipboard Management**: Retrieves and manages clipboard content with `pyperclip`.
- **AI Integration**: Leverages OpenAI's GPT model for generating conversational responses.
- **Humor Generation**: Designed to analyze chat history and generate humorous roasts.

## How It Works
1. **UI Automation**: The bot clicks a specified location to open a chat window.
2. **Text Selection**: It drags the mouse to select and copy the latest chat text.
3. **AI-Powered Reply**: Sends the chat history to OpenAI's API and retrieves a response.
4. **Automated Reply**: Pastes the AI-generated reply into the chat and sends it.

## Requirements
- Python 3.8+
- Installed libraries (see `requirements.txt`):
  - `pyautogui`
  - `pyperclip`
  - `openai`

## Usage
1. Install the required dependencies:
   ```bash
   pip install -r requirements.txt

## Notes
Ensure you grant accessibility permissions for automation on macOS.
Customize the script with the appropriate screen coordinates.
