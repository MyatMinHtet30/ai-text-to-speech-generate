🗣️ AI Text-to-Speech Generator

A modern Streamlit-based web app that converts text into lifelike speech using the ElevenLabs API. The app allows users to input text, select language models, customize voice parameters, and generate downloadable audio files.

🚀 Features

🎤 Multiple Voices – Choose from different preset voices (English & Multilingual).

🌐 Language Models – Supports both eleven_monolingual_v1 and eleven_multilingual_v2.

🎛️ Voice Controls – Fine-tune voice with:

Stability (natural tone control)

Similarity Boost (voice character consistency)

📝 Word Limit Enforcement – Supports up to 2500 words per request.

🔊 Playback & Download – Listen directly in-app or download as a .wav file.

🎨 Custom UI Styling – Clean interface with Google Poppins font, styled text areas, and custom buttons.

🛠️ Tech Stack

Streamlit
 – Interactive Python web apps

ElevenLabs API
 – Cutting-edge text-to-speech models

Python
 – Core programming language

Base64
 – For generating downloadable audio links

📦 Installation

Clone the repository

git clone https://github.com/yourusername/ai-tts-generator.git
cd ai-tts-generator


Create and activate a virtual environment (optional but recommended)

python -m venv venv
source venv/bin/activate   # Mac/Linux
venv\Scripts\activate      # Windows


Install dependencies

pip install -r requirements.txt


Set your ElevenLabs API Key

Open the app.py (or main script).

Replace the placeholder with your ElevenLabs API key:

API_KEY = "your_api_key_here"

▶️ Usage

Run the Streamlit app locally:

streamlit run app.py


Then open the local server URL (usually http://localhost:8501) in your browser.

📖 Example Workflow

Enter your text in the text box (max 2500 words).

Select a language model.

Choose a voice (e.g., Rachel, Bella, Antoni, Elli).

Adjust stability and similarity boost sliders.

Click "Generate & Play" to create the audio.

Listen in-app or download as a .wav file.

⚠️ Important Notes

Requires a valid ElevenLabs API key.

Audio generation may take a few seconds depending on text length.

Ensure you comply with ElevenLabs’ Terms of Service
.

👨‍💻 Authors

AI Text-to-Speech Project by:

AK

Kaung Kaung

Kaung Si Thu

Myat Min Htet

📜 License

This project is licensed under the MIT License – free to use and modify with attribution
