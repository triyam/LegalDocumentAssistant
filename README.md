### **Repository Description**

#### **Title**
**Legal Document Assistant with Advanced Summarization and Query Filtering**

#### **Overview**
This project is an advanced **Legal Document Assistant** designed to help users interact with legal documents effortlessly. Built using **Hugging Face Transformers**, it leverages the **`facebook/bart-large-cnn` model** for text summarization and document analysis. It includes features like file upload, document metadata filtering, summarization, and intelligent Q&A functionality.

---

#### **Features**
1. **File Upload**: Upload legal documents in `.txt` or `.pdf` format for processing.
2. **Document Preprocessing**:
   - Metadata extraction for filtering (e.g., jurisdiction, date).
   - Splitting large documents into manageable chunks for better performance.
3. **Summarization**:
   - Uses `facebook/bart-large-cnn` to generate concise summaries of legal clauses or documents.
4. **Question Answering**:
   - Retrieve relevant document sections and provide meaningful answers to user queries.
5. **Advanced Search Filters**:
   - Filter results based on metadata such as jurisdiction or document date.
6. **Interactive Chatbot**:
   - Seamlessly integrates the summarization and retrieval system into a chatbot interface.
7. **Fast and Efficient**:
   - Built with `Gradio` for an interactive web interface.

---

#### **Tech Stack**
- **Programming Language**: Python
- **NLP Framework**: Hugging Face Transformers
- **Model**: `facebook/bart-large-cnn` for summarization
- **Interface**: Gradio
- **Vector Store**: FAISS for efficient similarity search

---

#### **How It Works**
1. **Upload**: Users upload legal documents.
2. **Preprocess**: Documents are split into smaller chunks and enriched with metadata (jurisdiction, date).
3. **Summarization**: Use `facebook/bart-large-cnn` to summarize key clauses.
4. **Retrieve**: Filter documents by metadata and retrieve relevant sections using FAISS.
5. **Q&A**: Ask questions, and the system retrieves and summarizes the most relevant document sections.

---

#### **Installation**
Clone the repository and install the required dependencies:

```bash
git clone https://github.com/triyam/LegalDocumentAssistant.git
```

---

#### **Example**
1. Upload a legal document related to EU jurisdiction.
2. Ask: _“What are the key principles of Eurojust?”_
3. Output: A concise summary generated using BART.

---

#### **Video Sample**

https://github.com/user-attachments/assets/e091aa81-e772-4a87-980e-9fb024026b45

---

#### **Documentation**

[Documentation for Legal Document Assistant.pdf](https://github.com/user-attachments/files/17939335/Documentation.for.Legal.Document.Assistant.pdf)

---

#### **Future Enhancements**
- Add support for multiple file formats (e.g., JPG, PNG).
- Expand metadata extraction (e.g., document type, author).
- Enable multilingual summarization.
