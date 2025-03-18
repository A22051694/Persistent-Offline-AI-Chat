# **🚀 Personal CLI AI with Adaptive Memory, File Interaction & Session Management**  

### **📌 Project Overview**  
This is a **command-line AI assistant** designed for **personalized knowledge management, adaptive learning, and flexible interactions**. It integrates **offline AI models (Mistral 7B, Llama 3)** and supports **file-based operations, search, session management, and AI-driven insights**.  

---

## **✨ Features**  

### **💬 Conversational AI**  
✔ Supports **multiple professions** (DevOps, Full-Stack, UI/UX, etc.).  
✔ Handles **complex discussions** with **adaptive learning**.  

### **🧠 Adaptive Memory (Hybrid Learning Mode)**  
✔ **AI learns only with user approval** (Hybrid Adaptive Learning).  
✔ Users can **forget or refine** AI-stored knowledge.  
✔ **Forgetting Example:**  
   ```bash
   forget "Python Flask Deployment"
   ```  

### **📂 File-Based AI Analysis (Without Database Storage)**  
✔ Users **manually specify file paths** (No auto-indexing).  
✔ Supports:  
  - 📌 **Summarization** (Bullet Points, Abstracts)  
  - 🔎 **Keyword & Named Entity Recognition**  
  - 🎭 **Sentiment Analysis**  
  - 📄 **Document Comparison & Similarity Measurement**  
  - 📊 **Table & Form Parsing**  
  - 🎙️ **Speech-to-Text & Emotion Detection**  

### **🗂️ Session Management & Chat History**  
✔ **Automatic & manual session saving**.  
✔ **Reload previous conversations** anytime.  
✔ **Search within chat history** for past discussions.  
✔ **Session recall is adjustable**:  
  - ✅ **Auto-save (Default)**  
  - ✅ **Manual save (On-demand)**  

### **🔍 Powerful Search & Recall**  
✔ Retrieve past discussions & indexed files.  
✔ **Fuzzy search** for typo handling.  

### **🖥️ Interactive Mode & Exporting**  
✔ Runs in **interactive mode** with chat history.  
✔ Exports **chat sessions in JSON, Markdown, or text**.  

### **🔐 Secure & Private**  
✔ AI **does not auto-learn** or store unintended knowledge.  
✔ **No cloud-based storage**—fully offline.  

### **🐳 Docker-Optimized Deployment**  
✔ **Persistent data volumes** ensure AI memory survives container restarts.  
✔ Allows **external database support** if required.  
✔ Model selection via **command-line flags**.  

---

## **🛠️ Commands (When Running `help`)**  

| **📝 Command** | **📌 Description** |  
|------------|--------------|  
| `help` | 📖 Display available commands |  
| `chat` | 💬 Start AI chat mode |  
| `exit` or `quit` | 🚪 Close AI session |  
| `search <query>` | 🔍 Retrieve past discussions |  
| `analyze <file-path>` | 📂 Perform AI-based file analysis |  
| `forget <topic>` | 🗑️ Remove a specific memory from AI |  
| `export <format> <path>` | 📤 Export chat history (JSON, MD, TXT) |  
| `session save` | 💾 Save the current session manually |  
| `session load <session_id>` | 🔄 Reload a previous chat session |  
| `session clear` | 🧹 Delete all chat history |  

---

## **🔮 Future Enhancements**  
🚀 **Full GUI for desktop/mobile**  
🌍 **Browser-based UI (Flask or FastAPI)**  
👥 **Multi-user support** (For advanced users)  

---

## **📌 Final Notes**  
This project provides **offline, AI-powered assistance** with **manual control over learning, session management, and data**. It is designed for **privacy, flexibility, and personal AI-driven productivity**.  

### **🎯 Status: Production-Ready (CLI), GUI Planned for Future**  

