

#  YouTube RAG – Retrieval-Augmented Generation for YouTube Videos

YouTube RAG is an intelligent system that takes a YouTube video URL, extracts the transcript, converts the content into embeddings, and performs Retrieval-Augmented Generation (RAG) to answer questions, summarize content, and provide insights with high accuracy.

---

##  Features

*  **Input any YouTube URL**
*  **Automatic transcript extraction**
*  **Embedding generation using state-of-the-art models**
*  **Vector search for efficient retrieval**
*  **RAG-based question answering**
*  **Summaries, insights, and explanations**
*  Fast, accurate, and scalable

---

## Tech Stack

- Python
- LangChain 
- ChromaDB (vector database)
- Sentence Transformers / HuggingFace models
- YouTube Transcript API / Pytube
- Gemini

---

##  Project Structure 

```
youtube-rag/
│── app.py
│── requirements.txt
│── README.md
│── utils/
│   ├── extractor.py      # Transcript extraction
│   ├── embeddings.py     # Embedding generation
│   ├── retriever.py      # Vector search
│   └── rag_pipeline.py   # Answer generation
│── data/
│   └── vectors/          # Stored embeddings
```

---

##  How It Works

1. Provide a YouTube link
2. The system downloads or fetches the transcript
3. Transcript is split into chunks
4. Embeddings are generated
5. Vector database stores and retrieves relevant chunks
6. LLM generates accurate answers using RAG

---

##  Installation

```
git clone https://github.com/your-username/youtube-rag
cd youtube-rag
pip install -r requirements.txt
```

---

##  Run the App

```
python app.py
```

---

## Example Query

```
Ask: "What is the main topic of the video?"
Ask: "Give me a short summary."
Ask: "Explain the key points in simple terms."
```

---

##  Contributing

Contributions are welcome!
Feel free to open issues or submit PRs.

---

