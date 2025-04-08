# 🩺 Medical Chatbot – AI-Powered Virtual Medical Assistant

This is a web-based chatbot application designed to provide general medical information. It uses the OpenAI API to generate responses to user questions. The chatbot is based on the GPT-3.5-turbo model and includes logic to filter out non-medical queries.

---

## 🧠 Project Features

- Interactive chatbot embedded in a web interface
- Filters out irrelevant or non-medical queries
- Provides structured responses to general health-related questions
- API key management via `.env` file
- Live chatbox interface with real-time conversation

---

## 🔧 Technologies & Libraries Used

- **Backend:** Python, Django, OpenAI API, spaCy, os, dotenv  
- **Frontend:** HTML, CSS, JavaScript

---

## 🚀 Installation & Usage

1. Clone the repository to your local environment
2. Create a `.env` file with the following content:

```env
OPENAI_KEY='your-api-key-here'
```
3. Start the Django development server:
```
python manage.py runserver
```
4. Open your browser and go to: http://localhost:8000

5. You should see a chat interface titled “WIRTUALNA POMOC MEDYCZNA ONLINE 24/7”. In the bottom-right corner, click the chat icon to start asking questions.
   ![Chat preview](assets/chat-preview.png)
