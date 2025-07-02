# PDFChat with ChatGroq and LLaMA3! 🦙

> This is a Streamlit web application that demonstrates how to use LangChain, Groq’s LLaMA3-8B model, OpenAI Embeddings, and FAISS to create a document-aware chatbot. You can upload PDF documents, embed them into a vector store, and then ask questions about their content.

# ⚡Features~
- Loads and processes PDFs from a directory.
- Generates vector embeddings using OpenAI.
- Retrieves relevant chunks using FAISS vector store.
- Answers questions using Groq’s LLaMA3-8B-8192 model.
- Fast and contextual question-answering.
- Interactive UI built with Streamlit.

# 🤖 Tech Stack!

Used **Langchain**, **Streamlit**, **Groq**, **OpenAI API**, **FAISS**

# Try it out by:

- Clone the repository
```
git clone https://github.com/JuanitaCathy/Document-QnA-Chatbot

```
- Create and activate a virtual environment 
```
python -m venv venv
venv\Scripts\activate
```
- Install dependencies

```
pip install -r requirements.txt
```

- Create a .env file
```
OPENAI_API_KEY=your_openai_api_key
GROQ_API_KEY=your_groq_api_key
```


# 🧪 Usage

1. Place your PDF files inside the pdfs/ directory.
2. Run the Streamlit app
```
streamlit run app.py
```

3. In the web UI:

- Click "Documents Embedding" to preprocess and embed the PDFs.

- Ask a question in the input box.
  
- View answers and context below.

# Environment Variables

Make sure your .env file includes:
```
OPENAI_API_KEY=sk-...
GROQ_API_KEY=groq-...
```
