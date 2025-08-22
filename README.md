# RAG (Retrieval-Augmented Generation) System

A Wikipedia-based RAG system that scrapes data, creates vector embeddings, and performs hybrid search to provide context-aware LLM responses.

## System Overview

```
Wikipedia → Scraping → Chunking → Vector DB → Hybrid Search → LLM
```

## Quick Start

1. **Scrape Data**: Run `wiki_scrapy.py` with your topics and language
2. **Build Vector DB**: Execute `rag_training.ipynb` 
3. **Query System**: Use `rag.ipynb` to ask questions

## Key Features

- **Flexible Scraping**: Any Wikipedia topics in 10+ languages
- **Hybrid Search**: Semantic + Lexical search combination
- **Reranking**: Improves search result quality
- **ChromaDB**: Vector database for embeddings
- **LLM Integration**: Context-aware responses


**Note**: Modify `topics list`  in `wiki_scrapy.py` to scrape any Wikipedia content you want!



# Database – Wikipedia Country Pages

This dataset contains vectorized representations of the full English Wikipedia pages for all 195 recognized countries. 
--- 
  You don't have to use the provided data. You can download any Wikipedia pages you want with wiki_scrapy.py and vectorize them with rag_training.ipynb.

Wikipedia Country txt files:
https://drive.google.com/drive/folders/1Ul_PlLsLzslfYF8BxshJDUW82KjWWNt_?usp=sharing

Vector Database:
https://drive.google.com/drive/folders/1XzwrvNdPLqMtNifOn36Lo-_4aE9JDKOb?usp=drive_link


