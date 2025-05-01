# 🔍 BadgerSearch – Oracle Cloud Search System

**BadgerSearch** is a modular cloud-based search platform developed in **Google Colab using Python**, with **Firebase** as the backend.  
The system crawls content from the Oracle documentation site, indexes and stores it in JSON format, provides chatbot interaction, and displays useful statistics via visualizations — all designed to simulate a microservices architecture.

---

## 🌐 Live Notebook

▶️ [Open in Google Colab](https://colab.research.google.com/drive/1pQCkM-DXVlDmNmDWWTv5PLsH19PMh875?usp=sharing)

---

## 🧩 Key Features & Modules

### 🗣️ Chatbot Module
- Hardcoded chatbot that provides answers to pre-defined user prompts using indexed data.
- Pulls relevant content directly from Firebase in real time.

### 🔥 Firebase Integration
- Handles all database operations: storing crawled content, managing indexes, and syncing updates.
- Serves as the real-time backend for data persistence.

### 📦 JSON Data Analyzer
- Reads and writes JSON-formatted documents from Oracle pages.
- Parses and structures content for efficient search and retrieval.

### 🧑‍💼 Admin Panel Logic
- Enables updating and deleting indexes from the database.
- Controls audio content list used in the embedded music player.

### 📊 Statistics Dashboard
- Displays:
  - Top 10 most common words in crawled content
  - Most frequently searched user queries
- Helps identify trends and content relevance.

### 🎵 Music Player
- Streams songs hosted in the GitHub repository.
- Built-in audio control logic for playback across all app components.

---

## 🧱 Simulated Microservices Architecture

Despite being implemented in a unified Colab environment, the system is organized in a modular, microservice-inspired structure:

| Service                     | Description                                                                 |
|-----------------------------|-----------------------------------------------------------------------------|
| Oracle Crawler              | Extracts content from Oracle site and stores it in structured JSON format. |
| Query Handler               | Searches Firebase for matching results based on user input.                |
| Visualization Service       | Analyzes and presents statistical metrics as graphs.                       |
| Admin Management            | Updates/deletes index entries via admin-only logic.                        |
| Chatbot Query Response      | Responds to predefined questions using stored data.                        |

---

## 🚀 Technologies Used

- **Environment**: Google Colab (Python)
- **Database**: Google Firebase Realtime DB
- **Data Format**: JSON
- **Key Libraries**:  
  `firebase-admin`, `matplotlib`, `collections`, `re`, `pprint`


---

## 🧠 Lessons Learned

- Simulated a scalable microservices architecture using modular Python logic
- Implemented cloud database operations via Firebase
- Developed a functioning chatbot with real-time search capabilities
- Visualized data insights using custom graphs and analysis
- Managed real-time audio content and admin-side data control

---

> _"Search is not just about answers — it’s about understanding."_
