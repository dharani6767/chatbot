🤖 Nebula AI – Intelligent Chatbot Web Application

Nebula AI is a modern, responsive AI-powered chatbot web application built using Flask (Python) for the backend and HTML, CSS, JavaScript for the frontend.
It uses Google Gemini API to generate intelligent, real-time responses with a beautiful glassmorphism UI.

🚀 Features

✨ Modern futuristic UI with glassmorphism design
🤖 AI-powered conversational assistant (Gemini API)
⚡ Real-time chat interaction
🎨 Fully responsive and animated interface
🌐 REST-based frontend–backend communication
🔐 Secure API integration

🛠️ Tech Stack
Frontend

HTML5

CSS3 (Glassmorphism + Tailwind CDN)

JavaScript (Fetch API)

Font Awesome Icons

Backend

Python

Flask Framework

Google Gemini API (google-generativeai)

📁 Project Structure
📦 nebula-ai-chatbot
 ┣ 📂 templates
 ┃ ┗ 📜 index.html
 ┣ 📜 app.py
 ┣ 📜 requirements.txt
 ┣ 📜 README.md

⚙️ Installation & Setup
1️⃣ Clone the Repository
git clone https://github.com/your-username/nebula-ai-chatbot.git
cd nebula-ai-chatbot

2️⃣ Create Virtual Environment (Optional but Recommended)
python -m venv venv
source venv/bin/activate   # For Linux/Mac
venv\Scripts\activate      # For Windows

3️⃣ Install Dependencies
pip install flask google-generativeai

4️⃣ Set Your API Key

In app.py, replace:

client = genai.Client(api_key="YOUR_API_KEY")


👉 Get your API key from: https://makersuite.google.com/app/apikey

▶️ Run the Application
python app.py


Then open your browser and visit:

http://127.0.0.1:8000

🧠 How It Works

User enters a message in the chat UI.

Frontend sends the message to Flask backend via /chat API.

Flask sends the prompt to Google Gemini AI.

AI response is returned and displayed dynamically in the chat window.

📸 UI Preview

A modern glassmorphism interface with:

Sidebar navigation

Animated chat bubbles

Live AI response loading animation

Beautiful gradient effects

🧪 Example API Endpoint
POST /chat
Content-Type: application/json

{
  "message": "Explain machine learning"
}


Response:

{
  "reply": "Machine learning is a branch of AI that enables systems to learn from data..."
}

🔒 Security Notes

Do NOT expose your API key publicly.

Use environment variables for production.

Add .env to .gitignore.

🌟 Future Enhancements

User authentication

Chat history storage

Multi-model selection

Voice input support

Dark/Light theme toggle

👨‍💻 Author

Dharani Naripeddi
📧 Email: 24pa1a12f8@vishnu.edu.in

🔗 LinkedIn:https://www.linkedin.com/in/dharani-naripeddi-16b6b1321?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app

📜 License

This project is open-source and free to use for educational purposes.
