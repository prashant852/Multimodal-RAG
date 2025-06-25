# Multimodal RAG with Gemini

This project demonstrates a Retrieval-Augmented Generation (RAG) system enhanced with multimodal capabilities using Gemini's LLMs. Unlike traditional RAG pipelines limited to text, this system understands and processes both text and images from a single PDF document.

## 💡 Features

- Extracts **text (in Markdown format)** and **images** from a PDF
- Generates **captions for images** and integrates them into the extracted text
- Chunks text for efficient semantic search
- Builds a **vector database** of text chunks
- Retrieves top-k relevant chunks for a given query
- Uses **Gemini multimodal LLM** to answer questions using both image and text data
- Returns **structured JSON outputs**

## 🧠 GenAI Capabilities Used

- Multimodal image + text understanding
- Image captioning
- Embeddings generation
- Vector search (vector store/database)
- Retrieval Augmented Generation (RAG)
- Structured output / JSON mode

## 📦 Libraries & Frameworks

- Google GenerativeAI (Gemini)
- PyMuPDF
- Langchain / FAISS (or similar for vector store)
- Python (Jupyter Notebook)

## 🚀 How to Use

1. Upload a PDF (with text and images).
2. Run the notebook to extract, process, and index the content.
3. Ask a query; the system will retrieve the most relevant content and answer using Gemini.

## 📝 Limitations

- Currently supports **only a single PDF** at a time.
- Assumes clean document formatting for optimal captioning and chunking.

## 📁 Notebook

See [`multimodal-rag-with-gemini.ipynb`](./multimodal-rag-with-gemini.ipynb) for complete implementation.
