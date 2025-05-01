# 🔍 BadgerSearch – Cloud-Based Oracle Crawler & Search System

**BadgerSearch** is a modular cloud-based search platform developed using Python in Google Colab.  
It crawls, indexes, analyzes, and serves data from the Oracle documentation website, utilizing Firebase as the backend data store.  
The system includes chatbot interaction, admin controls, statistical visualization, and multimedia integration.

---

## 🧩 Key Features & Modules

### 🗣️ Chatbot Module
- Hardcoded chatbot that pulls context-relevant data from Firebase using pre-defined prompts.
- Provides fast, formatted responses to frequently asked queries.

### 🔥 Firebase Database Integration
- Centralized management of all read/write/update/delete operations via Firebase.
- Enables real-time data handling from Colab scripts and modules.

### 📦 JSON Analyzer
- Reads, parses, and transforms crawled data in JSON format for processing and storage.

### 🧑‍💼 Admin Panel Functionality
- Admin logic enables management of indexed content and audio playlist entries.
- Supports update/delete operations directly on Firebase.

### 📊 Statistics Module
- Displays dynamic metrics such as:
  - Top 10 most frequent words from Oracle content
  - Most common search queries from users

### 🎵 Music Playback Integration
- Embedded audio player streams tracks directly from the project’s GitHub repository.
- Playback functionality was implemented across all user-facing pages.

---

## 🧱 Microservices Logic

While developed in a single environment, the system architecture simulates microservices via modular Python notebooks/scripts:

1. **Oracle Crawler Service** – Extracts and structures content from Oracle documentation.
2. **Query Search Service** – Handles user queries and retrieves relevant results from Firebase.
3. **Visualization Service** – Generates graphs based on user behavior and data metrics.
4. **Admin Index Management** – Allows authorized updates and deletions of indexed entries.
5. **Chatbot Interface Service** – Responds to user prompts using stored indexed content.

---

## 🚀 Technologies Used

- **Development Environment**: Google Colab (Python-based)
- **Database**: Google Firebase (Realtime Database)
- **Data Format**: JSON
- **Tools**: `firebase-admin`, `matplotlib`, `collections`, custom crawlers
- **Version Control**: GitHub

---

## 🧠 Lessons Learned

- Built a simulated microservices system using modular Python logic inside Colab
- Integrated Firebase as a remote database for persistent structured storage
- Designed an interactive chatbot capable of structured responses using indexed data
- Created real-time statistics and visualizations for content and user query trends

---

> _"Search is not just about answers — it’s about understanding."_
