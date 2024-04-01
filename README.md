# RAG Pipeline
PDF Retrieval Augmented Generation Pipeline for LLMs.

**This end-to-end RAG pipeline project is designed to read PDF files and generate insights from the processed documents.**

## How?

- The process begins with preprocessing steps such as breaking sentences apart for every page in the document, chunking sentences into a fixed size, filtering irrelevant information, and creating sentence-level embeddings for text chunks. 
- The similarity search function is used to get query strings turned into embeddings, perform cosine similarity functions between text embeddings and query embedding, sort results in descending order, and finally, fire up the LLM (Google Gemma).
- The main goal of the project is to improve the generation outputs of LLMs by providing them with factual and relevant information. This helps prevent hallucinations, where an LLM may generate incorrect or misleading information.
- By running the pipeline locally on your own hardware, you can ensure data privacy, avoid delays caused by API queues or downtime, and reduce costs associated with external services.

## Workflow
![Untitled Diagram drawio](https://github.com/smellycloud/rag_pipeline/assets/52908667/5d742a3e-7c06-49f9-a725-68cdc70ad117)
