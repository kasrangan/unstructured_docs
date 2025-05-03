# unstructured_docs
Repository for reading unstructured documents using Langgraph
# 📄 PDF Question Answering using LangChain and OpenAI
This project shows how to extract text from a PDF, convert it into searchable chunks using AI embeddings, and ask questions like "What is LayoutParser?" using OpenAI and LangChain.
## 🔧 How it Works
1. Extract pages from a PDF using `PyPDFLoader`.
2. Use OpenAI to convert each page into a smart "searchable" vector.
3. Store them in an in-memory database.
4. Ask questions — and get the most relevant page snippets.

