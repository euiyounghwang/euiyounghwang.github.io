# euiyounghwang.github.io

I have ten years of experience in working with a modern search platform (Elasticsearch) and in building data pipelines & rest api services around it as a search engineer/senior software engineer. 
Especially, I am an expert in the Search Engine with a bunch of api from elasticsearch and rest_api environment using python flask, fastapi, docker … because I handled the entire version of ES from 1.7 up to 7.9 V.

In particular, I remember developing the elasticsearch search system for 7 years in South Korea and having a success story interview at the elastic on seoul conference(https://www.youtube.com/watch?v=qu0IXwi3Fq0). At that time, I participated in the Google search engine replacement project as project leader and senior software engineer. 

The screenshots attached below are for the Success Story with Elasticsearch Interview, Elastic on Seoul Conference, 2018
when i worked as Senior Software Engineer & Search/Data Engineer at POSC ICT, South Korea 

- Handle with Elasticsearch 1.7.3 ~ 7.9.0 (Implement search service on entire version of Elaticsearch)
- 1'st Develop & Deploy the Elasticsearch with 24 Nodes (3 Masters. 2 clients, 19 Data Nodes) in South Korea
- Korean Analyzer called Nori developed from elastic after our requests and find analyzer bug such as Korean Arirang, Mecab)
- Design & Create Index about more than 4,000 index with settings & mappings and index template for the client requirements
- Proper query implementation with Query DSL on Elasticsearch Cluster
- Improve search relevance for client requirements with ranking weight
- Design & Develop a novel java library based on Apache Tika to extract full text from various of documents such as MS-OFFICE, HWP, PDF and Text Format 
 (Import java library into Python Environment for amounts of unstructured text indexing into ES cluster)

if you want to watch the video, please go to this url (https://www.youtube.com/watch?v=qu0IXwi3Fq0) after set subtitled to English
(I was in the middle of guys)

![Alt text](image-5.png)

Recently, I am personally implementing to rest-api endpoint as test project using python, flask/fast(https://github.com/euiyounghwang/python-fastapi-vector-search, https://github.com/euiyounghwang/python-flask-connexion-example-openapi3-master), and nestjs(https://github.com/euiyounghwang/nest-js-rest-api) based restapi. A search engine (elasticsearch) and Postgres were used. It is also implemented based on Docker, and is being built, executed, and tested. Also I am interested with similary search such as huggingface embedding, vectorized search using Faiss and so on. (https://github.com/euiyounghwang/semantic-search-elasticsearch-openai-langchain)

![Alt text](image.png)

![Alt text](image-1.png)

Recently, research has been conducted for search engine cluster monitoring and web application monitoring. In other words, we are testing to monitor search engines and restapi endpoints using prometheus and grafana.
Elasticsearch Prometheus Exporter is a builtin exporter from Elasticsearch to Prometheus. It collects all relevant metrics and makes them available to Prometheus via the Elasticsearch REST API. This is an open source project - Cluster status, Node Status such as JVM, Indices, Circuit Breaker : the feature to prevent OOM occurrence

![Alt text](image-2.png)
![Alt text](image-4.png)
![Alt text](image-3.png)