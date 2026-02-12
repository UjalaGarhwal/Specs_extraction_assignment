This project builds a Retrieval-Augmented Generation (RAG) based system to extract torque specifications from technical PDF manuals.

**It combines:**
PDF text extraction
Transformer-based embeddings
FAISS vector similarity search
Structured torque extraction using Regex

The system allows users to query torque values and retrieve structured results from a large technical document.

**Tech Stack**
Python
PyMuPDF (fitz) - PDF text extraction
Sentence Transformers - Embedding generation
BAAI/bge-base-en-v1.5 - Embedding model
FAISS (Facebook AI Similarity Search) - Vector indexing
Transformers (HuggingFace)
NumPy / Pandas
Regex
