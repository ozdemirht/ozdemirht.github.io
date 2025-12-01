---
layout: archive
title: "Portfolio"
permalink: /portfolio/
author_profile: true 
excerpt: "Tim Ozdemir"
header:
  overlay_image: Data-Science-BG.jpg  # teaser: photo-nyc-1.jpg
  caption: "Data Engineering and Science"
---

{% include base_path %}

Articles in [Medium.com](https://ozdemirtim.medium.com/) by [Tim Ozdemir](https://www.linkedin.com/in/hasantimucinozdemir)
------
1. [AI Farming Buddy in Lesotho](https://github.com/ozdemirht/generative-ai/blob/main/Kaggle-Google-GenAI-2025/kaggle-ai-google-capstone.ipynb) capstone project for [5-Day AI Agents Intensive Course with Google](https://www.kaggle.com/learn-guide/5-day-agents) (2025) (Google ADK, Multi-Agent, MCP Servers, Tools, LLM Agents, Workflow: Coordinator, Weather, Farming, External API, DuckDB)
   1. ![Capstone Architecture Diagram](https://github.com/ozdemirht/generative-ai/blob/main/Kaggle-Google-GenAI-2025/docs/Capstone-Architecture-Diagram.png) , use [Capstone Architecture Diagram](https://github.com/ozdemirht/generative-ai/blob/main/Kaggle-Google-GenAI-2025/docs/Capstone-Architecture-Diagram.png)
   1. [Kaggle Notebook](https://www.kaggle.com/code/ozdemirht/kaggle-ai-google-capstone)
   1. [Writeup on AI Farming Buddy in Lesotho](https://www.kaggle.com/competitions/agents-intensive-capstone-project/writeups/ai-farming-buddy-in-lesotho)
1. [GenAI-Driven SDLC : Generate React UI Code](https://ozdemirtim.medium.com/genai-driven-sdlc-generate-react-ui-code-1746feb8d836) (2025) 
1. [GenAI-Driven SDLC](https://ozdemirtim.medium.com/genai-driven-sdlc-d7b02c673bb0) (2025)
1. [System Design: Food Delivery System](https://medium.com/@ozdemirtim/system-design-food-delivery-system-217356c1988d) (2025)
1. [Algorithm Interview by Example: Process](https://medium.com/@ozdemirtim/algorithm-interview-by-example-process-d12a70202c9f) (2020)
1. [Algorithm Interview by Example: Random Selection](https://medium.com/@ozdemirtim/algorithm-interview-by-example-random-selection-42bf4aaad9e2) (2020)

**Drafts**
1. [System Design: Food Delivery System, Proximity Search](https://medium.com/@ozdemirtim/system-design-food-delivery-system-a08364d680cd) (2025)
  - [Location Update to Redis](https://github.com/ozdemirht/py_redis_1) (Redis, multi-thread motion simulation of delivery agents, Python)
  - [NNQ: Uber H3 Spatial Index Jupyter Notebook](https://github.com/ozdemirht/py_redis_1/blob/master/docs/Test-H3.ipynb) (Uber H3, Folium, Python)
  - [NNQ: R-Tree vs H3 Index Jupyter Notebook](https://github.com/ozdemirht/py_redis_1/blob/master/docs/Test-DuckDB.ipynb) (DuckDB, R-Tree, Uber H3, Pandas, Folium, Python, SQL,...)
  - [Note: Distance calculation between spatial points (locations)](https://github.com/ozdemirht/py_redis_1/blob/master/docs/Note-SpatialDistance.ipynb) (DuckDB,PostGIS, SQL, Python)
  - [Note: ElasticSearch for Nearest Neighbour Query / Proximity Search](https://github.com/ozdemirht/py_redis_1/blob/master/docs/Note-ESearch.ipynb) (Elasticsearch, NNQ, Python)
  - [Note: Redis for Proximity Search](https://github.com/ozdemirht/py_redis_1/blob/master/docs/Note-Redis.ipynb) (Redis, Lua Scripting, NNQ, Python)
  - [Note: PostgreSQL and PostGIS for Nearest Neighbour Query / Proximity Search](https://github.com/ozdemirht/py_redis_1/blob/master/docs/Note-Postgresql-Spatial.ipynb) (Postgresql, PostGIS, psycopg2, NNQ, Python)
1. [Chat with your book (LLM with RAG)](https://github.com/ozdemirht/generative-ai/tree/main/RAG0) (streamlit, LangChain, OpenAI) (2025)
  - [Calculate The Number Of Tokens](https://github.com/ozdemirht/generative-ai/blob/main/RAG0/src/Calculate-Number-of-Tokens.ipynb) (tiktoken)
  - [Vector stores with FAISS, indexing and search visualization](https://github.com/ozdemirht/generative-ai/blob/main/RAG0/src/Retrieval_FAISS.ipynb) (FAISS, Dimension reduction(t-SNE, PCA), 2D/3D Visualization (Matplotlib, Plotly), LangChain, Hugging Face, Local LLM)
  - [Note: Elasticsearch for Semantic Search](https://github.com/ozdemirht/py_redis_1/blob/master/docs/Note-ESearch-Semantic.ipynb) (Elasticsearch, DSL, Semantic search, dense vectors, Text Embedding, Sentence-Transformers, Hugging Face (all-MiniLM-L6-v2,embeddinggemma-300m), Seaborn, Python) 
1. Open API: Adding summary of context history (Prompts for role: user and assistant) (2025)
1. Open API: Classification (utilize prompts of user-assitant for sample-label) (2025)
1. Open API: F(dietary restrictions, cuisine, available ingirendients) => Recipe (2025)
1. Open API: Recipes enhanced with Model Context Protocol (MCP) to pull in external trusted data (2025)
1. [Java Streaming API Example](https://github.com/ozdemirht/jstream_e2)  (2025)
   - [Spring Boot sample application](https://github.com/ozdemirht/ejava/tree/main/projects/sb/demo2) (Java 23, Maven, H2 Database, Spring Boot, JUnit 5, ) (2025)
   - [Concurrency:Executors and ExecutorService](https://github.com/ozdemirht/java/blob/main/projects/practice/jpractice/src/executors/Readme.md#scheduledexecutorservice-with-periodic-task-execution)
1. [Algorithm Interview by Example: Reduction](https://medium.com/@ozdemirtim/algorithm-interview-by-example-reduction-1773271bd9f2) (2025)
1. [Prompt Engineering practices with Claude](https://github.com/ozdemirht/py_claude_prompt_eng) (2025) 
  - [Conversation with Claude Samples Jupyter Notebook](https://github.com/ozdemirht/py_claude_prompt_eng/blob/master/src/Claude_Conversation.ipynb) (Claude API, Prompt: Context, System Prompt, Temperature; Python)
  - [Prompt Optimization](https://github.com/ozdemirht/py_claude_prompt_eng)
  
{% for post in site.portfolio %}
  {% include archive-single.html %}
{% endfor %} 
