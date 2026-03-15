# Web-Scraping-File-System-Manipulation
Automated web scraping project that collects Hugging Face Vision Transformer model documentation using Python, Selenium, BeautifulSoup, and Requests, and stores the extracted text in structured folders for further AI/ML processing or search tasks.
# Hugging Face Vision Model Documentation Scraper

## Overview

This project automatically collects documentation of **Vision models from Hugging Face Transformers**.
The script navigates the Hugging Face documentation website, extracts model information, and saves the cleaned text locally in structured folders.

The collected documentation can be used for:

* AI knowledge bases
* LLM retrieval systems
* Searchable documentation datasets
* NLP preprocessing tasks

---

## Features

* Automatically navigates Hugging Face documentation
* Extracts Vision Transformer model pages
* Removes unnecessary HTML elements
* Saves clean text documentation
* Creates structured folders for each model
* Includes fallback model list if dynamic scraping fails

---

## Technologies Used

* Python
* Selenium
* BeautifulSoup
* Requests
* WebDriver Manager

---

## Project Structure

```
Task3.ipynb

Vision_Models/
│
├── vit/
│   └── documentation.txt
│
├── swin/
│   └── documentation.txt
│
├── convnext/
│   └── documentation.txt
│
└── other_models/
    └── documentation.txt
```

Each model folder contains the extracted documentation in **documentation.txt**.

---

## Installation

Install required libraries:

```
pip install requests
pip install beautifulsoup4
pip install selenium
pip install webdriver-manager
```

---

## Workflow

1. Open Hugging Face Transformers documentation.
2. Detect Vision model documentation links using Selenium.
3. If links are not detected, use a fallback list of models.
4. Download each documentation page using Requests.
5. Extract clean text using BeautifulSoup.
6. Save the extracted documentation locally.




nd research purposes.
