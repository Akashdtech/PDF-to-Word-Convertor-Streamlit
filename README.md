# PDF-to-Word-Convertor-Streamlit
This project provides a PDF to Word Converter web application, built using Streamlit. It allows users to upload a PDF file, extracts the text from the document, and converts it into a downloadable Word document.
Features:

    Upload Functionality: Users can upload a PDF file for conversion.
    Text Extraction: Extracts text from the uploaded PDF using PyPDF2.
    Word Document Generation: Converts the extracted text into a Word document using python-docx.
    Download Option: Enables users to download the converted Word document directly from the app.

Requirements:

    streamlit - For building the web application.
    PyPDF2 - For reading and extracting text from PDF files.
    python-docx - For creating Word documents.

Setup:

    Install the required packages:

    pip install streamlit PyPDF2 python-docx

    Save the provided code into a file named app.py.

Running the Application:

    Run the app locally with:

streamlit run app.py

Use localtunnel to share the app online:

    npx localtunnel --port 8501

How It Works:

    Open the application in your browser.
    Upload a PDF file via the file uploader.
    The app extracts text from the PDF and generates a Word document.
    Download the converted Word document using the "Download Word Document" button.

This tool is perfect for simple and fast PDF-to-Word text conversion tasks.
