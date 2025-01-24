BERT-GovPII

This project is a machine learning application designed to identify government-issued Personally Identifiable Information (PII) embedded within documents and datasets. By leveraging the power of the BERT tokenizer, the tool detects sensitive information like Aadhaar numbers, PAN numbers, and names in file formats such as `.docx`, `.pdf`, and `.txt`. The primary goal is to ensure data security, confidentiality, and compliance with privacy standards.

---

Features

- PII Detection: Identifies Aadhaar numbers, PAN numbers, and names in uploaded documents.
- File Format Support: Compatible with `.docx`, `.pdf`, and `.txt` file types.
- AI-Powered Analysis: Uses a fine-tuned BERT model for efficient and accurate detection of sensitive data.
- User-Friendly Interface: Allows easy file uploads and provides clear reports on detected PII.
- Customizability: Extendable to include detection of other types of PII or sensitive information.

---

Tech Used

- Programming Language: Python
- Machine Learning Framework: Hugging Face Transformers (BERT)
- Web Framework: Flask or Streamlit (as per the implementation)
- File Handling Libraries: `PyPDF2`, `python-docx`
- Data Processing: `pandas`, `numpy`

---

Models

The project utilizes three separate fine-tuned BERT models:

1. Name Detection Model: Identifies Indian and non-Indian names.
2. Aadhaar Detection Model: Recognizes valid Aadhaar number patterns.
3. PAN Detection Model: Detects valid PAN numbers based on structure and context.

All models are stored in the `models/` directory and loaded dynamically during runtime.

---

Contact

For questions or feedback, reach out to:

- Name: Aditya M Hubli
- Email: adityahubli6@gmail.com



