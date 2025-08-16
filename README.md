# Book-Buddy AI 📖

![Book-Buddy AI Telegram Bot](https://github.com/HossamElsrah/Book-Buddy-AI/blob/main/Tele%20Bot.png)

### **Your Personal AI Study Assistant**

Are you tired of sifting through countless pages of a textbook to find one specific piece of information? **Book-Buddy AI** is a powerful Telegram bot designed to be your ultimate study companion. Simply upload any PDF book, and it will instantly become a knowledgeable resource that you can chat with. Ask questions, clarify concepts, and get precise answers without ever leaving your chat.

### **Features**

  * **Intelligent Q\&A:** Get accurate, context-aware answers to any question about your uploaded books.
  * **Effortless Book Loading:** Easily upload books in PDF format through a simple Telegram interface.
  * **Custom RAG Pipeline:** Built with a robust Retrieval-Augmented Generation pipeline to ensure high-quality responses.
  * **Modular Architecture:** The pipeline is broken down into distinct stages:
      * **Model Loading & Quantization:** Efficiently loads and optimizes models for performance.
      * **Document Setup:** Prepares and chunks the uploaded book's content for processing.
      * **Embeddings:** Converts text into a numerical format for semantic search.
      * **Retrieval, Reranking & Generation Stages:** A finely-tuned process to find the most relevant information and generate a concise answer.
  * **User-Friendly Telegram Bot:** A seamless and intuitive interface for students and researchers.

### **How It Works**

The core of **Book-Buddy AI** is a sophisticated RAG pipeline. Here's a brief overview of the process:

1.  **User Uploads a Book:** A user uploads a PDF file to the Telegram bot.
2.  **Document Chunking:** The book is broken down into smaller, manageable chunks.
3.  **Embeddings:** These chunks are then converted into vector embeddings and stored.
4.  **User Asks a Question:** When the user asks a question, the pipeline performs a semantic search to retrieve the most relevant chunks from the uploaded book.
5.  **Reranking:** The retrieved chunks are reranked to ensure the highest relevance.
6.  **Generation:** The top-ranked chunks and the user's question are fed into a powerful language model to generate a precise and coherent answer.

### **Why Students Will Love It**

  * **Saves Time:** Quickly find the information you need without manually searching.
  * **Enhances Learning:** Get instant clarifications on complex topics.
  * **Personalized Study Aid:** Turn any book into an interactive learning experience tailored just for you.
  * **Accessibility:** Study on the go, directly from your phone.


`![](https://github.com/HossamElsrah/Book-Buddy-AI/blob/main/Tele%20Bot.png)`

This will tell GitHub to render the image located at the provided URL directly in your README.md file. Make sure to commit this updated `README.md` file to your repository.
