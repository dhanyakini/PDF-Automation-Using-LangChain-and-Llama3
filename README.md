# PDF Automation with LangChain and Llama3

This project enables PDF automation using [LangChain](https://github.com/hwchase17/langchain) and Llama3, providing users with an interactive way to parse, summarize, and interact with PDF content through a user-friendly interface built with [Gradio](https://gradio.app/).

## Features
- **PDF Parsing**: Parse and extract structured content from PDFs.
- **Summarization and Q&A**: Answer questions and summarize content using advanced language models.
- **Document Embedding and Retrieval**: Index document chunks for efficient and relevant retrieval of information.
- **Interactive Gradio Interface**: User-friendly interface to ask questions and get concise, relevant answers from PDF content.

## Getting Started

### Prerequisites
To run this project, you'll need:
- **Google Colab** or **Jupyter Notebook** (recommended environments)
- API keys for **Groq** and **LlamaParse** (to handle parsing and language model queries)

### Installation
All required dependencies are installed directly within the notebook. Specified versions ensure compatibility, with key packages including:
- `langchain`, `llama-parse`, `qdrant-client`, `fastembed`, and `gradio`.

### Code Structure
The code is organized in cells (for Colab or Jupyter Notebook) as follows:
1. **Setup and Installation**: Installs necessary packages.
2. **Environment and API Key Setup**: Sets up API keys and imports libraries.
3. **File Upload and Parsing**: Enables file upload and parses the PDF using LlamaParse.
4. **Document Processing**: Chunks document text for embedding and retrieval.
5. **Embedding and Retrieval Configuration**: Initializes embeddings and a vector store for document indexing.
6. **Q&A System**: Configures LangChain’s Q&A chain to answer questions based on document content.
7. **User Interface**: A Gradio app allows users to input questions and get answers from PDF content.

### Usage

1. **Upload PDF**: The notebook allows you to upload PDF files directly within the notebook.
2. **Parse PDF**: Content is parsed using LlamaParse with a custom instruction to extract relevant information.
3. **Ask Questions**: Use the Gradio interface to ask questions based on the PDF content, and get accurate answers from the language model.

### Example

Once the code runs, you can enter questions in the Gradio interface, such as:
- "Summarize the key points of the document."
- "What does the document say about [specific topic]?"

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.



