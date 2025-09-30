# 🎓 Bachelor Thesis: GPU-Optimized Semantic Search on Video Transcripts

## 📌 Overview
This repository documents my **Bachelor of Science in Computer Science thesis project** at **FORTH (Foundation for Research and Technology – Hellas)**.  
The project implemented an **end-to-end Retrieval-Augmented Generation (RAG) pipeline**, enabling **semantic search over video transcripts** with results enriched by **timestamps and video identifiers**. 

✨ Key features include:  
- **RAG Architecture**: Combined video transcript retrieval with embedding-based semantic search.  
- **End-to-End Workflow**: Built a **Django REST Framework** API for embedding generation, vector storage, and similarity search.  
- **Semantic Video Transcript Search**: Extracted audio from videos, transcribed with **OpenAI Whisper**, and embedded with **BERT**.  
- **GPU Optimization**: Leveraged **PyTorch + FAISS GPU** for high-performance similarity search and efficient memory use.
- **Vector Database Benchmarking**: Conducted a comparative study of **FAISS, Pinecone, and PostgreSQL**  
- **Embedding Optimization**  
- **Deployment**: Containerized the system with **Docker** for reproducibility and portability.  
- **Environment**: Developed in **Python on Linux Ubuntu**, running exclusively on **FORTH’s GPU infrastructure via VPN**.


⚠️ **Note**: The source code is not publicly available due to infrastructure and legislation restrictions. This repository serves as a **portfolio showcase**. Access for review under supervision is possible by request.

---

## 🛠️ Tech Stack
- **Languages**: Python  
- **Frameworks/Models**: PyTorch, Hugging Face Transformers (BERT), OpenAI Whisper, Django REST Framework  
- **Vector Databases**: FAISS (GPU), Pinecone, PostgreSQL (pgvector)  
- **Benchmarking**: FAISS GPU benchmarking tools + custom evaluation scripts  
- **Deployment**: Docker, Linux Ubuntu  
- **Other Tools**: NLTK (text preprocessing), MoviePy (audio extraction)


## 🚀 Features
- End-to-end **RAG pipeline** for semantic retrieval.  
- Transcribes video to text with **Whisper**.  
- Encodes transcripts into embeddings with **BERT**.  
- Optimized embeddings with **normalization and quantization**.  
- Stores and queries embeddings in **vector databases**.  
- Retrieves **most semantically similar transcript segments** with their **timeframes and source video IDs**.  
- Fully **GPU-accelerated** for optimized performance.  
- Exposed as a **REST API** for seamless integration.  

---

## 📊 Vector Database Benchmarks & Embedding optimization 

**Embedding Optimization**:  
  - Applied **normalization (L2, quantization, etc.)** for space and time efficiency.  
  - Matched **embedding normalization strategies** with appropriate similarity search methods (inner product, cosine similarity, Euclidean distance). 

**Vector Databse Benchmarks**
I tested and compared FAISS, Pinecone, and PostgreSQL on:  
- **Accuracy and integrity** of top-k retrieved results  
- **Query speed / latency** and API response time (time complexity)  
- **Storage efficiency** under different embedding optimization strategies (space complexity)

**Each benchmark combined**:  
- Embedding normalization choice.  
- Appropriate similarity search metric.

---

## 📸 Screenshots 
**Workflow**

<img width="754" height="471" alt="Workflow_final" src="https://github.com/user-attachments/assets/2572ace9-4a97-414e-963f-2e6041e494bc" />

---

## About This Project
- **Type**: Bachelor Thesis Project  
- **Institution**: University of Crete, Computer Science Department  
- **Research Infrastructure**: The Foundation for Research and Technology - Hellas (FORTH) 

