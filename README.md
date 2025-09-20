# Voice-Assistant-AI

## Overview

A Python-based AI voice assistant leveraging ElevenLabs conversational API for natural voice interaction and dynamic responses. Designed for real-time audio input/output and secure integration of API credentials via environment variables.

## Features

- Real-time speech recognition and synthesis  
- Customizable conversational flow using ElevenLabs  
- Secure API key management (.env support)  
- Callback-driven agent response handling

## Installation

1. Install dependencies: pip install elevenlabs elevenlabs[pyaudio] python-dotenv
2. Create a `.env` file in the root folder:AGENT_ID=your_agent_id
ELEVENLABS_API_KEY=your_api_key
3. Run: python voice_assistant.py


## Usage

- Start the assistant script from terminal.  
- Respond to audio prompts and interact via speech.
- Customize prompts and conversation logic in `voice_assistant.py`.

## Troubleshooting

- Ensure `.env` variable names match the script (`AGENT_ID` and `ELEVENLABS_API_KEY`).  
- Double-check API key/agent validity.  
- Verify microphone/speaker connections.

## Project Structure

AI_voice_assistant/
├── voice_assistant.py
├── .env
├── README.md


## License

MIT License

## Acknowledgments

- ElevenLabs API documentation  
- Python, dotenv and pyaudio libraries


 
