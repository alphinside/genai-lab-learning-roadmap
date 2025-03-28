# GenAI Lab Learning Roadmap
This repository contains selected notebooks and codelabs to learn fundamentals and application use cases of GenAI on Cloud

`Notebook` sources is a python notebook complete with code and comments. `Codelab` sources is an self-followed instruction set to build application

## Selected Resources

| Type | Language | Title | Key Learning Points | Keywords |
|---|---|---|---|---|
| Notebook | Python | [Intro Gemini 2.0 Flash](https://github.com/GoogleCloudPlatform/generative-ai/blob/main/gemini/getting-started/intro_gemini_2_0_flash.ipynb) | - Text Generation<br>- Multi-turn conversations<br>- Asynchronous requests<br>- Model parameters and system instructions<br>- Multimodal prompts<br>- Safety Filters<br>- Structured Output<br>- Function Calling | Gemini API |
| Notebook | Python | [Context Caching](https://github.com/GoogleCloudPlatform/generative-ai/blob/main/gemini/context-caching/intro_context_caching.ipynb) | - Efficient token usage<br>- Context caching techniques | Gemini API |
| Codelab | Python | [Build a Gemini-Powered YouTube Summarizer](https://codelabs.developers.google.com/devsite/codelabs/build-youtube-summarizer) | - Create a Gemini-powered back-end API using Flask<br>- Build a GenAI app linking front-end and back-end<br>- Deploy the developed GenAI application on Cloud Run | Gemini API<br>Cloud Run|
| Codelab | Python | [Build and Deploy Multimodal Assistant on Cloud with Gemini (Python)](https://codelabs.developers.google.com/devsite/codelabs/gemini-multimodal-chat-assistant-python) | - Use Gemini SDK to submit text and other data type (multimodal)<br>- Structure chat history into Gemini SDK to maintain conversation context<br>- Frontend web prototyping with Gradio<br>- Backend service development with FastAPI and Pydantic<br>- Deploy application to Cloud Run using Dockerfile and provide environment variables with YAML file | Gemini API<br>Cloud Run|
| Codelab | Python | [Build a contextual Yoga Poses recommender app](https://codelabs.developers.google.com/yoga-pose-firestore-vectorsearch-python) | - Use Gemini to generate text descriptions for yoga poses<br>- Use Langchain Document Loader for Firestore with Hugging Face dataset<br>- Use Langchain Vector Store for natural language search<br>- Use Google Cloud Text to Speech API for audio content | Gemini API<br>Cloud Run<br>Firestore<br>Text to Speech API<br>Langchain|