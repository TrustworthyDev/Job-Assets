Alari Ilves
@AI/ML

Proxy:      @res.proxy-seller.com:10000

### Info
Link: 		
DOB:        06/04/1990
Address: 	Rakvere tn 24, 20305 Narva, Estonia  (Ida-Viru County)
Email: 		alailves90@outlook.com
LinkedIn: 	https://www.linkedin.com/in/alari-ilves-63l8283b8/
Real One:   https://www.linkedin.com/in/alari-ilves-ai-engineer/
Phone:      +372 5576 5846
Time Zone:  EET

Password: 	P@ssw0rd!@#$%
Recovery: 	mariuszkrol831@gmail.com
Real:       https://www.linkedin.com/in/alari-ilves-6318283b8/
GitHub: 	
Resume:		https://docs.google.com/document/d/1cYFFH4dX-AXwziuRHlF6tT9EkJ0m5yd2KZMyRuNzT7w/edit?usp=sharing
Cover:      



### Education
Bachelor's Degree in Computer Science
University of Tartu Narva College | Narva, Estonia
Sep 2010 - Jun 2013

### Work History
# Senior AI/ML Software Engineer	
Yalantis | Warszawa, Poland
Nov 2021 – May 2026
• Led the backend and ML architecture for a voice-driven concierge platform used by hotel operators, handling real guest requests (booking updates, service orders, FAQs) cross multiple regions; contributed to automation that enabled ~75% of guest interactions to be handled without manual intervention. 
• Built and continuously improved multilingual NLP pipelines using Python, PyTorch, Hugging Face, and spaCy, tuning intent classification and entity extraction against real production logs rather than static datasets. 
• Introduced LLM-based response generation (OpenAI API) in a controlled way—kept business logic deterministic and used LLMs only where they added value, with guardrails and fallback flows to prevent hallucinations in customer-facing responses. 
• Designed a hybrid retrieval layer (Elasticsearch + vector search via FAISS/Pinecone) to serve hotel policies and guest context; spent significant effort on ranking quality, cache strategy, and keeping latency stable under load. 
• Built a distributed microservices setup using FastAPI and gRPC, with Celery, Redis, and Kafka for async workflows (speech processing, enrichment, integrations); tuned queues and backpressure to handle traffic spikes without cascading failures. 
• Developed data pipelines (Airflow, Spark, PostgreSQL) to process booking logs and interaction data into training datasets; worked closely with real data issues (missing fields, noisy inputs, schema drift). 
• Owned parts of the AWS deployment (EC2, S3, Lambda, RDS, SageMaker) using Docker/Kubernetes + Terraform, with emphasis on safe rollouts, observability, and rollback rather than over-engineering infra. 
• Integrated with external hotel systems (PMS/CRM) via REST, GraphQL, and WebSockets, handling unreliable APIs, rate limits, and inconsistent contracts. 
• Built monitoring and dashboards (Prometheus, Grafana, React) to track latency, error rates, and system behavior; these insights helped reduce operational overhead and contributed to ~40% reduction in manual workflows and support costs. 


# Experienced AI/ML Software Engineer 
Eremenko & Polomani | Tallinn, Estonia
May 2018 – Oct 2021
• Built a system to process incoming booking emails and extract structured data (dates, locations, preferences), reducing manual parsing work for operations teams. 
• Implemented NLP pipelines with spaCy, NLTK, and Transformers, focusing on robustness rather than perfect accuracy due to messy, real-world email formats. 
• Trained and evaluated models using Scikit-learn, XGBoost, and LightGBM for tasks like classification and ranking; kept models simple and explainable since outputs affected operational decisions. 
• Developed backend services with FastAPI, using Celery + RabbitMQ + Redis to handle asynchronous email processing and retries. 
• Built preprocessing pipelines with Pandas and Airflow, cleaning HTML-heavy email data and converting it into usable training datasets. 
• Deployed workloads on Azure (AKS, Azure ML, Functions); spent a good amount of time debugging deployment issues and handling scaling inconsistencies. 
• Created lightweight dashboards (mainly Power BI) so non-technical users could track processing results and error cases. 


# AI/ML Software Engineer
Terratra | Maardu, Estonia
Sep 2015 - Apr 2018
• Worked on an automated grading system for educational platforms, helping reduce manual grading load while keeping results interpretable for teachers. 
• Built evaluation pipelines combining rule-based logic with ML models (PyTorch, Transformers) to handle essays, structured answers, and simple code submissions. 
• Introduced retrieval-based approaches (early RAG-style patterns) to reference grading rubrics and course materials instead of relying purely on model outputs. 
• Designed backend workflows using Kafka, Redis, and PostgreSQL to process large batches of submissions asynchronously. 
• Deployed services on GCP (GKE, Cloud Run) using Docker/Kubernetes, focusing on cost control and predictable scaling during exam periods. 
• Integrated with LMS platforms via REST APIs and OAuth, dealing with version mismatches and inconsistent payloads. 


# AI Software Engineer
Golems GABB | Tallinn, Estonia
Jul 2013 – Aug 2015
• Contributed to an internal ML-driven platform for developer workflow automation, focusing on code understanding and task prediction from large codebases. 
• Built code analysis pipelines using AST parsing and structural feature extraction (dependencies, call graphs, file relationships) to generate ML-ready datasets. 
• Developed feature engineering workflows with Python, NumPy, and Pandas, transforming repository metadata into structured inputs for downstream models. 
• Implemented classification and ranking models (Scikit-learn) to recommend relevant files and implementation patterns based on historical commit data. 
• Applied early embedding techniques (TF-IDF, word2vec-style) to model code similarity and improve search and recommendation relevance. 
• Designed offline evaluation pipelines using historical data to validate model performance and reduce noise in predictions. 


### Cover Letter
Hi Hiring Team,

I came across your opening for a Senior AI/ML Engineer, and it immediately stood out — it sounds like the kind of work where AI isn’t just a feature, but a core part of the product.

Over the past 10+ years, I’ve been building end-to-end AI systems that move beyond prototypes into production — systems that handle real users, real scale, and real-world messiness. Most recently, I designed and delivered a voice-driven AI concierge platform for the hospitality industry, combining LLMs, RAG pipelines, and predictive models to automate guest interactions and service workflows at scale. The system processes thousands of concurrent interactions, integrates with multiple backend systems, and delivers real-time, context-aware responses.

A big part of my work has been making AI systems actually usable and reliable in production. That means building not just models, but the full ecosystem around them — data pipelines, retrieval layers, microservices, and cloud infrastructure. I’ve worked extensively with Python, PyTorch, Transformers, LangChain, and vector databases like Pinecone and FAISS, along with AWS, Azure, and GCP to deploy and scale systems globally.

What I enjoy most is working across the full stack of AI development — from shaping the problem and designing the architecture to optimizing performance and ensuring the system holds up under real-world conditions. I tend to gravitate toward problems where there’s complexity, ambiguity, and a need to balance speed with long-term scalability.

I’m particularly interested in roles where AI is treated as a product capability, not just an experiment — where the focus is on building systems that are intelligent, dependable, and genuinely useful.

If that aligns with what you're building, I’d be glad to connect and talk through how I could contribute.

Kind regards,
Alari Ilves
