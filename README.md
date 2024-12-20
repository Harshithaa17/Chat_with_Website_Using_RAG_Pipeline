# Chat_with_Website_Using_RAG_Pipeline

This project implements a simple RAG pipeline to scrape data from websites, process it,
and generate responses to user queries. The system crawls given URLs, chunks the content, converts it into embeddings,
and uses a vector database for similarity-based retrieval.


Steps:

Crawl and scrape websites for textual content.

Chunk the data and create vector embeddings using Sentence-BERT.

Store embeddings in a FAISS index for fast retrieval.

Accept user queries, find the most relevant content, and generate responses.



Usage:

Update the URLs in the code.

Run the script and enter your queries.

Get relevant responses based on the website data.



Requirements:

Python 3.8+

Libraries: requests, beautifulsoup4, sentence-transformers, faiss-cpu

This system demonstrates the basics of RAG with a focus on crawling and query response generation.
