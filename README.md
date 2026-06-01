# Smart Academic Form Processing System Using Vision-Language Models

## Overview

The Smart Academic Form Processing System is an AI-powered document processing solution designed to automate the extraction, validation, and management of student academic forms. The system leverages Vision-Language Models (VLMs) and reasoning models to transform unstructured form images into structured, validated records with minimal human intervention.

## Features

* Automated extraction of student information from scanned academic forms
* Context-aware validation of extracted data
* Structured JSON generation for downstream processing
* Automatic Excel logbook generation
* Automatic Word report generation
* User-friendly Gradio interface for form uploads
* Secure offline execution using local AI models

## System Architecture

1. Form Upload through Gradio Interface
2. Image Preprocessing
3. Text Extraction using Qwen2-VL-2B-Instruct
4. Data Validation using DeepSeek-R1-7B
5. Structured JSON Generation
6. Excel and Word Report Generation

## Technologies Used

* Python
* Gradio
* Ollama
* Qwen2-VL-2B-Instruct
* DeepSeek-R1-7B
* OpenPyXL
* python-docx
* Pandas

## Results

* Field Extraction Accuracy: 91.2%
* Critical Field Accuracy: 94.67%
* Automation Success Rate: 97%
* Reduced average processing time from 180 seconds to 84.59 seconds

## Project Team

* Aditi M
* Anushka Gaur
* Ayushi Ghosh
* Deshna Jain

## Future Enhancements

* Cloud deployment support
* ERP integration
* Multi-language form processing
* Mobile application support
* Analytics dashboard for academic administration

## Repository Structure

├── notebooks/
├── dataset/
├── outputs/
├── reports/
├── images/
├── requirements.txt
└── README.md

## License

This project was developed as part of the Mini Project coursework for the Department of Computer Science and Engineering, M.S. Ramaiah Institute of Technology.
