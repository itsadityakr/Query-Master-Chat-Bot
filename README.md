# ai-chatbot
OpenAI Chatbot Interface - README
Overview
This repository contains a Python script that creates a chatbot interface using OpenAI's GPT-3.5 Turbo model. The chatbot is named "Assistant Friday" and allows users to have text-based conversations with it. Additionally, it offers the option to have the chatbot's responses spoken aloud using text-to-speech (TTS). The script also includes a rate limiting mechanism to control the number of responses per minute.
<br>
Prerequisites
Before using this chatbot interface, you'll need to have the following prerequisites installed:

Python: You should have Python installed on your system. You can download it from the official Python website.

OpenAI Python Library: Install the OpenAI Python library by running the following command:
pip install openai

pyttsx3: Install the pyttsx3 library for text-to-speech functionality:
pip install pyttsx3
OpenAI API Key: You must have an OpenAI API key to access the GPT-3.5 Turbo model. Replace the placeholder API key in the script with your own.

Usage
Clone the repository to your local machine:

git clone https://github.com/yourusername/openai-chatbot-interface.git
Navigate to the project directory:

cd openai-chatbot-interface
Open the chatbot.py script in a text editor or IDE of your choice.

Replace OpenAI API key in the openai.api_key line.

Run the script:

python_ai_chatbot.py
The chatbot interface will start, and you can have conversations with "Assistant Friday." Enter your messages in the terminal, and the chatbot will respond accordingly. You can quit the interface by entering "quit()".

Optionally, when prompted, you can choose to have the chatbot's responses spoken aloud by typing "Y" or "N."

Rate Limiting
The script includes a rate limiting mechanism to ensure that you don't exceed the rate limits imposed by the OpenAI API. If you send more than two messages within a minute, the script will pause and wait for a minute before allowing further responses.

Customization
You can customize the chatbot's behavior by modifying the system_msg variable to set a different chatbot type.

Disclaimer
This script is intended for educational purposes and may require proper authorization and compliance with OpenAI's terms of use, including rate limits and usage policies. Make sure to review OpenAI's documentation and policies before using this script in any production or commercial applications.

Author
Aditya Kumar

License
This project is licensed under the MIT License - see the LICENSE file for details.
