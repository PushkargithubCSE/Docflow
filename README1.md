# Built DocFlow for Copperlane YC W26 

DocFlow is a lightweight AI underwriting copilot that converts borrower documents into structured financial intelligence.

This project was built as a technical exploration inspired by Copperlane (YC W26) and their thesis around AI-native mortgage intake systems.

The goal was to explore a simple but important question:

Can borrower documents be transformed into structured underwriting signals in real time?

DocFlow attempts to prototype that pipeline.

Built in ~5 hours (6pm → 11pm) as a technical exploration of AI-native mortgage intake workflows.
## Overview

Mortgage underwriting often starts with unstructured borrower documents — payslips, bank statements, tax forms, etc.

DocFlow explores a pipeline where these documents are automatically parsed, structured, and analyzed to generate early underwriting insights.

Pipeline:

Document → Text Extraction → Structured Financial JSON → Risk Rules → Underwriting Summary

---

## Features

• PDF ingestion and parsing for borrower documents  
• AI-powered financial data extraction  
• Strict JSON schema validation  
• Deterministic underwriting risk checks  
• Automated underwriting summary generation  
• Clean product interface built with Next.js

---

## Technical Pipeline

1. **Document Ingestion**
   - Upload borrower financial documents (e.g., payslips)

2. **Text Extraction**
   - PDF parsing to obtain raw financial text

3. **AI Structured Extraction**
   - Gemini model converts unstructured text into structured financial JSON

4. **Schema Validation**
   - Ensures deterministic output fields

5. **Risk Engine**
   - Runs underwriting checks such as:
     - income variance
     - reserve adequacy
     - anomaly detection

6. **Underwriting Summary**
   - Generates explainable signals for early risk assessment

---

## Tech Stack

Next.js (App Router)  
TypeScript  
TailwindCSS  
Gemini API  
PDF Parsing  
Rule-based Risk Engine

---

## Why This Project

This prototype was built to explore the intersection of:

- AI document intelligence
- mortgage intake automation
- structured underwriting workflows

Built to showcase to the founders of Copperlane( YC W26)


## Author

Pushkar Chandra
