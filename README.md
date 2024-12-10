## Conversational RAG Q&A with PDF and Chat History

This project is a web-based application built using **Streamlit** and **LangChain**. It provides a conversational interface for retrieving answers from uploaded PDFs and retaining chat history for contextual follow-up questions.

---

## Features

- **Conversational RAG (Retrieval-Augmented Generation)**:
  - Answer questions based on the content of uploaded PDF documents.
  - Retain chat history for context-aware Q&A.
- **PDF Integration**:
  - Upload multiple PDFs to extract and process text for Q&A.
- **Contextual Q&A**:
  - Reformulate questions considering chat history for precise answers.
- **AI-Powered**:
  - Powered by the Gemma2-9b-It model for efficient question answering.
- **Embeddings and Search**:
  - Uses HuggingFace embeddings and Chroma for vector-based document retrieval.

---

## Installation

1. Clone the repository:
   ```bash
   git clone <repository_url>
   cd <repository_directory>
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Set up environment variables:
   - Create a `.env` file in the root directory with your HuggingFace token:
     ```
     HF_TOKEN=your_huggingface_token
     ```

4. Run the application:
   ```bash
   streamlit run app.py
   ```

---

## Usage

1. Launch the application in a browser.
2. Enter your **Groq API Key** in the provided input field.
3. Upload one or more PDF files.
4. Ask questions about the uploaded content using the chat interface.
5. View concise and context-aware answers along with chat history.

---

## Requirements

- Python 3.8+
- Libraries:
  - `streamlit`
  - `langchain`
  - `langchain-groq`
  - `langchain-community`
  - `langchain_chroma`
  - `langchain_text_splitters`
  - `HuggingFaceEmbeddings`
  - Other dependencies in `requirements.txt`

---

## Future Enhancements

- Support for additional file types (e.g., Word documents).
- Improved embeddings for faster and more accurate retrieval.
- Integration with cloud storage for document uploads.

---

This project demonstrates the integration of document retrieval and conversational AI for an intuitive and effective question-answering experience. Feel free to contribute and expand its capabilities!
