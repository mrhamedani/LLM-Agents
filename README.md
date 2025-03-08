# LLM-Agents

 Apply agents and Implement Strategies for Large Language Models


**1-Chatbot-Panel-OpenAI.ipynb:**

Create a simple chatbot with openai API and then create a menu to use it using Panel package

**2- Chatbot_Gradio_OpenAi.ipynb :** 

Create a simple chatbot with openai API and then create a menu to use it using Gradio package

**3- SQL_Generator_OpenAi.ipynb:**

Creating a chatbot using openai api and creating a menu using Gradio. This chatbot receives a database and answers only the sql command related to the question.

**4- BBCNews_Chromadb_Liama:**

BBC News dataset is used. Here, we first save a part of the dataset using the Chroma DB database and extract the news related to the word "laptop" by embedding.
Then we use the llama model from the transformer library related to huggingface and also use it by transformers.
Then we connect the model to Chroma DB. Now the model answers our question using the resources provided to it.Important topics:
- Creating the Chroma DB database
- embedding with sentence_transformers
- Using the LLM 
- Using Transformers libery for working with LLM -->AutoTokenizer/AutoModelForCausalLM/pipeline

**5.SemanticCache-Faiss&ChromaDB**

A semantic caching system aims to identify similar or identical user requests. When a matching request is found, the system retrieves the corresponding information from the cache, reducing the need to fetch it from the original source.I place the cache system between the user and the vector database, not between the user and the large language model.Important topics:
-  hugging face --> Gemma-2b-it model 
-  Database on ChromaDB & SemanticCache on Faiss
-  SemanticCache(RAG) --> def (init, retrieve ,store) & class (semantic_cache)
-  SemanticCache(RAG) --> threshold Semantic distance

**6_RAG_langchain**

In this code, we try to use the langchain library with the approach of using RAG.Important topics:
- using langchain --> TextSplitter & embeddings & HuggingFacePipeline & Chroma & RetrievalQA
- ushng langchain  LCEL Architecture
- T5 & dolly-v2-3b models

**7_LLAMA2_Moderation**

In order to give a filtered answer to the user (for example, a rude question), we use this Moderation System technique with and longchain. Here we use one model to respond to users and another model to check and change inappropriate answers. Finally, we connect the two using longchain.Important topics:
- Model: Llama-2-7b-chat-hf / meta-llama/Meta-Llama-3.1-8B-Instruct
- Create a Moderation System using LangChain




  
ـ
