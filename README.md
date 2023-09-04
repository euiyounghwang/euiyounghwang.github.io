# euiyounghwang.github.io

#### Euiyoung Hwang (marieuig@gmail.com) / Linkedin(https://www.linkedin.com/in/euiyoung-hwang/) : Search, Data & AI Software Engineer

- __<i>Tools (Pycharm, Eclipse, Postman, VS Code, ELK, Jupyter, Databricks, Datadog, Grafana, Bonsai for Elasticsearch Cluster, Jira/Confluence)</i>__
- __<i>Environment (Vagrant, Conda, Docker&Docker-Compose, Poetry, Github, CircleCI, AWS)</i>__
- Programming (Python, Java, Flask, Flask/Rest-Flask:https://github.com/euiyounghwang/python-fastapi-vector-search, https://github.com/euiyounghwang/python-flask-connexion-example-openapi3-master, Elasticsearch API, Databricks notebook, Google colab for implementation/testing AI model)
- Research, Develop and Deploy from Elasticsearch v1.7.3 ~ v7.9.X (Design, Develop and Deploy an  Elasticsearch Cluster between WAS and Data Feed application with DB and Documentum server for 7 years)
- Interested with Elasticsearch v8 new features with Vectorized Search (https://github.com/euiyounghwang/semantic-search-elasticsearch-openai-langchain)
- Elasticsearch 1’st Deploy & Go Live Expert (Production : Elasticsearch Cluster with 24 Nodes, Log Cluster with 8 Nodes)  in South Korea
- Search (Elasticsearch, Google Search Appliance) with Cluster, Design Index for Search, Restful API, Analyzer and Data Migration)
- Big Data Analysis (Elasticsearch, Logstash, Beat, Redis, MongoDB, SQL)
- Machine Learning with Scikit-Learn, NumPy, Pandas, Doc2Vec, Wor2vec, FastText and Tensorflow (distilbert), Keras, Text-Mining and NLP(Natural Language Processing) with Python v 3.5 ~
- Restful API (Socket, HTTP WebService with JSON based on Rest-Flask, Spring Boot Controller, Swagger UI API)
- Research new Technology for AI & Big Data (Jupyter with Anaconda)
- Project Leader & AI Engineer to <i>AI POS-ComplAi Project with AI Model based on Supervised Machine Learning Model</i> (News: http://bit.ly/2Ojc7Ij, https://www.donga.com/news/Economy/article/all/20200204/99522285/1, It requires to translate in English) in South Korea

I have ten years of experience in working with a modern search platform (Elasticsearch) and in building data pipelines(e.g https://github.com/euiyounghwang/python-search) & rest api services around it as a search engineer/senior software engineer. 
<i>Especially, I am an expert in the Search Engine with a bunch of api from elasticsearch and rest_api environment using python flask, fastapi, docker … because I handled the entire version of ES from 1.7 up to 7.9 V.</i>

In particular, I remember developing the elasticsearch search system for 7 years in South Korea and having a success story interview at the elastic on seoul conference(https://www.youtube.com/watch?v=qu0IXwi3Fq0). At that time, I participated in the Google search engine replacement project as project leader and senior software engineer. 

The screenshots attached below are for __<i>the Success Story with Elasticsearch Interview, Elastic on Seoul Conference, 2018</i>__ (https://www.elastic.co/customers/posco)
when i worked as Senior Software Engineer & Search/Data Engineer at POSC ICT, South Korea 

- Handle with Elasticsearch 1.7.3 ~ 7.9.0 (Implement search service on entire version of Elaticsearch)
- 1'st Develop & Deploy the Elasticsearch with 24 Nodes (3 Masters. 2 clients, 19 Data Nodes) in South Korea - Monitoring with Spring Boot (https://github.com/euiyounghwang/Spring_Boot_Monitoring)
- Korean Analyzer called Nori developed from elastic after our requests and find analyzer bug such as Korean Arirang, Mecab)
- Design & Create Index about more than 4,000 index with settings & mappings and index template for the client requirements
- Proper query implementation with Query DSL on Elasticsearch Cluster (https://github.com/euiyounghwang/GitHub_Guide)
- Improve search relevance for client requirements with ranking weight
- Design & Develop a novel java library based on Apache Tika to extract full text from various of documents such as MS-OFFICE, HWP, PDF and Text Format (https://github.com/euiyounghwang/ES_Python_Project, https://github.com/euiyounghwang/DocumentsTextExtract)
 (Import java library into Python Environment for amounts of unstructured text indexing into ES cluster)

if you want to watch the video, please go to this url (https://www.youtube.com/watch?v=qu0IXwi3Fq0) after set subtitled to English
(I was in the middle of guys)

![Alt text](image-5.png)

Recently, I am personally implementing to rest-api endpoint as test project using python, flask/fastapi(https://github.com/euiyounghwang/python-fastapi-vector-search, https://github.com/euiyounghwang/python-flask-connexion-example-openapi3-master), and nestjs(https://github.com/euiyounghwang/nest-js-rest-api) based restapi. A search engine (elasticsearch) and Postgres were used. It is also implemented based on Docker, and is being built, executed, and tested. Also I am interested with similary search such as huggingface embedding, vectorized search using Faiss and so on. (https://github.com/euiyounghwang/semantic-search-elasticsearch-openai-langchain)

#### <i>Rest-API on OPEN API Specifiation(Swagger)</i>
```
components:
  schemas:
    ..
    Search:
      type: object
      properties:
        query_string:
          type: string
          description: Full text search
          default: "Cryptocurrency"
          nullable: true
        start_date:
          type: string
          format: date
          description: Start date
          default: "2021 01-01 00:00:00"
        size:
          type: integer
          description: The number of size
          default: 20
        sort_order:
          type: string
          enum:
            - DESC
            - ASC
        include_basic_aggs:
          type: boolean
          description: Flag to enable/disabled aggregations which can slow down queries
        pit_id:
          type: string
          format: date
          description: pit_id
          example: ""
        ids_filter:
           type: array
           items:
            type: string
           default: ["*"]
    ..
```
![Alt text](image.png)

#### <i>Docker in my local Environment</i>
![Alt text](image-1.png)

Recently, I have been researching & implementing for search engine cluster monitoring and web application monitoring. In other words, we are testing to monitor search engines and restapi endpoints using prometheus and grafana. Elasticsearch Prometheus Exporter is a builtin exporter from Elasticsearch to Prometheus. It collects all relevant metrics and makes them available to Prometheus via the Elasticsearch REST API. This is an open source project - Cluster status, Node Status such as JVM, Indices, Circuit Breaker : the feature to prevent OOM occurrence

#### <i>Prometheus (Build Docker on my local environment with Elasticsearch-Exporter Plugin)</i>
![Alt text](image-2.png)
#### <i>Elasticsearch Cluster monitoring</i>
![Alt text](image-4.png)
#### <i>Python Webservice monitoring</i>
![Alt text](image-3.png)