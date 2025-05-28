# 🧠 Local LLM Chat Interface

A simple, customizable chat interface built with **Streamlit** to interact with local LLM (Large Language Model) backends. Styled for readability with a dark mode theme and persistent chat history.

## 🚀 Features

- 💬 Interactive chat interface with Streamlit
- 🎨 Dark-themed message bubbles (user and assistant)
- 🔧 Sidebar model selection
- 🧠 Local model inference using your own setup
- 📝 Chat history persistence during the session
- ⚡ Displays response time for assistant replies

## 🛠️ Requirements

- Python 3.8+
- Streamlit
- Any backend LLM service (custom or local API)

Install dependencies:
```bash
pip install -r requirements.txt

📁 Folder Structure
bash
Copy
Edit
.
├── main.py               # Streamlit app entry point
├── requirements.txt      # Python dependencies
├── README.md             # Project overview
└── assets/
    └── screenshot.png    # UI preview (optional)

Clone the repository:
git clone https://github.com/yourusername/local-llm-chat.git
cd local-llm-chat

Install dependencies:
pip install -r requirements.txt

Run the Streamlit app:
streamlit run main.py

⚙️Configuration
Ensure your backend LLM endpoint is integrated into the prepare_chat() function in main.py. The model selector will call get_models()—customize this based on your setup.

🧩Customize the UI
Modify the st.markdown() block for custom CSS. Dark mode message styling is included:
.user-msg { background: #1e1e1e; color: #d4f1f9; }
.assistant-msg { background: #2e2e2e; color: #e0ffe0; }

🧠Future Plans
Model config panel (temperature, max tokens)

Chat history download

Support for markdown/rendered responses

🤝 Contributing
Pull requests and suggestions are welcome! Fork this repo and create a PR for any enhancements or fixes.

Let me know if you’d like to include [badges](f), [API integration instructions](f), or a [project logo](f) in the README.







