# AI_Lawyer_ChatBot 👩🏻‍⚖️🏛️📜⚖️🎓🖋️ 
Chat with your PDFs using a powerful RAG system built with Deepseek, LangChain, and Streamlit. Real-time answers powered by Deepseek-r1 and an intuitive UI

## Descripotion 🚀
I developed a robust Retrieval-Augmented Generation (RAG) system using Deepseek, LangChain, and Streamlit. This solution enables interactive conversations with PDF documents, delivering precise answers to complex queries based on your local files. The process begins with setting up Ollama’s Deepseek-r1 LLM model, renowned for its advanced reasoning capabilities. I then integrate this model into a LangChain-powered RAG pipeline and build an intuitive Streamlit interface for real-time PDF querying






This project integrates **Deepseek-r1**, a highly capable open-source LLM (via Ollama), into a **LangChain-based RAG pipeline**. The system retrieves relevant context from user-uploaded PDFs and generates intelligent responses using the LLM. The entire experience is wrapped in an easy-to-use **Streamlit** interface, enabling natural conversation with your documents.

## 🧠 Key Features

- 💬 **Ask Questions**: Chat with your own PDFs in real time.
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


# Clone the repository
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name

# Install dependencies
pip install -r requirements.txt
