Retrieval-Augmented Generation (RAG) System for Legal Document Q&A
This project demonstrates how to build a Retrieval-Augmented Generation (RAG) pipeline that can answer questions about legal documents and retrieve relevant clauses using open-source tools like LangChain, FAISS, and Hugging Face Transformers.

🔍 Use case: Automating legal document understanding — including contract clause retrieval, regulatory Q&A, and compliance insights.

🚀 Features
✅ Load and process legal contract datasets.

📄 Intelligent document chunking using RecursiveCharacterTextSplitter.

🔍 Semantic search via dense embeddings and FAISS vector store.

🤖 Query answering using LLMs like Mistral-7B or other Hugging Face-hosted models.

📚 End-to-end RAG pipeline using LangChain.

⚙️ Modular and extendable — plug in your own datasets, models, or prompts.

🧠 Technologies Used
LangChain – for chaining retrieval and LLM generation.

SentenceTransformers – for generating text embeddings (MiniLM-L6-v2).

FAISS – for fast similarity search over document chunks.

Transformers (Hugging Face) – to load and run LLMs.

BitsAndBytes – for 4-bit quantized LLM loading.

Google Colab – for development and GPU experimentation.

Folder structure:
.
├── RAG_project3.ipynb       # Jupyter Notebook with full pipeline
├── data/                    # (optional) directory for PDF or text contracts
├── README.md                # You are here!


