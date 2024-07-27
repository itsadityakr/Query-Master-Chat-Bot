
# Query Master - Chat Bot

## Overview

This repository contains a Python script that creates a chatbot interface using OpenAI's GPT-3.5 Turbo model. The chatbot, named "Master," allows users to have text-based conversations and offers the option to have responses spoken aloud using text-to-speech (TTS). The script includes a rate limiting mechanism to control the number of responses per minute.

## Prerequisites

Before using this chatbot interface, ensure you have the following prerequisites installed:

1.  **Python**: Install Python from the official [Python website](https://www.python.org/).
2.  **OpenAI Python Library**: Install the OpenAI Python library:
    
    `pip install openai` 
    
3.  **pyttsx3**: Install the pyttsx3 library for text-to-speech functionality:
        
    `pip install pyttsx3` 
    
4.  **OpenAI API Key**: Obtain an OpenAI API key and replace the placeholder API key in the script with your own.

## Usage

1.  Clone the repository to your local machine:
    
    `git clone https://github.com/yourusername/openai-chatbot-interface.git` 
    
2.  Navigate to the project directory:
    
    `cd ai-chatbot` 
    
3.  Open the `chatbot.py` script in a text editor or IDE of your choice.
4.  Replace the placeholder OpenAI API key in the `openai.api_key` line with your own key.
5.  Run the script:
    
    `python_ai_chatbot.py` 
    
6.  The chatbot interface will start. Enter your messages in the terminal, and the chatbot will respond accordingly. To quit the interface, enter `quit()`.
7.  Optionally, when prompted, you can choose to have the chatbot's responses spoken aloud by typing "Y" or "N."

## Rate Limiting

The script includes a rate limiting mechanism to ensure compliance with OpenAI's API rate limits. If you send more than two messages within a minute, the script will pause and wait for a minute before allowing further responses.

## Customization

You can customize the chatbot's behavior by modifying the `system_msg` variable to set a different chatbot type.

## Disclaimer

This script is intended for educational purposes and may require proper authorization and compliance with OpenAI's terms of use, including rate limits and usage policies. Review OpenAI's documentation and policies before using this script in any production or commercial applications.

## Author

Aditya Kumar

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## How to Get an OpenAI API Key

To get an OpenAI API key, follow these steps:

1.  **Sign Up/Login**:
    
    -   Go to the [OpenAI website](https://www.openai.com/).
    -   Sign up for an account or log in if you already have one.
2.  **Navigate to API Keys**:
    
    -   After logging in, go to the [API Keys page](https://platform.openai.com/account/api-keys).
3.  **Create a New API Key**:
    
    -   Click on the "Create new secret key" button.
    -   A new API key will be generated. Copy this key as it will be shown only once.
4.  **Store the Key Securely**:
    
    -   Save the API key securely. You will need this key to access OpenAI's API.
5.  **Use the API Key in Your Script**:
    
    -   Replace the placeholder API key in your script with the one you generated. For example, in your `chatbot.py` script, update the line:
        
        `openai.api_key = 'your-openai-api-key'` 
        
    -   Replace `'your-openai-api-key'` with the actual key you copied.

Remember to keep your API key confidential and do not share it publicly to prevent unauthorized usage.
