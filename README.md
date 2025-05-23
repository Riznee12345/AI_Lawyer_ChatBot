# AI_Lawyer_ChatBot 👩🏻‍⚖️🏛️📜⚖️🎓 
You can chat with your PDFs using a powerful RAG system built with Deepseek, LangChain, and Streamlit. Real-time answers powered by Deepseek-r1 and an intuitive UI

## 🚀 Descripotion 
I developed a robust Retrieval-Augmented Generation (RAG) system using Deepseek, LangChain, and Streamlit. This solution enables interactive conversations with PDF documents, delivering precise answers to complex queries based on your local files. The process begins with setting up Ollama’s Deepseek-r1 LLM model, renowned for its advanced reasoning capabilities. I then integrate this model into a LangChain-powered RAG pipeline and build an intuitive Streamlit interface for real-time PDF querying
![ChatGPT Image May 10, 2025, 08_07_01 PM](https://github.com/user-attachments/assets/261fb6d9-78de-4f65-8f12-96fd7f25a088)


## 🧠 Key Features

- 💬 **Ask Questions**: Chat with your PDFs in real-time.
- 🔍 **Contextual Retrieval**: Uses advanced RAG techniques to fetch relevant information before answering.
- 🧱 **Deepseek-r1 LLM**: Leverages Ollama’s local LLM with strong reasoning and comprehension.
- ⚡ **LangChain Integration**: Powers the logic behind document parsing and retrieval.
- 🖥️ **Streamlit UI**: User-friendly interface for loading PDFs and interacting with the chatbot.

## 🛠️ Tech Stack

- **[Deepseek LLM](https://ollama.com/library/deepseek)** via [Ollama](https://ollama.com/)
- **LangChain** for document processing and retrieval
- **Streamlit** for UI
- **Python** as the core programming language
- **FAISS** or similar vector store for document chunk indexing

## 📦 Installation

Make sure you have the following installed:
- Python 3.9+
- Ollama installed and Deepseek model pulled (`ollama pull deepseek`)


# Install dependencies
pip install -r requirements.txt
