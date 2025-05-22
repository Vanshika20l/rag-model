# rag-model

# RAG Model

## Overview
This repository contains a Jupyter Notebook that implements a Retrieval-Augmented Generation (RAG) model. The model is designed to process PDF documents, extract text, and generate embeddings for further analysis or question-answering tasks.

## Features
- Upload PDF files and extract text from them.
- Process the extracted text into sentences and chunks.
- Generate embeddings for the text chunks using a pre-trained model.
- Perform similarity searches on the embeddings to answer user queries.

## Requirements
To run this notebook, you need the following Python packages:
- torch
- PyMuPDF
- pdfplumber
- python-docx
- docxtxt
- tqdm
- sentence-transformers
- accelerate
- bitsandbytes
- flash-attn

You can install these packages using pip. If you are using Google Colab, the necessary installations are included in the notebook.

## Usage
1. **Upload PDF**: Click the "Upload PDF" button to upload your PDF document.
2. **Process PDF**: The notebook will read the PDF and extract text from each page.
3. **Text Processing**: The extracted text will be split into sentences and further chunked for embedding.
4. **Generate Embeddings**: The notebook will generate embeddings for the text chunks.
5. **Query the Model**: You can enter a query, and the model will return the most relevant text chunks based on the embeddings.

## Example
After uploading a PDF, you can ask questions like:
- "What is the focal length of a convex lens?"
- "Explain the phenomenon of light reflection."

The model will return relevant excerpts from the PDF that answer your questions.

## Contributing
Contributions are welcome! If you have suggestions for improvements or new features, feel free to open an issue or submit a pull request.

