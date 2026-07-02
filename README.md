# WHATSAPP-AGENT
# 🤖 WhatsApp AI Assistant

An intelligent AI-powered WhatsApp assistant built using n8n, Google Gemini, Pinecone, Supabase, and the WhatsApp Cloud API.

The assistant can receive WhatsApp messages, process them using Google's Gemini AI, store conversation history, maintain long-term memory using vector embeddings, and reply automatically.

---

## 🚀 Features

- 💬 WhatsApp Cloud API Integration
- 🧠 Google Gemini AI Chat Model
- 📚 Long-Term Memory using Pinecone Vector Database
- 🗄️ Conversation Storage with Supabase
- 📊 Google Sheets Logging
- ⚡ Low-code Workflow Automation with n8n
- 🔄 Automatic AI Responses
- 🧩 Modular Workflow Design
- 📈 Easily Extendable for Gmail, Google Calendar, CRM and other APIs

---

## 🛠️ Tech Stack

| Technology | Purpose |
|------------|---------|
| n8n | Workflow Automation |
| Google Gemini | AI Chat Model |
| Pinecone | Vector Database |
| Google Gemini Embeddings | Semantic Embeddings |
| Supabase | Conversation Storage |
| WhatsApp Cloud API | Messaging Platform |
| JavaScript | Data Processing |
| Google Sheets | Logging |

---

## 📂 Workflow

```
WhatsApp User
        │
        ▼
Webhook
        │
        ▼
JavaScript Processing
        │
        ▼
AI Agent (Gemini)
        │
 ┌──────┼────────────┐
 ▼      ▼            ▼
Google  Supabase   Pinecone
Sheets  Database   Memory
        │
        ▼
HTTP Request
        │
        ▼
WhatsApp Reply
```

---

## 🧠 AI Capabilities

- Context-aware conversations
- Semantic memory using vector embeddings
- Automatic response generation
- Conversation logging
- Retrieval-Augmented Generation (RAG)
- Expandable multi-tool architecture

---

## 📁 Project Structure

```
workflow/
docs/
assets/
privacy-policy/
README.md
```

---



## ⚙️ Installation

Clone the repository

```bash
git clone https://github.com/bhavyaraibatra15-hash/whatsapp-ai-assistant-n8n.git
```

Import the workflow into n8n.

Configure the following credentials:

- Google Gemini API
- WhatsApp Cloud API
- Pinecone
- Supabase
- Google Sheets

Activate the workflow.

---

## 🔮 Future Improvements

- Gmail Integration
- Google Calendar Assistant
- Voice Message Support
- Document RAG
- Multi-user Memory
- Image Understanding
- Multi-Agent Architecture
- LangChain Integration

---

## 📜 License

MIT License

---

## 👨‍💻 Author

**Bhavya Rai Batra**

B.Tech Computer Science (AI & ML)

Passionate about Artificial Intelligence, Automation, Multi-Agent Systems, and Building Real-World AI Products.



LinkedIn:
https://www.linkedin.com/in/bhavya-rai-batra-3ba6033bb/

---

⭐ If you found this project helpful, consider giving it a star.
