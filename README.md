# TENDORA
### AI-Powered Tender Intelligence & Procurement Platform

**Understand. Evaluate. Bid.**

Turn complex government tender documents into clear, evidence-backed procurement decisions.

TENDORA is an AI-powered tender intelligence platform designed to help businesses understand Indian government tenders, identify eligibility requirements, organize supporting documents, and assess bid readiness through document intelligence, semantic search, and rule-based evaluation.

---

## Overview

Government tender documents often contain hundreds of pages of technical specifications, financial conditions, eligibility criteria, and supporting forms. Extracting the relevant information manually can be time-consuming and error-prone.

**TENDORA simplifies this process** by combining document processing, information retrieval, structured data extraction, and bidder-to-tender requirement matching.

The platform is being developed as a practical AI solution for businesses, contractors, and organizations participating in government procurement.

## Key Features

### 1. Tender Document Intelligence
- Upload tender documents in PDF, Excel, and ZIP formats.
- Extract text and tables from tender documents.
- Process scanned PDFs using OCR.
- Organize extracted information by document, page, and section.
- Maintain source references for important findings.

### 2. AI-Powered Tender Q&A
- Ask natural-language questions about uploaded tenders.
- Retrieve relevant information using semantic search.
- Generate evidence-backed responses.
- Identify information that is unavailable or requires verification.
- Reference source documents and page or spreadsheet locations.

### 3. Eligibility Assessment
- Extract key eligibility requirements.
- Evaluate bidder information against tender conditions.
- Compare financial thresholds such as bank solvency and turnover.
- Identify missing information and documents.
- Generate a structured eligibility assessment.

### 4. Document Intelligence & Classification
- Upload bidder certificates and supporting documents.
- Classify documents by type.
- Extract relevant fields such as company name, PAN, GSTIN, certificate numbers, and financial values.
- Compare uploaded documents against tender requirements.
- Identify document coverage and missing submissions.

### 5. Requirement Verification
- Build a structured tender requirement register.
- Group requirements into categories.
- Connect extracted requirements to their supporting evidence.
- Flag requirements that need manual verification.

### 6. Bid Readiness Assessment
- Compare bidder information with tender requirements.
- Identify potential gaps before bid submission.
- Generate a bid-readiness report.
- Highlight items requiring further review.

### 7. Interactive Dashboard
- Tender overview and key metrics.
- Tender exploration interface.
- Tender intelligence and document center.
- AI assistant.
- Bid-readiness assessment.
- Report generation.

---

## Technology Stack

| Area | Technologies |
|---|---|
| Programming Language | Python |
| Development Environment | Google Colab |
| Document Processing | PyMuPDF, pdfplumber |
| OCR | Tesseract OCR, pytesseract |
| Data Processing | Pandas, NumPy |
| Machine Learning | Scikit-learn |
| Semantic Search | Sentence Transformers |
| Vector Search | FAISS |
| Language Model Prototype | Flan-T5 |
| Dashboard & UI | Gradio |
| Data Visualization | Plotly |
| Report Generation | Python-docx, ReportLab |
| Excel Processing | OpenPyXL, xlrd |

---

## System Workflow

1. **Tender Upload:** Upload tender documents in supported formats.
2. **Document Processing:** Extract text, tables, and structured information.
3. **Information Indexing:** Convert extracted content into searchable semantic chunks.
4. **Tender Intelligence:** Retrieve relevant evidence using semantic search and verification rules.
5. **Bidder Document Processing:** Classify uploaded certificates and extract relevant information.
6. **Requirement Matching:** Compare bidder information against tender conditions.
7. **Bid Readiness:** Generate an assessment highlighting matches, gaps, and verification requirements.
8. **Reporting:** Produce structured reports for further review.

---

## AI & Data Intelligence

TENDORA combines multiple techniques rather than relying entirely on generated responses.

| Component | Approach |
|---|---|
| Text Extraction | PDF parsing and OCR |
| Table Extraction | Structured PDF and Excel extraction |
| Semantic Retrieval | Sentence Transformers |
| Vector Search | FAISS similarity search |
| Requirement Identification | Rule-based keyword and contextual matching |
| Eligibility Evaluation | Threshold-based rule engine |
| Document Classification | Rule-based document classification |
| Field Extraction | Pattern-based and structured extraction |
| Evidence Verification | Source-linked retrieval and verification rules |

### Reliability Approach

Procurement decisions require accuracy and traceability. TENDORA follows these principles:

- Important findings should be linked to their original source.
- Missing information should not be treated as a confirmed requirement.
- Unverified values should be marked for review.
- Financial thresholds should be evaluated using explicit rules wherever possible.
- AI-generated responses should not replace official tender documents.
- Document extraction does not establish certificate authenticity.

---

## Demonstration Dataset

The current development and testing workflow uses a sample BARC tender package concerning:

**Replacement of IBR steam piping, fittings & steam pressure reducing station at PRTRF, FRD, BARC, Trombay, Mumbai.**

The test package includes:
- Technical specifications.
- Tender documents.
- Schedules and forms.
- Bill of Quantities (BOQ).
- Technical bid spreadsheets.

Synthetic bidder certificates are also used to test document classification and requirement matching. These documents are clearly marked as synthetic and are not valid for official submission.

---

## Project Structure

```text
TENDORA/
│
├── TENDORA.ipynb
├── README.md
├── requirements.txt
└── .gitignore
```

The current repository contains the Colab-based prototype. The project is intended to evolve into a modular application with separate processing, intelligence, backend, and frontend components.

---

## Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/rushikulkarni-design/TENDORA.git
cd TENDORA
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Install Tesseract OCR

For Ubuntu or Google Colab:

```bash
sudo apt-get update
sudo apt-get install -y tesseract-ocr
```

### 4. Run the Notebook

Open `TENDORA.ipynb` in Google Colab or Jupyter Notebook.

Execute the notebook cells in sequence, upload the required tender documents, and follow the workflow.

---

## Current Development Status

**Project Stage: Working Research Prototype**

| Module | Status |
|---|---|
| PDF and Excel Extraction | Implemented |
| OCR Processing | Implemented |
| Document Inventory | Implemented |
| Semantic Search with FAISS | Implemented |
| Tender Q&A Prototype | Implemented |
| Evidence-Based Fact Verification | Implemented |
| Eligibility Assessment Engine | Implemented |
| Requirement Register | Implemented |
| Bidder Document Classification | Implemented |
| Certificate Field Extraction | Implemented |
| Bidder-Tender Matching | Implemented |
| Bid Readiness Report | Implemented |
| Gradio Dashboard | Prototype |
| End-to-End UI Upload Integration | In Development |
| Modular Backend and Frontend | Planned |
| Official Tender Portal Integration | Planned |

---

## Limitations & Responsible Use

TENDORA is an experimental decision-support prototype, not an official government procurement platform or a substitute for professional tender evaluation.

- Extracted information may require manual verification.
- OCR and document classification can produce errors.
- Some eligibility conditions may require human interpretation.
- A detected certificate does not prove its authenticity or validity.
- Tender requirements and submission conditions must always be checked against the latest official tender documents.
- No automated bid submission or official portal scraping is currently claimed.

**Always refer to the official tender documents before making procurement or bidding decisions.**

---

## Potential Future Enhancements

- Automated tender discovery from official procurement portals.
- Tender recommendations based on bidder profiles.
- Advanced LLM-based document reasoning with evidence citations.
- Improved BOQ analysis and financial comparison.
- Automated compliance checklist generation.
- Multi-tender comparison.
- Modular FastAPI backend.
- Dedicated React/Next.js frontend.
- Cloud deployment and secure document storage.

---

## Official Procurement Portals

- [Central Public Procurement Portal (CPPP)](https://eprocure.gov.in/eprocure/app)
- [Maharashtra e-Tendering Portal](https://mahatenders.gov.in/)
- [Government e-Marketplace (GeM)](https://bidplus.gem.gov.in/bidlists)

---

## Author

**Rushi Kulkarni**  
Artificial Intelligence & Data Science

GitHub: [@rushikulkarni-design](https://github.com/rushikulkarni-design)

**Repository:** [TENDORA](https://github.com/rushikulkarni-design/TENDORA)

---

<p align="center">
  <strong>TENDORA — Understand. Evaluate. Bid.</strong><br/>
  Turning complex tender documents into clearer procurement decisions.
</p>
