# Gemini Multimodal Chatbot

A free, easy-to-use chatbot web application powered by Google's Gemini 1.5 Flash model. This Streamlit app supports both **text-only prompts** and **image + text prompts**, making it a versatile tool for experimenting with Generative AI.

## ✨ Features
- 💬 Text chatbot: Ask any question and get instant AI-generated responses.
- 🖼️ Image chatbot: Upload an image along with a prompt to get context-aware answers.
- ⚡ Uses `gemini-1.5-flash-latest` (free-tier friendly)
- 🧪 Built using Python, Streamlit, and Google's Generative AI SDK
- 🔐 Secure API key usage with `.env` file

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/gemini-multimodal-chatbot.git
   cd gemini-multimodal-chatbot
2. Create a .env file and add your API key:
    GOOGLE_API_KEY=your_api_key_here
3. Install dependencies:
    pip install -r requirements.txt

4. Run the app
    streamlit run app.py
