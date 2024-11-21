# AI Workflow Automation with LangChain, ChromaDB, and Groq

This project demonstrates an AI-powered workflow using **LangChain**, **ChromaDB**, and **Groq** to extract job information from web pages, manage a vector-based portfolio, and generate personalized cold emails.

## Features
- **Web Scraping and Job Post Extraction**: Scrape data from career pages and extract job postings into structured JSON format.
- **Portfolio Management with ChromaDB**: Use a persistent vector database to store, query, and manage portfolio data.
- **Cold Email Automation**: Generate tailored cold emails with dynamic inclusion of portfolio links using LangChain's pipeline.

## File Structure
- `tutorial_chromadb.ipynb`: Contains the implementation of portfolio vector storage and query using **ChromaDB**.
- `tutorial_groq.ipynb`: Details the job extraction and email generation pipeline using **LangChain** and **Groq**.
- `requirements.txt`: Python dependencies required to run the project.

## Prerequisites
- Python 3.10+
- API keys for Groq LLM and ChromaDB

## Setup
**Clone the repository**:
   ```bash
   git clone <repository_url>
   cd <repository_directory>
```
## Usage

### 1. Web Scraping and Job Extraction
The script uses `WebBaseLoader` to fetch web content and LangChain's prompt templates to extract job postings into JSON format. Example job attributes include:
- `role`
- `experience`
- `skills`
- `description`

### 2. Portfolio Management with ChromaDB
Store and query portfolio data in a vector database. This step involves:
- Adding `tech stack` descriptions as vectors.
- Associating links for portfolio examples.
- Querying the database to find relevant projects based on job skills.

### 3. Cold Email Generation
LangChain pipelines generate dynamic, personalized emails tailored to job descriptions. The emails include links from the portfolio database to demonstrate expertise.

## Running the Code

### 1. Run `tutorial_groq.ipynb`:
- Extract job information from web pages.
- Generate personalized cold emails.

### 2. Run `tutorial_chromadb.ipynb`:
- Manage and query portfolio data.
### 3. Use `main.py `:
- Run on Streamlit directly 

## Example Output

**Email**:
```plaintext
Subject: Expert AI/ML Solutions for Nike's Data Science Services and Platform

Dear Hiring Manager,

... [personalized email content] ...
Best regards,  
Mohan  
Business Development Executive  
AtliQ
