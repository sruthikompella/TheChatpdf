# Chat with PDF

This repository contains a Python application that allows you to upload PDF files and ask questions about their content. The application uses `Gradio` for the user interface, `PyPDF2` for reading PDF files, and `LangChain` for processing and answering questions based on the PDF content.

## Features

- **Upload PDFs**: Upload multiple PDF files for text extraction.
- **Ask Questions**: Input your questions related to the content of the uploaded PDFs.
- **Conversational AI**: The application uses Google's Generative AI for embedding and answering questions based on the extracted text from PDFs.
- **Interactive Interface**: A user-friendly interface powered by Gradio.

## Installation

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/yourusername/chat-with-pdf.git
    cd chat-with-pdf
    ```

2. **Create a Virtual Environment** (Optional but recommended):
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. **Install Dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

4. **Set Up API Keys**:
    - Create a `.env` file in the root directory.
    - Add your Google API key in the `.env` file:
      ```
      GOOGLE_API_KEY=your-google-api-key
      ```

## Usage

1. **Run the Application**:
    ```bash
    python app.py
    ```
    The application will launch in your default web browser.

2. **Upload PDFs**:
    - Click on "Upload your PDF Files" to upload one or more PDF files.

3. **Ask a Question**:
    - Enter a question related to the content of the PDFs and click "Submit" to receive an answer.

## File Structure

- `app.py`: The main application script.
- `requirements.txt`: The list of dependencies.
- `.env`: The environment file (not included, needs to be created).
- `README.md`: This file, containing documentation about the repository.

## Dependencies

- `gradio`
- `PyPDF2`
- `langchain`
- `google-generativeai`
- `FAISS`
- `dotenv`

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request or open an Issue.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

## Acknowledgements

- [Gradio](https://gradio.app/) for the UI framework.
- [LangChain](https://langchain.com/) for providing the language model interface.
- [Google Generative AI](https://developers.generativeai.google/) for embeddings and conversational AI.

