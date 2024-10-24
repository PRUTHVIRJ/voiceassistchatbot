# Voice Assistant Conversational Chatbot

This project demonstrates a **Voice Assistant Conversational Chatbot** that provides seamless, real-time voice interactions using speech-to-text, natural language processing (NLP),Large Language Model(LLM), and text-to-speech technologies. It captures user voice inputs, processes them using NLP models, and responds interactively through a user-friendly web interface.

## Features

- **Real-time Voice Interaction**: Supports continuous, context-aware conversations with users.
- **Speech Recognition**: Captures and converts user voice input into text using the `SpeechRecognition` library.
- **Natural Language Processing (NLP)**: Processes text input and generates responses using Groq's NLP models, ensuring context-aware and relevant replies.
- **Text-to-Speech Conversion**: Converts text responses into speech using `gTTS (Google Text-to-Speech)` for natural and engaging interaction.
- **Audio Playback**: Plays back the audio response to the user using `PyAudio`.
- **Web Interface**: A simple and intuitive interface built with `Streamlit` for ease of use, allowing users to interact with the chatbot via a web browser.

## Technologies Used

- **Streamlit**: Used to create the web-based interface for the chatbot, providing an easy-to-use platform for users to interact with the assistant.
- **SpeechRecognition**: Handles the conversion of spoken language into text, enabling the chatbot to understand and process voice inputs from users.
- **Groq API**: Powers the natural language understanding and context-aware response generation, making the chatbot's interactions intelligent and coherent.
- **gTTS (Google Text-to-Speech)**: Converts text responses from the chatbot into spoken language for natural-sounding voice responses.
- **PyAudio**: Facilitates real-time audio input and output, capturing voice input and playing back the chatbot's responses.

## Installation
# 1. Install the required dependencies:
```bash
pip install -r requirements.txt
```
# 2. Run the application:
``bash
streamlit run app.py


# Skills Developed
* Python: Core language for implementing the chatbot logic, integrating libraries, and handling API interactions.
* Natural Language Processing (NLP): Used to process voice input and generate context-aware responses.
* User Interface Design: Developed a simple yet effective web interface using Streamlit.
* Machine Learning: Integrated machine learning-based NLP models for intelligent conversation handling.

# How It Works
1.The user interacts with the chatbot via the Streamlit web interface, providing voice input.
2.The voice input is captured using the SpeechRecognition library and converted into text.
3.The Groq NLP API processes the text, generating a context-aware response.
4.The response is converted back into speech using gTTS and played to the user using PyAudio.
5.The conversation continues in real-time with the chatbot responding to further queries seamlessly.
