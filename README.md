# Bio LLM Assistant 🧬

A *Bioinformatics Q&A assistant* built in Google Colab using a generative language model.  
It reads your notes and answers questions in *full, relevant sentences*.

## Features
- Handles multiple bio topics (CRISPR, RNA-Seq, NGS, etc.)  
- Generates *complete answers*, not tiny snippets  
- Easy to add new topics or questions  
- Fully contained in a *single Colab notebook*, no CSV needed  

## How to Use
1. Open the notebook in Google Colab  
2. Paste your bio notes into the contexts list  
3. Add your questions to the questions list  
4. Run the notebook → answers appear below each question  

## Requirements
- Python 3  
- transformers library  
- torch library  
- Google Colab recommended  

## Installation (Local)
```bash
pip install transformers
