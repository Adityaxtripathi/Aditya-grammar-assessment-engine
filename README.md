Aditya Grammar Assessment Engine (Voice Sample Upload)
A simple and powerful tool that analyzes spoken English grammar using AI.
Users upload a voice sample, the app transcribes it using Whisper and evaluates grammar accuracy using LanguageTool — giving a clear score, error count, and transcription.
Perfect for language learners, teachers, and developers building speech-based assessment tools.

🚀 Features
🎤 Upload MP3/WAV voice samples

✍️ Automatic speech‑to‑text transcription (Whisper)

✅ Grammar scoring with error detection

⭐ Clean purple UI layout

⚡ Fast and easy to use

📦 Installation
1. Clone the repository
git clone https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
cd YOUR_REPO_NAME
2. Install required libraries
pip install gradio whisper language-tool-python
If you are using Kaggle, install manually:

!pip install -q gradio language-tool-python
!pip install -q git+https://github.com/openai/whisper.git
3. Install / Update Java for LanguageTool
LanguageTool requires Java 17+:

!apt-get install openjdk-17-jre-headless
▶️ Run the App
python app.ipynb
Then open the link shown in your terminal to access the interface.

📁 Project Structure
├── app.ipynb                 # Main application code
└── README.md              # Project documentation
🧠 How It Works
You upload a voice sample.

Whisper model transcribes your speech to text.

LanguageTool checks the text and finds grammar issues.

The app calculates:

Final score (0–100)

Number of grammar errors

Full transcription

📘 Usage Notes
Works best with clear audio.

Avoid background noise for better transcription.

Engine supports English grammar only (en‑US).

🤝 Contributing
Feel free to open issues or pull requests to improve the UI, scoring logic, or features.



