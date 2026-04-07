# AI Ethics RAG Chatbot 

##  Project Overview
This project is an AI-powered Retrieval-Augmented Generation (RAG) chatbot built using Flowise. It is designed to answer questions based on documents related to Artificial Intelligence Ethics.

The chatbot retrieves relevant information from documents and generates accurate, context-based responses.

---

##  Objective
- To apply AI in real-world problem solving
- To improve document-based question answering
- To ensure ethical and responsible AI responses

---

##  Tech Stack
- Flowise AI
- Mistral AI (LLM)
- Google Gemini Embeddings
- Vector Store (In-Memory)
- Conversational Retrieval QA Chain

---

##  Workflow Explanation

1. **File Loader**
   - Loads the AI ethics document

2. **Text Splitter**
   - Splits document into smaller chunks for processing

3. **Embeddings**
   - Converts text into vector format using Gemini

4. **Vector Store**
   - Stores embeddings for similarity search

5. **Retriever**
   - Fetches relevant content based on user query

6. **Chat Model (Mistral)**
   - Generates responses using retrieved context

7. **Conversational Chain**
   - Maintains chat history for better interaction

---

##  Key Features
- Context-aware responses
- Ethical AI-focused knowledge
- Conversational memory
- Prevents hallucination (answers only from documents)

---

##  Screenshots

### 🔹 Flowise Workflow
[Workflow Configuration] <img width="1885" height="868" alt="Flowise" src="https://github.com/user-attachments/assets/d0b9b80d-d8c2-4776-affd-c797e9ac242f" />


### 🔹 Chatbot Interaction
[Chat Output 1]<img width="1200" height="858" alt="Output1" src="https://github.com/user-attachments/assets/e62f33b8-44fc-4b29-b07f-d7a78fae7033" />

[Chat Output 2]<img width="1156" height="841" alt="Output2" src="https://github.com/user-attachments/assets/37f79460-19c0-460f-b73f-af21a60e0579" />

[Chat Output 3]<img width="1164" height="840" alt="Output3" src="https://github.com/user-attachments/assets/9ce31764-fd48-4bea-8289-52568d4146aa" />

---

---

##  Project Files
- Chatflow JSON (Flowise)
- AI Ethics document
- Screenshots

---

##  How to Run

1. Open Flowise
2. Import the JSON file from `/chatflow`
3. Add API keys:
   - Mistral API
   - Google Gemini API
4. Upload document
5. Run chatbot

---

##  Future Improvements
- Add database (Pinecone / FAISS)
- Deploy chatbot on web
- Add multi-document support

---

##  Author
Jhanvi Sabharwal

---

##  License
This project is for educational purposes.
