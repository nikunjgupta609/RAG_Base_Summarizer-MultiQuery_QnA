# RAG-Based Summarizer and Multi-Query QnA

## About the Project
This project is a **RAG-Based Summarizer and Multi-Query Question Answering System** designed to process various document formats and provide structured, concise information. The tool extracts key insights from uploaded documents and enables users to ask multiple queries about the content, delivering precise answers based on the given data.

### Key Features:
- Summarization of documents using a **Graph-based Semantic Relation Analysis** approach.
- Multi-query question-answering system for in-depth analysis of documents.
- Supports multiple file formats, including `.doc`, `.pdf`, `.json`, and plain text.
- Frontend developed using **Next.js** for seamless user interaction.
- Backend powered by **Python** and **LLM-based APIs** for text processing.

## Technologies Used
This project is built using the following technologies:

1. **Frontend**
   - Next.js (React Framework)
   - TypeScript
   - Tailwind CSS
   
2. **Backend**
   - Python (FastAPI / Flask for API development)
   - LangChain for RAG-based summarization and QnA
   - OpenAI GPT API for text generation
   
3. **Database & Storage**
   - PostgreSQL / MongoDB for storing document data
   - AWS S3 / Cloudinary for document storage

4. **Additional Tools & Libraries**
   - Tesseract OCR for text extraction from images in PDFs
   - PyMuPDF for PDF parsing
   - Puppeteer for webpage text extraction

## Installation Guide
To set up the project on your local system, follow these steps:

### 1. Clone the Repository
```sh
git clone https://github.com/your-username/RAG-Summarizer-MultiQnA.git
cd RAG-Summarizer-MultiQnA
```

### 2. Install Dependencies
#### **Backend (Python)**
```sh
cd backend
python -m venv env
source env/bin/activate  # On Windows: env\Scripts\activate
pip install -r requirements.txt
```

#### **Frontend (Next.js)**
```sh
cd frontend
npm install
```

### 3. Run the Backend Server
```sh
cd backend
uvicorn app:app --reload  # For FastAPI users
```

### 4. Run the Frontend Application
```sh
cd frontend
npm run dev
```

## Project Directory Structure
```
RAG-Summarizer-MultiQnA/
│── backend/                # Backend API service
│   ├── app.py              # Main backend application
│   ├── models/             # Model definitions
│   ├── routes/             # API routes
│   ├── utils/              # Utility functions
│   ├── data/               # Sample data
│   └── requirements.txt    # Python dependencies
│
│── frontend/               # Frontend UI (Next.js)
│   ├── pages/              # Page components
│   ├── components/         # UI components
│   ├── styles/             # CSS styles
│   ├── public/             # Static assets
│   ├── package.json        # Frontend dependencies
│   └── tsconfig.json       # TypeScript configuration
│
│── docs/                   # Documentation & resources
│── README.md               # Project documentation
└── .gitignore              # Git ignore file
```

## Resources
- [Next.js Documentation](https://nextjs.org/docs)
- [FastAPI Documentation](https://fastapi.tiangolo.com/)
- [LangChain Documentation](https://python.langchain.com/en/latest/)
- [OpenAI GPT API](https://beta.openai.com/docs/)
- [Tesseract OCR](https://github.com/tesseract-ocr/tesseract)

---
**Contributions & Issues:** If you find a bug or want to improve the project, feel free to open an issue or submit a pull request. 🚀

