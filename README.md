# Simple RAG Chatbot with Langchain

## Overview
The goal of this project is to develop a **domain-specific application** that combines the strengths of a **Large Language Model (LLM)** with the **efficiency of a vector database** for data storage and retrieval. Using **Retrieval-Augmented Generation (RAG)** for the method and **Streamlit** for the front-end, the application is built with Python.

## Technology Stack:
- **Frontend**: Streamlit for building the user interface.
- **Vector Database**: Pinecone for efficient data storage and retrieval. 
- **LLM**: Ollama LLM model running on a local machine for natural language processing and query handling.
- **Backend**: LangChain framework utilizing the RAG method.

## Project Structure
- **src/**: Contains Python-based chatbot script and Streamlit main script.
- **src/materials/**: Contains data that our model will use to answer questions.
- **report/**: Stores [Report](report) files.
- **video/**: Contains [video](video) presentation. You can also watch the video on [YouTube](https://youtu.be/wo-0wUplqSM).
- **.env**: Contains API keys.

## Dependencies
- Python 3.7+
- langchain
- pinecone-client
- python-dotenv
- streamlit
- pypdf

## Usage
1. Clone the repository: `git clone https://github.com/Faridghr/Simple-RAG-Chatbot.git`
2. Navigate to the project directory: `cd Simple-RAG-Chatbot`
3. Install dependencies: `pip install -r requirements.txt`
4. Set up your LLM.
5. Set up your Pinecone API key in `.env` file.
5. Navigate to src directory: `cd src`
6. Run the Streamlit application: `streamlit run streamlitMain.py`
7. Open your web browser and navigate to the URL provided by Streamlit (usually http://localhost:8501).
8. Interact with the chatbot by typing messages and receiving responses from the local LLM service.

## Setting Up OpenAI API
1. Enter our OpenAI account and navigate to [OpenAI Platform](https://platform.openai.com/apps). 
2. Navigate to the API section.
3. Proceed to create a new API key by pressing '+ Create' new secret key.
4. Select a suitable name to remember and press the Create secret key button.
5. Copy the secret key and add your OpenAI API Keys in a file called `.env`.

## Setting up Pinecone
1. To create a PineCone account, sign up via this link: [Pinecone](https://www.pinecone.io/)
2. After registering with the free tier, go into the project, and click on Create a Projec.
3. Fill in the Project Name, Cloud Provider, and Environment. In this case, I have used “SimpleRAGChatbot Application” as a Project Name, GCP as Cloud Provider, and Iowa (gcp-starter) as an Environment.
4. After the project is created, go into the API Keys section, and make sure you have an API key available. Do not share this API key.
5. After completing the account setup, you can add your Pinecone API Keys in a file called `.env`.


