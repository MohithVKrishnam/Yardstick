# Yardstick

# Conversation Management & Classification using Groq API

This repository contains the implementation of an internship assignment to manage conversation history, summarize chats, and extract structured information from user messages using Groq API and OpenAI-compatible SDK.  

---

## Assignment Overview

**Objective:**  
Implement two core tasks using Groq APIs (with OpenAI SDK compatibility):  

### 1. Conversation Management & Summarization
- Maintain running conversation history between user and assistant.
- Summarize conversations periodically to keep history concise.
- Truncate conversation history by number of turns or by character/word length.
- Demonstrate periodic summarization (e.g., after every k-th run).  

### 2. JSON Schema Classification & Information Extraction
- Extract key details (name, email, phone, location, age) from user chats.
- Use OpenAI function calling (compatible with Groq API) for structured JSON outputs.
- Validate extracted outputs against a predefined JSON schema.
- Demonstrate extraction on multiple sample chats.

---

## Tech Stack

- Python 3.x  
- Standard Python libraries (`os`, `json`, `re`, `uuid`, `dataclasses`)  
- OpenAI SDK (compatible with Groq API)  
- Google Colab for execution  

**No frameworks** were used, only standard Python + OpenAI client.

---

## Installation / Setup

1. Clone the repository:  
```bash
git clone <your-github-repo-url>
cd <repo-folder>
