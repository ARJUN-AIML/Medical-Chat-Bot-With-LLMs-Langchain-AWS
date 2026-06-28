# Medical Chatbot with LLMs using LangChain & HuggingFace

An end-to-end AI-powered medical chatbot that provides intelligent responses to user queries based on medical documents using Large Language Models (LLMs), vector embeddings, and semantic search.

---

## Project Overview

This project is designed to build a medical assistant chatbot capable of answering questions from medical documents such as books, reports, and healthcare PDFs.

The system uses:
- Document ingestion
- Text chunking
- Embedding generation
- Vector similarity search
- LLM-powered response generation

---

## Features

✅ Upload and process medical PDFs  
✅ Semantic search for relevant medical context  
✅ Context-aware medical question answering  
✅ LLM-powered chatbot responses  
✅ Scalable cloud deployment  

---

##  Tech Stack

- **Python**
- **OpenAI / Cohere** → Large Language Models
- **LangChain** → LLM Orchestration
- **Hugging Face** → Embedding Models
- **Pinecone** → Vector Database
- **Flask** → Backend
- **HuggingFace** → Deployment

---

## Project Structure

```bash
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

## Installation

### Clone Repository
```bash
git clone https://github.com/ARJUN-AIML/Medical-Chat-Bot-With-LLMs-Langchain-AWS.git
```

### Move to Project Folder
```bash
cd Medical-Chat-Bot-With-LLMs-Langchain-AWS
```

### Create Virtual Environment
```bash
conda create -n medibot python=3.10 -y
conda activate medibot
```

### Install Dependencies
```bash
pip install -r requirements.txt
```

---

## Environment Variables

Create a `.env` file and add:

```env
OPENAI_API_KEY=your_api_key
PINECONE_API_KEY=your_api_key
```

---

## Run Application

```bash
python app.py
```

---

## Future Improvements

- Multi-document support
- Better medical knowledge retrieval
- Voice-based chatbot
- Improved UI/UX
- Chat history support

---

## Contributing

Contributions are welcome!  
Feel free to fork this repository and submit pull requests.

---

## License

This project is licensed under the MIT License.

---

## Author

**Arjun S**  
B.E Artificial Intelligence and Machine Learning
