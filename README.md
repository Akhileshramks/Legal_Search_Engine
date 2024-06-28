# Needhi Legal Search

## Overview
**Needhi Legal Search** is a specialized search engine designed to enhance accessibility and awareness of legal information in India. It aims to simplify the retrieval and understanding of legal documents for ordinary citizens, lawyers, and judges. By leveraging advanced technologies in Natural Language Processing (NLP) and Information Retrieval (IR), Needhi Legal Search democratizes access to legal knowledge and promotes transparency within the legal system.

## Features
- **Advanced Search Functionality:** Tailored for legal professionals, including filters for date, judge, and appeal type to facilitate precise document retrieval.
- **Simple Search Interface:** Designed for the general public, allowing free-text searches without needing detailed legal knowledge.
- **Interactive Visualizations:** Includes an India Map highlighting top keywords per state and a network graph of related documents to enhance user understanding and engagement.
- **Automatic Summarization:** Provides quick insights into case documents, making it easier to find pertinent information.

## System Design
The system architecture of Needhi Legal Search utilizes a Vector Space Model (VSM) for efficient retrieval of unstructured legal data. Key components include:
- **Document Preprocessing:** Tokenization, normalization, and Named Entity Recognition (NER) to enrich document metadata.
- **Indexing and Retrieval:** Using VSM and TF-IDF weighting for accurate document ranking and retrieval.
- **User Interface:** A responsive and intuitive interface built with HTML/CSS and modern JavaScript frameworks.

## Implementation
- **Backend:** Python with Flask for API creation and management.
- **Frontend:** HTML/CSS, JavaScript (React/Vue.js) for interactive and responsive user interfaces.
- **Data Processing:** Incorporates NLP techniques for data preprocessing, including tokenization, NER, and TF-IDF weighting.

## Workflow
1. **User Query Submission:** Users submit queries through the search interface.
2. **Query Preprocessing:** Tokenization and NER to enhance query understanding.
3. **Indexing and Retrieval:** VSM-based document retrieval using cosine similarity.
4. **Document Ranking and Presentation:** Ranked documents are presented with key sections highlighted.

## Future Enhancements
- **Dataset Expansion:** Incorporating OCR modules for offline documents.
- **Collaborations:** Working with legal institutions to expand the dataset.
- **Integration:** Connecting with existing legal databases for comprehensive access to legal information.

## Acknowledgements
This project was developed by Akhilesh Ram K S, Dept of Information Technology, Madras Institute of Technology. Inspired by personal experiences with the legal system's complexities, this project aims to empower individuals and legal professionals in their pursuit of justice.
