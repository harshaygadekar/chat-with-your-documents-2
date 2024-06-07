
## Authors

[@harshaygadekar](https://www.github.com/harshaygadekar)


## License

[MIT-License](https://opensource.org/license/mit/)


# Chat-with-your-documents-2

This is my second AI-powered document summarizer application, but first to use Streamlit. It leverages advanced language models from LLaMA-3 and FastEmbed for efficient document embedding and summarization. The application allows users to upload PDF documents, generate concise summaries, and interact with the summaries through a chat interface for follow-up questions.

Unlike my previous chat-with-your-documents project which was built using Langchain. In this project, I've actually used Meta LLaMa-3 for processing and summarizing your documents and streamlit to create a GUI which makes the use-case much simpler and effective.

## Features

- **PDF Document Upload**: Upload your PDF documents directly through the web interface.
- **Automated Summarization**: Generate concise summaries of uploaded documents using state-of-the-art language models.
- **Interactive Query Engine**: Ask follow-up questions about the document and receive accurate responses based on the content.
- **Chat History**: Review the history of interactions for continuous reference.

### Contributing
Contributions are welcome! Please fork the repository and submit a pull request for any improvements or bug fixes.
## Installation

### Install my project with following instructions:

```bash
git clone https://github.com/harshaygadekar/chat-with-your-documents-2.git
cd chat-with-your-documents-2
```
### Set Up a Virtual Environment

```bash
python3 -m venv venv
source venv/bin/activate   # On Windows, use `venv\Scripts\activate`
```
### Install Required Dependencies

```bash
pip install -r requirements.txt
```
### Run the Streamlit Application

```bash
streamlit run ai_document_summarizer2.py
```
## Upload a PDF Document:

Once the Streamlit app is running, open your web browser and go to http://localhost:8501.

Use the file uploader to select a PDF document from your local system.
Click "Process & Summarize" to generate a summary.
Use the chat interface to ask follow-up questions based on the document's content.


## Tech Stack

Python, Meta LLaMa-3/llma_index, Streamlit (GUI), Pillow (to handle image inputs)


