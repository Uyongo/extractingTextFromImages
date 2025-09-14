# Extracting Structured Data from PDF Receipts Using LLMs

This repository contains Python code for extracting structured data from PDF receipts using a Large Language Model (LLM). Many of the PDFs are image-based—including photos taken with my Android phone—but I found that [`pdfplumber`](https://github.com/jsvine/pdfplumber) performs well without additional OCR modules.

As a contractor running a micro company, I accumulated a large number of receipts. At my accountant’s request, I needed a reference table listing each PDF filename alongside key details:
- Transaction date  
- Total amount  
- Brief expense description  

## What This Code Covers

The code is beginner-friendly and well-commented. It walks through:
- Required Python modules (minimal setup—no OCR dependencies)
- Text extraction from PDFs using `pdfplumber`
- Looping through all PDFs in a folder
- Calling an LLM to extract structured data
- Formatting results as dictionaries
- Combining all outputs into a single table

## Inspiration

This project is inspired by Ed Donner’s excellent Udemy course:  
**_LLM Engineering: Master AI, Large Language Models & Agents_**  
For further reference, see his [LLM Engineering Resources](https://edwarddonner.com/2024/11/13/llm-engineering-resources/).

---

Feel free to fork, adapt, or extend the workflow. Contributions and feedback are welcome!


