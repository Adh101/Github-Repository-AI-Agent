# Github-Repository-AI-Agent

## 📋 Project Overview:
This project demonstrates the creation of an AI Agent that can process and analyze content from GitHub repositories.

### Key Features:
 - Multi-format Data Pipeline: Downloads and processes various file types from GitHub repositories
 - Code-aware Processing: Handles Python, SQL, Java files alongside markdown content
 - Intelligent Content Extraction: Uses frontmatter parsing and content analysis
 - RAG-ready Data Preparation: Prepares data for chunking and vector search

### Supported File Types:
 - Markdown files (.md, .mdx)
 - Python scripts (.py)
 - SQL files (.sql)
 - Java files (.java)
 - Jupyter notebooks (.ipynb)
------------------------------
## 🚀 Getting Started
### 1. Clone the repository
```
git clone https://github.com/alexeygrigorev/data-engineering-rag.git
cd project
```
### 2. Install dependencies:
```
uv sync --dev
```
### 3. Set up OpenAI API Key:
```
export OPENAI_API_KEY='your-actual-openai-key'
```
### 4. Run the data processing pipeline: Open and run the data-processing.ipynb notebook to download and process repository data.
