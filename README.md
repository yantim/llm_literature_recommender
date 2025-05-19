# llm_literature_recommender
This project is an AI-powered book recommendation system that uses LLMs, semantic search, and emotion analysis to match user queries with relevant literature titles.

## 🔍 What It Does

Users can input natural language queries like _"Books about overcoming adversity and personal growth"_ and get personalized recommendations based on:

- Semantic similarity (meaning, not keywords)
- Emotional tone (joy, sadness, suspense, etc.)

## ✨ Features

- 🔎 **Semantic Search**: Matches queries with book descriptions using OpenAI embeddings.
- 😊 **Emotion Filtering**: Filters books by the dominant emotion in their description.
- 💻 **Interactive Web UI**: Built with Gradio for simple input and instant results.
- ⚡ **Vector Search Engine**: Uses ChromaDB for fast embedding lookup.
- 🧠 **Sentiment & Emotion Classifiers**: Extracts deeper signals from book summaries.
