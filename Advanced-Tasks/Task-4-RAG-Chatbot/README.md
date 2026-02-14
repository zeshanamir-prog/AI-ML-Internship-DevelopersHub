# Task 4: Context-Aware Chatbot Using RAG

## Objective
Build a chatbot that remembers conversation context and retrieves external information
from a vectorized document store (RAG).

## Knowledge Base
Custom corpus (documents stored inside the notebook/app).

## Methodology
- Split documents into chunks
- Generated embeddings using sentence-transformers
- Stored embeddings in a FAISS vector index for similarity search
- Retrieved top relevant chunks for each question
- Used an LLM (Flan-T5) to generate answers grounded in retrieved chunks
- Added conversation memory (chat history) for follow-up questions
- Deployed with Streamlit (`app.py`)

## Key Results
- Retrieval grounds responses and reduces hallucinations
- Memory improves follow-up handling
- Complete RAG workflow implemented and deployable

## How to Run
Install:
`pip install faiss-cpu sentence-transformers transformers==4.44.2 accelerate streamlit`

Run:
`streamlit run app.py`
