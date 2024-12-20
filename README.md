Implementing a Retrieval-Augmented Generation model for a QA chatbot.
The primary data is based on in house publications related to ARTSENS technology (vaskrisc.com) and cardiovascular engineering.
It made use of Hugging face embeddings to generate the text embeddings. FAISS db was used for embeddings and SQLite for storing metadata and text chunks.
The retrieved text chunks were integrated to the llm (gemini-1.5-flash), for answering the queries about ARTSENS technology.
