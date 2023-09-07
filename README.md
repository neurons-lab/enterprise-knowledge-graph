# Enterprise Knowledge Graph and AI Automation Solution

This project demonstrates using an enterprise knowledge graph and AI models to automate manual business workflows. It accompanies a 2-part video series on YouTube.

## Overview

Many document-heavy business processes like RFP responses, audits, assessments, and proposal generation rely extensively on tribal knowledge spread across an organization's documents and experts. This results in inefficient, repetitive manual effort to extract and combine relevant information each time the process runs.

This project aims to transform such workflows into automated, self-serving processes by: 

- Extracting unstructured data from company sources into a structured knowledge graph
- Developing a conversational interface via natural language processing models to query the graph  
- Generating outputs like reports and proposals using large language models

## Contents

The repository contains code and instructions to:

- [**Part 1:** Extract documents and build the knowledge graph database](https://youtu.be/zYDqvbYMOos) 
- [**Part 2:** Develop the conversational AI interface with LangChain and OpenAI](https://youtu.be/3xVckUGsomk)

## Knowledge Graph Construction 

- Extract documents from company sources like SharePoint, GitHub, internal wikis
- Clean, preprocess, and split documents using headers
- Generate embeddings for documents using sentence encoders  
- Store documents and embeddings in a vector database 
- Build helper functions to query the database for relevant contexts

## Conversational Interface

- Initialize a large language model like GPT-3.5
- Create a QA pipeline with LangChain
- Pass questions through knowledge graph to find contexts 
- Feed contexts into LLM to generate answers
- Continuously expand knowledge graph   
- Automate workflows by querying in natural language

## Demo Use Case

The demo automates answering questions for an internal audit across categories like security, access control, IP policy etc. The knowledge graph is built from a hypothetical company's handbook on GitHub.

## Installation 

Provide instructions for setting up the environment and dependencies to run the notebooks.

```bash
pip install -r requirements.txt
```
