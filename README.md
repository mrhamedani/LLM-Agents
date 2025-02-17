# How-to-apply-popular-LLMs

 Apply and Implement Strategies for Large Language Models


**1-Chatbot-Panel-OpenAI.ipynb:**

Create a simple chatbot with openai API and then create a menu to use it using Panel package

**2- Chatbot_Gradio_OpenAi.ipynb :** 

Create a simple chatbot with openai API and then create a menu to use it using Gradio package

**3- SQL_Generator_OpenAi.ipynb:**

Creating a chatbot using openai api and creating a menu using Gradio. This chatbot receives a database and answers only the sql command related to the question.

**4- BBCNews_Chromadb_Liama:**

BBC News dataset is used. Here, we first save a part of the dataset using the Chroma DB database and extract the news related to the word "laptop" by embedding.
Then we use the llama model from the transformer library related to huggingface and also use it by pipline.
Then we connect the model to Chroma DB. Now the model answers our question using the resources provided to it.Important topics:
- Using the pipeline
- Creating the Chroma DB database and connecting to the model
- Using the llama model
- Using ChromaDB --> embedding to find related items

**5.RAG-SemanticCache-Faiss&ChromaDB**
A semantic caching system aims to identify similar or identical user requests. When a matching request is found, the system retrieves the corresponding information from the cache, reducing the need to fetch it from the original source.I place the cache system between the user and the vector database, not between the user and the large language model.Important topics:
-  hugging face --> Gemma-2b-it model
-  RAG system Architecture 
-  Database on ChromaDB & SemanticCache on Faiss
-  SemanticCache --> init, retrieve ,store
-  SemanticCache --> thresold Semantic distance
ـ
