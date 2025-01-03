# docling-pdf-processor

**PDF Intelligence Platform** combining **IBM Docling** for document processing, **LlamaIndex** for data structuring, and **Streamlit** for a powerful UI. Extract, analyze, and interact with documents using AI capabilities.

## Overview

`docling-pdf-processor` is a cutting-edge PDF processing solution that combines multiple AI-powered tools to extract, analyze, and interact with PDF documents in an intuitive and user-friendly way.

### Key Features:
- **Document Processing**: Using **IBM Docling**, the platform processes PDF files, extracting structured data, tables, and text content.
- **Data Structuring**: **LlamaIndex** is used to structure the extracted data, making it easier to search, analyze, and manipulate.
- **User Interface**: Built with **Streamlit**, the platform provides a powerful and easy-to-use web interface for interacting with documents. You can upload, view, and analyze PDF files, view extracted content, and explore document metrics.

### How It Works:
1. **Upload PDF**: Users upload PDF files for processing.
2. **Extract and Analyze**: The platform uses **IBM Docling** to extract text, tables, and images, and apply advanced analysis such as OCR.
3. **Structure Data**: Extracted data is organized using **LlamaIndex**, allowing efficient querying and analysis.
4. **Interactive UI**: The user interacts with the document and extracted data through a **Streamlit** interface. This includes visualizing text content, tables, images, and document analysis metrics.

### Setup

To get started with the project, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/AhmedNazeh2/docling-pdf-processor.git
    cd docling-pdf-processor
    ```

2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Run the Streamlit app:
    ```bash
    streamlit run app.py
    ```

4. Upload your PDF documents through the web interface and start exploring the content.

### Technologies Used:
- **IBM Docling**: A powerful document processing library for text extraction, table detection, and OCR.
- **LlamaIndex**: An AI tool for structuring and organizing extracted data to enable efficient querying.
- **Streamlit**: A web framework for building interactive applications, providing a simple UI for users to interact with documents and data.

### Example Usage

Upload a PDF to the platform, and the system will process the document, extract the content, and display it on an interactive dashboard. You can analyze the document, view tables, check for extracted images, and more.

For instance, if you're processing a financial report, the platform will extract tables, figures, and text content, allowing you to explore the report's contents in a structured way.

### Contributions

Feel free to contribute to this project! If you find any issues or would like to add features, open an issue or create a pull request.

### License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Built with the power of **IBM Docling**, **LlamaIndex**, and **Streamlit**.
