# 🤖 AI Customer Support Chat

An intelligent, real-time chatbot that serves as a virtual support assistant. It answers customer queries using Groq's LLM APIs integrated via LlamaIndex and a custom UI built with Cursor.

---

## 🚀 Features

- 🧠 Smart AI responses to all types of customer queries
- 📋 Ticket handling interface
- 📚 Knowledge base integration
- 🟢 Real-time chat support
- 💻 Beautiful and responsive UI using Cursor

---

## 🛠️ Technologies Used

- **Backend:**
  - `Groq API` for LLM-based responses
  - `LlamaIndex` for document/question understanding (`vision.py`)
  - `Flask` app for handling requests (`app.py`)

- **Frontend:**
  - UI designed using **Cursor**
  - Live chat interface with message threading and status indicators

---

## 📦 Installation & Setup

Follow the steps below to run the project locally:

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/ai-customer-support-chat.git
cd ai-customer-support-chat

2. Create Virtual Environment (optional but recommended)
    python -m venv venv
    source venv/bin/activate  # On Windows: venv\Scripts\activate
3. Install Dependencies
    pip install -r requirements.txt
    Make sure you have these key libraries installed:

    llama-index

    flask

    openai (Groq API compatible libraries)

    python-dotenv (if using .env for keys)

4. Add Your Groq API Key
    Create a .env file in the root directory and add:
    GROQ_API_KEY=your_api_key_here
    Or you can directly add it in app.py as:

    import os
    os.environ["GROQ_API_KEY"] = "your_api_key_here"
5. Run the Application
    python app.py
    Then, open your browser and navigate to:
    http://127.0.0.1:5000
    You should now see the AI Support Dashboard running with live chat!





