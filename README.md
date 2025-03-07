
# 📄✨ **GeminiPDF-Chat: AI-Powered PDF Q&A** 🤖📚  

## 🚀 **Project Overview**  
Ever struggled to **find information quickly** in long PDFs? **GeminiPDF-Chat** lets you **upload single or multiple PDFs** and ask **any questions** about the content. 💡 The **LLM (Google Gemini Pro)** will process the documents and fetch **precise answers** from them! 🔥  

---

## 🎯 **Objective**  
✅ **Instantly retrieve answers** from large PDFs 📑  
✅ **Chat with multiple documents** at once 💬  
✅ **AI-powered understanding** of complex texts 🤖  
✅ **Save time** searching for key information ⏳  

---

## 🏗 **Tech Stack**  
🖥 **Frontend:** HTML, CSS,  
🐍 **Backend:** Flask (Python)  
📄 **PDF Processing:**  `PyPDF2`  
🔍 **Vector Search:** FAISS  (for efficient retrieval)  
🧠 **LLM (AI Model):** Google **Gemini Pro**  
📡 **Hosting:** Render / Vercel / AWS  

---

## 🔍 **How It Works?**  
1️⃣ **Upload PDFs** – Drop one or multiple PDFs into the web app.  
2️⃣ **Preprocessing** – The PDFs are parsed into **text chunks**.  
3️⃣ **Embedding & Storage** – Text is **vectorized** and stored in **FAISS/ChromaDB** for fast searching.  
4️⃣ **Ask a Question** – Users input a query related to the PDF.  
5️⃣ **AI-Powered Answering** – The **LLM** retrieves relevant text from the PDF and generates a **precise answer**.  

---

## 📜 **Installation & Setup**  
### 1️⃣ **Clone the Repository**  
```bash
git clone https://github.com/your-username/GeminiPDF-Chat.git  
cd GeminiPDF-Chat
```

### 2️⃣ **Install Dependencies**  
```bash
pip install flask google-generativeai PyMuPDF chromadb
```

### 3️⃣ **Set Up API Keys**  
Create a `.env` file and add your **Google Gemini API Key**:  
```bash
GEMINI_API_KEY="your-api-key-here"
```

### 4️⃣ **Run the Application**  
```bash
python app.py
```

### 5️⃣ **Open in Browser**  
Visit: `http://127.0.0.1:5000/` 🎯  

---

## 🛠 **Features**  
📤 **Upload Single or Multiple PDFs** – Handles multiple documents at once.  
🔍 **Ask Any Questions** – AI fetches the exact data from PDFs.  
🤖 **Google Gemini Pro (or GPT-4)** – Smart text understanding.  
📋 **Efficient Search** – Vector storage for faster results.  
🌐 **User-Friendly Web UI** – Simple & responsive design.  

---

## 📈 **Future Enhancements**  
🔹 **Summarization Feature** – Get a concise summary of your PDFs.  
🔹 **Multiple File Formats** – Support for Word, TXT, and more.  
🔹 **Browser Extension** – Chat with PDFs directly from your browser.  
🔹 **Memory Feature** – Save past conversations for future reference.  
🔹 **Speech-to-Text Support** – Ask questions via voice input.  

---

## 🏁 **Conclusion**  
🔍 **GeminiPDF-Chat** makes working with PDFs effortless. Whether you're a **student, researcher, or professional**, get **quick insights** from **multiple documents** without manually searching through pages. 📄💡  

