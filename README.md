# A Generative AI based Chatbot


## 🚀 Project Workflow


# **Step 1 – Setup Memory for LLM (Vector Database)**

**1. Load raw PDFs** — import medical or knowledge base documents.

**2. Create text chunks** — split large documents into manageable segments.

**3. Generate vector embeddings** — convert chunks into numerical representations using HuggingFace embeddings.

**4. Store embeddings in FAISS** — build a searchable vector database to enable fast and accurate retrieval.


# **Step 2 – Connect Memory with LLM**
**1. Setup LLM (Mistral via HuggingFace)** — load the generative language model for response generation.

**2. Integrate LLM with FAISS** — allow the model to retrieve relevant context before answering.

**3. Create a RAG chain** — combine retrieval and generation to produce informed, context-aware responses.


# **Step 3 – Build the Chatbot UI**

**1. Develop chatbot interface with Streamlit** — create a user-friendly, interactive front end.

**2. Load the FAISS vector store into cache** — ensure quick access to the knowledge base.

**3. Enable RAG-based responses** — generate real-time, accurate medical insights powered by generative AI.
