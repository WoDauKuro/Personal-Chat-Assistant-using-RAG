# RAG Chat Assistant: Document-Powered Conversational AI

## 🚀 Project Overview

This project implements a Retrieval Augmented Generation (RAG) chat assistant that allows users to interact with and query multiple PDF documents using advanced natural language processing techniques.

## ✨ Key Features

- **Multi-Document Support**: Load and query multiple PDF documents simultaneously
- **Advanced Retrieval**: Uses Chroma Vector Database for efficient document searching
- **Intelligent Response Generation**: Powered by Groq's Llama 3.1 70B Versatile model
- **Web Interface**: Interactive Gradio UI for easy querying
- **Contextual Understanding**: Maintains conversation history for coherent interactions

## 📦 Technologies Used

- **Language Processing**: LangChain
- **Embedding**: Hugging Face Sentence Transformers
- **Vector Database**: Chroma
- **Language Model**: Groq (Llama 3.1 70B)
- **Web Interface**: Gradio
- **Programming Language**: Python

## 🔧 Prerequisites

- Python 3.8+
- Groq API Key
- Hugging Face Embeddings

## 🛠️ Installation

1. Clone the repository:
```bash
git clone https://github.com/WoDauKuro/Personal-Chat-Assistant-using-RAG.git
cd rag-chat-assistant
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Set up configuration:
- Create a `config.py` file
- Add your Groq API key

## 🚀 Usage

1. Place your PDF documents in the project directory or use the PDF documents in the `data` directory
2. Update `file_path` in the notebook with your document paths
3. Run the Jupyter Notebook
4. Access the Gradio web interface

## 📝 Configuration Options

- Adjust `chunk_size` and `chunk_overlap` for document processing
- Modify LLM temperature for response creativity
- Customize embedding model

## 🔒 Security Notes

- Never commit API keys to version control
- Use environment variables or secure configuration management

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Create a Pull Request

## 📄 License

MIT License

## 🙏 Acknowledgements

- LangChain
- Hugging Face
- Groq
- Gradio


**Note**: Ensure you have the necessary API keys and permissions before running the application.