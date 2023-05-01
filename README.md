# Voice Enabled Chatbot

This repository contains a voice-enabled chatbot based on OpenAI's API text-davinci-003. You can talk and chat with this chatbot as if you were conversing with a person. The chatbot is available in both GUI and non-GUI versions, providing flexibility to suit your preferences.

## Getting Started

Follow these steps to set up and run the chatbot:

1. Clone this repository:
```
git clone https://github.com/shahdivax/VoiceEnabled_Chatbot.git
```

2. Change into the project directory:
```
cd VoiceEnabled_Chatbot
```

3. Install the required dependencies:
```
pip install -r requirements.txt
```

4. Obtain your OpenAI API key from [OpenAI Platform API Keys](https://platform.openai.com/account/api-keys) and set it as an environment variable:

For Linux or macOS:
```
export OPENAI_API_KEY="Your_API_Key"
```

For Windows:
```
setx OPENAI_API_KEY "Your_API_Key"
```

5. Run the GUI version of the chatbot:
```
python voicebot_with_GUI.py
```

Alternatively, to run the non-GUI version, open the `voicebot_without_GUI.py` file and replace `"Your_API_Key"` with your actual OpenAI API key. Then, run the following command:

```
python voicebot_without_GUI.py
```

## Features

- Voice-enabled interaction, providing a more natural and engaging experience
- Powered by OpenAI's advanced text-davinci-003 model
- Available in both GUI and non-GUI versions
- Easy setup and configuration

## Acknowledgements

- Thanks to OpenAI for providing the text-davinci-003 API
- Special thanks to the developers of the libraries and tools used in building this chatbot
