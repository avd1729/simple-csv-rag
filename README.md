# CSV-RAG: Prompt-Tuned Retrieval over CSV

A minimal Retrieval-Augmented Generation (RAG) setup that answers questions from CSV data and demonstrates how **prompting techniques** impact **response relevancy**.

## What It Does

* Loads a CSV file as the knowledge base
* Retrieves relevant rows using vector search
* Generates answers using an LLM based on the retrieved context and user prompt
* Allows experimentation with prompt phrasing to observe its effect on answer quality

## Purpose

This project helps explore how different prompting styles—like instructions, chain-of-thought, few-shot examples, and output constraints—can improve the accuracy, clarity, and relevance of answers generated from structured tabular data.

## Try Prompts Like

* "Summarize sales by region."
* "Act as a financial analyst. What insights can you give from January data?"
* "Think step by step before answering. What’s the total revenue?"

## Components

* CSV parser and chunker
* Vector retriever for similarity search
* Prompt formatter
* LLM for final answer generation

## Why It Matters

Even with the same data and model, **prompt wording significantly influences the quality of answers**. This project is a hands-on way to test and learn prompt engineering in a structured data context.

