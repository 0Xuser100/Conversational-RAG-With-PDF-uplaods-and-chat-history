
---

# 📚 Conversational RAG with PDF Uploads and Chat History

An advanced conversational assistant built using **Streamlit** and **LangChain**, designed to handle your PDF uploads and answer questions intelligently. This app leverages **Retrieval Augmented Generation (RAG)** and supports contextual, session-aware conversations with chat history.

## ✨ Key Features
- **📄 PDF Uploads**: Effortlessly upload one or multiple PDF documents for analysis.
- **💬 Conversational Interface**: Engage in natural language conversations, asking questions directly based on your uploaded PDFs.
- **🕒 Context-Aware Responses**: Maintains chat history across sessions for better context and accuracy.
- **🔑 Session Management**: Organize conversations with unique session IDs for independent histories.
- **🚀 Advanced Language Model**: Powered by **Groq's Gemma2-9b-It** model for state-of-the-art response generation.
- **📊 HuggingFace Embeddings**: Uses `all-MiniLM-L6-v2` for efficient and accurate document vectorization.

---

## 🎯 Prerequisites
- **Python**: Version 3.7 or higher.
- **Groq API Key**: To access the language model.
- **HuggingFace API Token**: For embeddings.

---

## ⚙️ Installation

### 1. Clone the Repository
```bash
git clone https://github.com/0Xuser100/Conversational-RAG-With-PDF-uplaods-and-chat-history.git
cd Conversational-RAG-With-PDF-uplaods-and-chat-history
```

### 2. Create a Virtual Environment
```bash
python -m venv venv
```

### 3. Activate the Virtual Environment
- **Windows**:
  ```bash
  venv\Scripts\activate
  ```
- **macOS/Linux**:
  ```bash
  source venv/bin/activate
  ```

### 4. Install Dependencies
```bash
pip install -r requirements.txt
```

### 5. Set Up Environment Variables
- Create a `.env` file in the project root.
- Add your API keys:
  ```plaintext
  HF_TOKEN=your_huggingface_api_token
  ```

---

## 🚀 How to Use

1. **Run the Application**
   ```bash
   streamlit run app.py
   ```

2. **Enter Your API Keys**
   - When prompted, provide your Groq API key.

3. **Upload PDFs**
   - Use the app interface to upload one or more PDF files.

4. **Start Conversing**
   - Ask questions about your uploaded content.
   - Enjoy contextual and accurate responses.

---

## 🗂️ Project Structure
```
Conversational-RAG-With-PDF-uplaods-and-chat-history/
├── app.py             # Main application script
├── requirements.txt   # Required dependencies
├── .env.example       # Template for environment variables
├── README.md          # Project documentation
└── resources/         # Placeholder for additional resources
```

---

## 📋 Dependencies

### Key Python Packages
- `streamlit`
- `langchain`
- `langchain_groq`
- `langchain_huggingface`
- `dotenv`
- `duckduckgo-search`

Ensure all required packages are included in `requirements.txt`.

---

## 🧪 Example Workflow
1. **User**: "Upload multiple PDFs containing AI-related research papers."
2. **App**: Uploads the PDFs and analyzes their content.
3. **User**: "What are the key differences between supervised and unsupervised learning?"
4. **App**: Provides a concise, context-aware response based on the uploaded content.

---

## 🤝 Contributing
We welcome contributions! Here's how you can help:
- Fork the repository.
- Create a feature branch.
- Submit a pull request with your changes.

---

## 📜 License
This project is licensed under the **MIT License**.

---

## 📞 Contact
For questions, suggestions, or feedback:
- **Name**: Mahmoud Abdelhamid
- **Email**: [mahmoudabdulhamid22@gmail.com](mailto:mahmoudabdulhamid22@gmail.com)
- **GitHub**: [https://github.com/0Xuser100](https://github.com/0Xuser100)
- **LinkedIn**: [https://www.linkedin.com/in/mahmoud-abdulhamid-052244230/](https://www.linkedin.com/in/mahmoud-abdulhamid-052244230/)

---

With this chatbot, you're just a conversation away from unlocking the insights hidden in your documents. 🚀
