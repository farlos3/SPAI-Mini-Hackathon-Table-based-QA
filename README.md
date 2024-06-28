# Try-RAG-Ollama![image](https://github.com/Farlos3/Try-RAG-Ollama/assets/86741684/28d8eeef-77cb-4701-bb0b-09b06cec40fb)

RAG (Retrieval-Augmented Generation) is a powerful technique that combines the strengths of retrieval-based and generation-based models. It allows for generating contextually relevant text by retrieving pertinent information from a pre-existing knowledge base. This approach is particularly useful for tasks that require access to a large corpus of information, such as question answering, document summarization, and language translation.

This README has been written with the assistance of ChatGPT to provide clear and concise instructions

## Key Components
1. Loading PDFs: The project involves loading PDF documents to extract and use their content for retrieval and generation purposes.
2. Chroma Database: We use the Chroma database for storing embeddings. Chroma is a robust and efficient database designed for managing large-scale vector data.
3. Nomic Embed Text: For embedding text, we use the nomic-embed-text tool, which provides high-quality text embeddings suitable for retrieval and other downstream tasks.
4. Local LLM with Ollama: We use a local Large Language Model (LLM) with Ollama for generating contextually relevant responses based on the retrieved information.
 
