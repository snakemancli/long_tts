Long-form content processor

This script processes content by generating TTS audio, combining it with background music, and creating a video from images. It uses several Python libraries to achieve this.

## License

This project is licensed under the Zero-Clause BSD license.

## Requirements

- Python 3.x
- ffmpeg
- pydub
- openai

## Setup

### Using a Virtual Environment

It is recommended to use a virtual environment to manage dependencies. Follow these steps to set up the project:

1. **Create a virtual environment:**
   ```bash
   python -m venv venv
   source venv/bin/activate
   pip install ffmpeg-python pydub openai
   export OPENAI_API_KEY=your_api_key_here
   python long_tts.py
