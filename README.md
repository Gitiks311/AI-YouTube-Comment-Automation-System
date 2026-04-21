# AI-YouTube-Comment-Automation-System

An automated workflow system built using n8n that:
- Fetches latest YouTube comments
- Filters spam and irrelevant messages
- Generates intelligent, context-aware replies using AI
- Stores and retrieves video knowledge using vector search
- Automatically posts replies back to YouTube

---

## 📌 Project Type
Group Project (n8n-based automation system)


---

##  Key Workflows

### 1. Comment Processing & Auto Reply
- Fetches latest comments via YouTube API
- Filters:
  - Already replied comments
  - Spam / meaningless comments
- Uses AI agent to generate human-like replies
- Posts reply automatically to YouTube
- Stores interaction in database

---

### 2. Knowledge Base Builder (RAG Pipeline)
- Fetches all channel videos
- Extracts:
  - Title
  - Description
  - Metadata
  - Transcript
- Cleans and structures content
- Stores data in Supabase
- Generates embeddings for semantic search

---

##  How It Works (Architecture)

1. Fetch latest YouTube comments  
2. Check if already replied  
3. Classify comment:
   - meaningful / spam  
4. Retrieve context:
   - video transcript  
   - knowledge base  
5. Generate reply using AI agent  
6. Store data in Supabase  
7. Post reply via YouTube API  

---

##  Tech Stack
- **n8n** (workflow automation)
- **OpenAI (GPT models)** – response generation
- **Supabase** – database + vector store
- **YouTube Data API** – comments & video data
- **Embeddings** – semantic search (RAG)

---

##  Features
- Context-aware replies (not generic)
- Multi-language response handling
- Spam filtering pipeline
- Automatic engagement system
- Knowledge-aware AI responses (RAG-based)

---

##  Use Case
- Automates YouTube engagement
- Saves time replying to comments
- Provides accurate answers using video content
- Scales for content creators

---
