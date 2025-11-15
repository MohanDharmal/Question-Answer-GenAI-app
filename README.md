# Question-Answer-GenAI-app
🚀 LangChain + Gemini Simple Question-Answer-GenAI-app (Streamlit App)
A simple and powerful chatbot built using LangChain, Google Gemini, and Streamlit. This project demonstrates how to integrate Google’s Gemini 2.5 Flash model with a clean prompt pipeline and a web-based UI.

✨ Features

🧠 Google Gemini 2.5 Flash for fast and reliable responses
🔗 LangChain for prompt management & model integration
🌐 Streamlit for a simple and interactive UI
🛠️ Environment-based API Key management
⚡ Real-time question answering

📂 Project Structure

.
├── app.py
├── .env
├── requirements.txt
└── README.md

🔧 Installation & Setup
1. Clone the Repository
git clone https://github.com/MohanDharmal
Question-Answer-GenAI-app/your-repo.git
cd your-repo
2. Create and Activate a Virtual Environment
python -m venv venv
venv\Scripts\activate
3. Install Dependencies
pip install -r requirements.txt
4. Add Your API Keys
Create a .env file in the project folder:
GOOGLE_API_KEY=your_google_api_key
LANGCHAIN_API_KEY=your_langchain_api_key
▶️ Run the App
Start the Streamlit server:
streamlit run app.py
Your app will open in the browser at:
http://localhost:8501

🔑 IMPORTANT: Add Your API Keys

Create a '.env' file in the project directory and add your own API keys:
GOOGLE_API_KEY=your_google_api_key_here
LANGCHAIN_API_KEY=your_langchain_api_key_here

⚠️ Note:
You must use your personal Google API Key and LangChain API Key.
Without these keys, the chatbot will not work.
