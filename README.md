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

