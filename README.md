
# TENDORA
### Understand. Evaluate. Bid.

**AI-Powered Tender Intelligence & Procurement Platform**

TENDORA is an AI-assisted procurement intelligence prototype
designed to help businesses understand Indian government tenders,
review eligibility requirements and organize bidder documentation.

## Key Features

- Government tender PDF and Excel ingestion
- Document text and table extraction
- OCR-assisted PDF processing
- Semantic search using Sentence Transformers and FAISS
- Evidence-based tender question answering
- Financial requirement extraction
- Bidder certificate information extraction
- Tender requirement matching
- Bid-readiness assessment
- Interactive Gradio dashboard

## Technology Stack

| Area | Technologies |
|---|---|
| Language | Python |
| Interface | Gradio |
| PDF Processing | PyMuPDF, pdfplumber |
| OCR | Tesseract, pytesseract |
| Data Processing | Pandas, NumPy |
| Embeddings | Sentence Transformers |
| Vector Search | FAISS |
| Visualization | Plotly |
| Language Model Prototype | FLAN-T5 |

## Project Structure

```text
TENDORA/
├── TENDORA.ipynb
├── README.md
├── requirements.txt
└── .gitignore
```

## Getting Started

1. Open the notebook in Google Colab.
2. Install the required dependencies.
3. Upload a tender document package.
4. Run the notebook cells sequentially.
5. Review extracted tender information and evidence.
6. Upload bidder documents for testing.
7. Explore the TENDORA dashboard.

## Reliability and Limitations

TENDORA is a prototype, not an official government procurement
system or a legal eligibility authority.

Extracted values must be checked against their original source
documents. Unverified criteria must remain marked for review.

Synthetic certificates are used only for software testing.
They are not valid official documents.

## Data and Privacy

Do not upload confidential tender documents, bidder records,
API keys, passwords or private certificates to this repository.

## Project Status

Prototype under active development.
