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

📷 ![image](https://github.com/user-attachments/assets/53d43228-fc53-493c-bbd9-ed101c62c209)
    ![image](https://github.com/user-attachments/assets/2aaf9673-9b6e-490c-891b-c3fe023f5a35)
    ![image](https://github.com/user-attachments/assets/7a1ec78f-0cfd-42b6-9dd6-0a19c962c0f0)


🙌 Credits
Groq – for the powerful LLM APIs

LlamaIndex – for making data integration easy

Cursor – for the sleek front-end design

Developed by: Hammad Hassan

📬 Contact
For queries or freelance work:

📧 Email: hammadblti302@gmail.com

🌐 Linkedin: https://www.linkedin.com/in/hammad-hassan-52a054360/ 

📝 License
This project is licensed under the MIT License. Feel free to use, modify, and distribute it.







