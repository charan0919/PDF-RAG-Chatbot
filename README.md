\# PDF RAG Chatbot



Ask questions about any PDF and get answers based on its content, with the matching page shown next to each reply.



\*\*How it works:\*\* the PDF is split into chunks and stored in a vector database (ChromaDB). For each question, the most relevant chunks are retrieved and sent to Google Gemini, which writes the answer.



\*\*Tech stack:\*\* Python, LangChain, Google Gemini API, ChromaDB, Hugging Face embeddings, PyMuPDF, Gradio



\## Run it



1\. Get a free API key from \[Google AI Studio](https://aistudio.google.com/app/apikey).

2\. Install dependencies: `pip install -r requirements.txt`

3\. Copy `config.yaml.template` to `config.yaml` and add your API key.

4\. Start the app: `python src/app.py`



