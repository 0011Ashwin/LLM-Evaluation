# LLM Evaluation Project

This project provides a comprehensive approach to evaluating Large Language Models (LLMs), with a focus on Retrieval-Augmented Generation (RAG) systems.

## Overview

The project demonstrates how to:
- Set up and evaluate RAG pipelines using LangChain
- Implement deterministic local embeddings as a fallback
- Use structured outputs for grading
- Visualize the LLM evaluation process through an interactive HTML interface

## Project Structure

- **LLM-Evaluation.md**: Details the setup and configuration for the evaluation notebook
- **index.html**: Interactive UI that explains how LLM evaluation works
- **README.md**: This file - project documentation

## Getting Started

1. Clone the repository
2. Review `LLM-Evaluation.md` for setup instructions
3. Open `index.html` in a browser to explore the LLM evaluation concepts

## Key Features

- **RAG Evaluation**: Demonstrates evaluation of RAG pipelines
- **Local Embeddings Fallback**: Uses deterministic `HashEmbeddings` when OpenAI API key is not available
- **Structured Outputs**: Implements grading with `ChatGroq` for structured evaluation results
- **Visual Interface**: Provides an HTML-based UI to understand the evaluation process

## Prerequisites

The evaluation notebook requires:
- `LANGSMITH_API_KEY`
- `GROQ_API_KEY`

Optional (for OpenAI embeddings):
- `OPENAI_API_KEY`

## Usage

The main notebook (`LLM-Evalution/1-RAG-evalution.ipynb`) handles:
- Loading API keys from `.env` file
- Setting up RAG components
- Evaluating responses using structured outputs
- Generating evaluation reports

## Documentation

- For setup details: See [LLM-Evaluation.md](LLM-Evaluation.md)
- For interactive concepts: Open [index.html](index.html) in your browser