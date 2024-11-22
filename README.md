# Conversational RAG with PDF Uploads and Chat History

This Streamlit application allows users to upload PDF documents and engage in a conversational question-answering session based on the content of the uploaded PDFs. It leverages Retrieval Augmented Generation (RAG) and maintains chat history for context-aware responses.

## Features

- **PDF Uploads**: Upload multiple PDF files to the application.
- **Conversational Interface**: Ask questions related to the uploaded PDFs and receive answers based on their content.
- **Chat History**: The application maintains chat history to provide context-aware answers.
- **Session Management**: Support for multiple sessions with customizable session IDs.
- **Language Model Integration**: Utilizes the Groq API with the `Gemma2-9b-It` model for generating responses.
- **Embeddings**: Uses HuggingFace embeddings (`all-MiniLM-L6-v2`) for document vectorization.

## Prerequisites

- Python 3.7 or higher
- [Streamlit](https://streamlit.io/)
- [LangChain](https://github.com/hwchase17/langchain)
- Groq API Key
- HuggingFace API Token

## Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/0Xuser100/Conversational-RAG-With-PDF-uplaods-and-chat-history.git
   cd your-repo-name
   ```

2. **Create a virtual environment**:

   ```bash
   python -m venv venv
   ```

3. **Activate the virtual environment**:

   - On Windows:

     ```bash
     venv\Scripts\activate
     ```

   - On macOS/Linux:

     ```bash
     source venv/bin/activate
     ```

4. **Install dependencies**:

   ```bash
   pip install -r requirements.txt
   ```

5. **Set up environment variables**:

   - Create a 

.env

 file in the project root directory.
   - Add your HuggingFace API token to the 

.env

 file:

     ```env
     HF_TOKEN=your_huggingface_api_token
     ```

## Usage

1. **Run the Streamlit application**:

   ```bash
   streamlit run app.py
   ```

2. **Enter your Groq API Key**:

   - Upon launching the app, you'll be prompted to enter your Groq API key. This key is required to access the language model.

3. **Upload PDF files**:

   - Use the file uploader in the app to select one or more PDF files. The application supports multiple file uploads.

4. **Interact with the chatbot**:

   - Enter a session ID or use the default `default_session`.
   - Ask questions about the content of the uploaded PDFs.
   - The chatbot will provide answers based on the documents and maintain context using chat history.

## File Overview

- 

app.py

: Main application file containing the Streamlit app code.
- 

.env

: Environment file where you store your HuggingFace API token.
- 

requirements.txt

: Dependencies required to run the application.

## Dependencies

- 

streamlit


- 

langchain


- 

langchain_chroma


- 

langchain_core


- 

langchain_community


- 

langchain_groq


- 

langchain_huggingface


- 

langchain_text_splitters


- 

dotenv



*Note: Ensure all dependencies are listed in the 

requirements.txt

 file.*

## Additional Information

- **Embeddings Model**: The application uses HuggingFace's `all-MiniLM-L6-v2` model for generating embeddings.
- **Language Model**: Utilizes the `Gemma2-9b-It` model via the Groq API for conversational responses.
- **Session Management**: Sessions are managed using 

session_id

, allowing for multiple, independent chat histories.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request if you have suggestions or improvements.

## License

This project is licensed under the MIT License.
