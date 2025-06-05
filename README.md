Implementing a Retrieval-Augmented Generation model for a QA chatbot.

 Contributed to the development of a Retrieval-Augmented Generation (RAG) chatbot aimed at improving user interaction with technical content related to ARTSENS technology. The system   was designed to assist users in querying and understanding complex documents in a simplified, conversational manner.
 The primary data is based on in house publications related to ARTSENS technology (vaskrisc.com) and cardiovascular engineering.
 It made use of Hugging face embeddings to generate the text embeddings. FAISS db was used for embeddings and SQLite for storing metadata and text chunks.
 The retrieved text chunks were integrated to the llm (gemini-1.5-flash), for answering the queries about ARTSENS technology.
 xquerying and understanding complex documents in a simplified, conversational manner.

Key Milestones:
1. Created HuggingFace Embeddings and Developed a dual-database retrieval system using FAISS and SQLite databases.
2. Implemented semantic search of the query embeddings and integrated the pipeline with Gemini 1.5 Flash LLM. 
3. Tested integration by running the chatbot backend on Flask with Ngrok from Colab, exposing API endpoints for queries, and connecting it to an existing WordPress site using a simple    plugin for demonstration purposes.

Skills: Retrieval-Augmented Generation (RAG) · Natural Language Processing (NLP) · Semantic Search · Python (Programming Language) · Gemini
