# GenAI Lab Learning Roadmap
This repository contains selected notebooks and codelabs to learn fundamentals and application use cases of GenAI on Cloud

`Notebook` sources is a python notebook complete with code and comments. `Codelab` sources is an self-followed instruction set to build application

## Getting Started

- [[Notebook] Intro Gemini 2.0 Flash](https://github.com/GoogleCloudPlatform/generative-ai/blob/main/gemini/getting-started/intro_gemini_2_0_flash.ipynb) : Fundamental on how to use Gemini 2.0 using it's SDK, learn the following things:
  
  - Text Generation
  - Start multi turn conversation
  - Asynchronous request
  - Model parameters and system instructions
  - Multimodal prompt
  - Safety Filters
  - Structured Output
  - Function Calling
- [[Notebook] Context Caching](https://github.com/GoogleCloudPlatform/generative-ai/blob/main/gemini/context-caching/intro_context_caching.ipynb): Learn how to use context caching to improve cost efficiency from frequently used input tokens

## Start Building

- [[Codelab] Build a Gemini-Powered YouTube Summarizer ](https://codelabs.developers.google.com/devsite/codelabs/build-youtube-summarizer): Build a cloud application with web interface to summarize YouTube videos, what you'll learn:
    - Create a Gemini-powered back-end API using Flask API library
    - Build a GenAI app link the front-end and back-end together
    - Deploy the developed GenAI application on Cloud Run
- [[Codelab] Build a contextual Yoga Poses recommender app with Firestore, Vector Search, Langchain and Gemini](https://codelabs.devsite.corp.google.com/yoga-pose-firestore-vectorsearch-python): You will build out an application that uses vector search to recommend Yoga poses, what you'll learn:
  - Use Gemini to generate text descriptions for yoga poses
  - Use Langchain Document Loader for Firestore to load records from an enhanced dataset from Hugging Face into Firestore along with Vector Embeddings
  - Use Langchain Vector Store for Firestore to search for data based on a natural language query
  - Use Google Cloud Text to Speech API to generate Audio content