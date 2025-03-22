# Multimodal Retrieval Augmented Generation (RAG) using the Gemini API in Vertex AI

This repository contains the Jupyter Notebook and related resources for the Google Cloud Skills Boost lab: **Multimodal Retrieval Augmented Generation (RAG) using the Gemini API in Vertex AI (GSP1231).**

## Overview

This lab demonstrates how to implement Multimodal Retrieval Augmented Generation (RAG) using the Gemini API on Vertex AI. You'll learn how to build a document search engine capable of querying financial documents containing both text and images. By combining text and image embeddings, you'll enhance the retrieval process and improve the accuracy of question-answering systems.

## Key Concepts

* **Gemini API:** Utilizing Google DeepMind's Gemini family of generative AI models for multimodal use cases.
* **Retrieval Augmented Generation (RAG):** Accessing external data to improve LLM responses and mitigate hallucinations.
* **Multimodal RAG:** Processing and retrieving information from both textual and visual data sources.
* **Embeddings:** Generating text and image embeddings for efficient similarity searches.

## Lab Objectives

In this lab, you will:

* Extract and store metadata from documents with text and images.
* Generate embeddings for documents.
* Perform text-based searches to find similar text and images.
* Perform image-based searches to find similar images.
* Implement multimodal RAG to answer questions using both text and images.

## Prerequisites

* Basic Python programming knowledge.
* General understanding of API concepts.
* Experience running Python code in Jupyter notebooks on Vertex AI Workbench.

## Lab Contents

* **`intro_multimodal_rag.ipynb`**: The main Jupyter Notebook containing the lab exercises.
* **`intro_multimodal_rag_utils.py`**: Helper functions used in the notebook.
* **Data:** Images and documents used in the lab (downloaded from Cloud Storage during the lab).

## Lab Tasks

1.  **Open the notebook in Vertex AI Workbench:**
    * Navigate to Vertex AI > Workbench in the Google Cloud console.
    * Open the JupyterLab instance.
2.  **Set up the notebook:**
    * Open `intro_multimodal_rag.ipynb`.
    * Select the Python 3 kernel.
    * Install necessary libraries and configure the environment.
3.  **Use the Gemini Pro model:**
    * Download helper functions and load the Gemini Pro model.
    * Download documents and images from Cloud Storage.
4.  **Build metadata of documents:**
    * Extract and store metadata for text and images from the provided financial documents.
5.  **Text Search:**
    * Use text embeddings to search for relevant information based on text queries.
6.  **Image Search:**
    * Use image embeddings to search for similar images based on image queries.
7.  **Multimodal RAG:**
    * Implement a multimodal RAG system to answer questions using both text and image context.

## Setup and Requirements

* Access to a standard internet browser (Chrome recommended).
* Use an Incognito or private browser window.
* Time to complete the lab (approximately 1 hour).
* Temporary Google Cloud credentials provided by the lab.

## How to Start the Lab

1.  Click the "Start Lab" button in Google Cloud Skills Boost.
2.  Open the Google Cloud console using the provided credentials.
3.  Navigate to Vertex AI > Workbench.
4.  Open the JupyterLab instance.
5.  Follow the instructions within the `intro_multimodal_rag.ipynb` notebook.

## Additional Resources

* [Vertex AI Documentation](https://cloud.google.com/vertex-ai/docs)
* [Gemini API Documentation](https://cloud.google.com/vertex-ai/docs/generative-ai/gemini/get-started)
* [Google Cloud Skills Boost](https://www.cloudskillsboost.google)
