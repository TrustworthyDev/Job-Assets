Your responsibility is to generate the resume tailored to the specific job descrition.
Make sure the resume is ATS-friendly and optimized for a high score.

# I will provide:
1. A Job Description (JD)
2. Personal Info: Name, Title, Address, Email, Phone, Linkedin
3. Work History Info (Role Title, Company Name & Location, Period)
4. Projects (Title/link and its description)

# What you have to do
1. Calculate the total years of work experience from university graduation date to the present. The total years should be mentioned in Summary section.
2. You should read the job description first, then identify the company's tech stack and industry. Those are most important things for creating the resume content, especially the summary and work experience sections.
3. Generate the resume-ready content (in JSON schema) including the following sections:
- Personal info: Name, Title, Email, Phone, Address, Linkedin, Other links (optional)
- Professional Summary: Will be descripted below
- Skills: Tech stack from the Job Description, relevant tools, libraries, frameworks, and supporting technologies that match the role
- Professional Expreience: Will be descripted below
- Education: Degree, University Name and Location, Education Period
- Projects: Title/Link and its description

# Professional Summary
* 650 - 720 Characters
* Include the total years of experience, calculated from the university granduation date to the present
* Include the main tech stack mentioned in the Job Description
* Include industry from only Job Description (Not others, especially Project I provide) with its Abbreviation, plus two or more related industries
* Do NOT include any Company Names, especially company names from the Job Description.

# Core Technical Skills
* Inlcude 6 ~ 8 Categories of following categories:
- Programming Languages: Python, TypeScript, SQL
- Engineering Practices: DDD, TDD, OOP, Clean Architecture, Microservices Architecture
- Backend: Django, Django REST Framework, FastAPI, REST APIs, gRPC, GraphQL, WebSocket, Third-Party API Integration
- Authentication & Security: JWT, OAuth 2.0, OIDC, Passwordless Magic Link, RBAC, Cloudflare WAF, Cloudflare Bot Management, Rate Limiting
- AI / GenAI: OpenAI APIs, GPT-4, GPT-4o, LLMs, RAG, PyTorch, Streaming STT, Neural Machine Translation, Azure Neural TTS
- Frontend: React, Next.js, TypeScript, SSR, SSG, UI/UX, SEO, WCAG 2.2, Core Web Vitals: LCP, CLS, INP, FCP, TTFB
- Database: PostgreSQL, RDBMS, Query Optimization, Indexing, Partitioning
- Caching & Async Processing: Redis, Celery, AWS ElastiCache
- Messaging: Kafka, AWS MSK
- Search Engine: Elasticsearch, AWS OpenSearch
- Cloud & Hosting: AWS (EKS, ECR, EC2, RDS, S3, CloudFront, Route 53, IAM), Secrets Manager, CloudWatch
- Containerization: Docker, Kubernetes, AWS EKS, AWS ECR
- CI/CD: GitHub Actions, Docker-based CI/CD, Kubernetes Deployment Pipelines
- Unit Test: PyTest, Jest, Prettier
- IDE & Collaboration: Cursor, PyCharm, Git, Pull Requests, Code Review, Agile/Scrum
* Point all skills (based on Job Description) and its relevant skills

# Professional Experience