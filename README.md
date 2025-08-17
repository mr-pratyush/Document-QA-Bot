# 📄 Document Q&A Chatbot (GenAI + Hugging Face)

This project is a **Generative AI-powered Document Q&A Chatbot**.  
You can **upload a document (PDF/TXT/CSV)**, and the chatbot will answer your questions based on the document’s content.  
It uses **FastAPI** as the backend, **Hugging Face Transformers** for embeddings and LLM, and a simple **HTML/CSS frontend**.

---

## 🚀 Features
- 📤 **Upload Documents** – Supports PDF, TXT, and CSV files  
- 🤖 **Ask Questions** – Chatbot answers based only on your uploaded document  
- 🧠 **Embeddings + Vector Search** – Finds the most relevant chunks of text before answering  
- ⚡ **FastAPI Backend** – Clean API endpoints for upload & query  
- 🎨 **Simple Frontend** – Minimal HTML + CSS interface  
- 💡 **Uses Free Hugging Face Models** – No paid API required  

---

## 🔍 Preview
<img width="1352" height="858" alt="image" src="https://github.com/user-attachments/assets/87f0e3c3-0eed-4fde-93c7-a208904ce00e"/>

---

## 🧑‍💻 Tech Stack
- **Backend**: FastAPI, Uvicorn  
- **Frontend**: HTML, CSS  
- **Vector Store**: FAISS (in-memory similarity search)  
- **Models**: Hugging Face Transformers  
  - Embeddings → `sentence-transformers/all-MiniLM-L6-v2`  
  - LLM → `google/flan-t5-base`  

---

## 📈 Future Enhancements
- 📂 Add support for multiple documents at once  
- 💾 Store embeddings persistently (instead of in-memory)  
- 🗨️ Add chat history & context memory  
- ☁️ Deploy on **Streamlit**, **Vercel**, or **Hugging Face Spaces**  

---

## 👨‍💻 Author
Built with ❤️ by **Pratyush**  

💼 Senior Analyst | GenAI Developer  
🌐  https://mr-pratyush.netlify.app/
📧 Contact: mr.gautam1508@gmail.com 

---

⚠️ **Note**: For the codebase, please contact me separately as the it is private now.
