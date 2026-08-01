# Medical Chatbot using LangChain & Hugging Face

A medical question-answering chatbot that retrieves relevant information from medical documents and generates context-aware responses using Large Language Models (LLMs), semantic search, and vector embeddings.

---

# Overview

This project enables users to ask questions about medical information contained in documents such as textbooks, research papers, and healthcare PDFs.

Instead of relying solely on a language model, the system retrieves the most relevant content from uploaded documents before generating an answer, improving accuracy and relevance.

---

# Features

- 📄 Process medical PDF documents
- 🔍 Semantic document retrieval
- 💬 Context-aware question answering
- 🧠 LLM-powered responses
- ⚡ Fast vector search using Pinecone
- ☁️ Ready for cloud deployment

---

# Tech Stack

- **Python**
- **LangChain**
- **OpenAI / Cohere** (LLMs)
- **Hugging Face** (Embeddings)
- **Pinecone** (Vector Database)
- **Flask**
- **Hugging Face Spaces** (Deployment)

---

# Project Structure

```text
Medical-Chat-Bot-With-LLMs-Langchain-AWS/
│
├── src/
│   ├── __init__.py
│   ├── helper.py
│   └── prompt.py
│
├── research/
│   └── trials.ipynb
│
├── app.py
├── setup.py
├── requirements.txt
├── template.sh
└── README.md
```

---

# How It Works

1. Upload medical PDF documents.
2. Extract and split text into manageable chunks.
3. Generate vector embeddings using Hugging Face models.
4. Store embeddings in Pinecone.
5. Retrieve the most relevant document sections based on the user's query.
6. Generate an answer using an LLM with the retrieved context.

---

# Installation

### Clone the Repository

```bash
git clone https://github.com/ARJUN-AIML/Medical-Chat-Bot-With-LLMs-Langchain-AWS.git
```

### Navigate to the Project

```bash
cd Medical-Chat-Bot-With-LLMs-Langchain-AWS
```

### Create a Virtual Environment

```bash
conda create -n medibot python=3.10 -y
conda activate medibot
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

---

# Environment Variables

Create a `.env` file in the project root.

```env
OPENAI_API_KEY=your_api_key
PINECONE_API_KEY=your_api_key
```

---

# Run the Application

```bash
python app.py
```

---

# Future Enhancements

- Support multiple document collections
- Conversation history
- Voice interaction
- Source citation for responses
- Improved user interface
- Authentication and user management

---

# License

This project is licensed under the MIT License.

---

# Author

**Arjun S**

B.E. Artificial Intelligence and Machine Learning

Saranathan College of Engineering