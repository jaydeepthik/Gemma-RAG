# Gemma-RAG
Retrieval Augmentation Generation (RAG) using FAISS and Gemma 2b instruction tuned model from HuggingFace for answering your questions regarding movies.

# Details
- Dataset: "MongoDB/embedded_movies"
- Embedding: "thenlper/gte-small"
- VectorDB: FAISS
- Generator LLM: "google/gemma-2b-it"

# Libraries
- accelerate
- bitsandbytes
- transformers
- sentence-transformers
- faiss-gpu
- datasets
- langchain
