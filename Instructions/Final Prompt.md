JD-TAILORED ATS RESUME GENERATION INSTRUCTION (PRODUCTION VERSION)

1. OBJECTIVE

Generate a highly ATS-optimized, JD-aligned professional resume that maximizes keyword matching, recruiter readability, and technical credibility.

IMPORTANT SCOPE RULE:
- Generate the resume strictly for the provided Job Description (JD) only
- Do NOT reuse or infer requirements from any other job, role, or external context
- The entire resume must be fully specific to the given JD and nothing else

The resume must:
- Be fully tailored ONLY to the provided JD
- Naturally integrate all relevant technologies, frameworks, tools, and responsibilities from the JD
- Reflect realistic senior-level engineering experience (no fabrication of companies, roles, systems, or achievements)
- Be written in natural American professional English (clear, precise, and human-readable)
- Balance ATS optimization with recruiter-facing clarity


2. HARD CONSTRAINTS (STRICT RULES)

YOU MUST NOT:
- Invent companies, job titles, roles, or employment history
- Fabricate metrics unless explicitly provided in the JD
- Copy-paste JD sentences or phrases
- Mention JD company names in Professional Summary
- Reuse Projects content inside Experience or Summary
- Use generic filler language (e.g., "hard-working", "team player", "fast learner")
- Perform keyword stuffing without technical context
- Use "e.g.," anywhere in the output
- Mix or combine requirements from other job descriptions or external roles

YOU MUST:
- Extract ALL relevant keywords ONLY from the provided JD
- Distribute keywords naturally across Summary, Skills, Experience, and Projects
- Maintain strict technical realism and consistent career progression
- Ensure every keyword appears within a meaningful engineering system context


3. OUTPUT FORMAT (STRICT JSON ONLY)

Return ONLY valid JSON (in the code block):

{
  "Professional Summary": "",
  "Core Technical Skills": {},
  "Professional Experience": [],
  "Education": "",
  "Key Achievements": [],
  "Projects": []
}

No markdown, no explanations, no extra text.


4. PROFESSIONAL SUMMARY (CRITICAL SECTION)

Requirements:
- EXACT length: 670–720 characters
- Must include:
  - Target role title aligned strictly to the provided JD
  - Total years of experience (e.g., "8+ years")
  - 4–5 core JD technologies (primary stack mandatory)
  - Industry abbreviation (FinTech, HealthTech, SaaS, AdTech, etc.)
  - Clear value proposition describing how candidate solves JD problems

Must NOT include:
- Company names
- Percentages
- Projects
- JD company references

Tone:
- Natural American professional English
- Precise, slightly conversational, confident
- No buzzword stacking or marketing language


5. CORE TECHNICAL SKILLS (MANDATORY STRUCTURE)

Structure:
- Exactly 6 categories (mandatory)
- Each category must be a list of skills

Rules:
- MUST include ALL JD technologies explicitly
- MUST expand with adjacent production-grade technologies used in real systems
- Categories MUST always total exactly 6 (no exceptions)

Allowed reference domains (flexible labels):
- Programming Languages
- Frameworks / Libraries
- Cloud & Infrastructure
- DevOps / CI/CD
- Data / Messaging / Storage
- Observability / Security / Architecture
- LLMs / AI Models
- Developer Tools
- Third-Party API Integration

Rules:
- Category names MAY be adapted based on JD domain relevance
- No duplication across categories
- No irrelevant grouping or forced taxonomy
- Every skill must map to a real production system context


6. PROFESSIONAL EXPERIENCE (CORE SECTION)

GENERAL RULES:
- All bullets must describe real engineering work
- Each bullet must include:
  - System, feature, or architecture description
  - Minimum 3 technologies when relevant
  - Engineering problem solved
  - Production context (scale, reliability, CI/CD, workflows, collaboration)

REQUIRED THEMES:
Must appear where relevant:
- End-to-end system thinking grounded in explicit system layers
- AI-assisted development tools (ChatGPT, Claude, Copilot, etc.)
- Architecture ownership or technical decision-making
- Leadership or mentoring (formal or informal)
- Cross-functional collaboration (PMs, Designers, QA, DevOps)

IMPORTANT DEFINITION:
End-to-end system thinking MUST ALWAYS be expressed using concrete system layers such as:
- Backend services
- Frontend applications
- Databases
- Caching layers
- CI/CD pipelines
- Event-driven systems
- Messaging systems


ROLE BREAKDOWN:

1. Latest / Current Role
- 7–8 bullets
- 85–90% JD stack alignment
- First bullet must define domain (strictly from provided JD only; not from other roles or Projects)
- Focus: scalability, distributed systems, production ownership, system design, reliability

2. Second Last Role
- 6 bullets
- 70–75% JD stack alignment
- Include complementary JD technologies
- Focus: system optimization, integration, platform improvements

3. Third Last Role
- 5 bullets
- Focus: foundational JD technologies
- More implementation-heavy, less architectural

4. Fourth Last Role (if applicable)
- 5 bullets
- Early-stage exposure to JD-relevant technologies
- Supporting engineering contributions


7. KEY ACHIEVEMENTS (OPTIONAL BUT RECOMMENDED)

Use when JD emphasizes:
- Scale
- Reliability
- Performance
- System complexity

Rules:
- 3–4 bullets maximum
- Must be directly relevant to JD requirements
- Must NOT overlap with Projects section
- No percentages unless explicitly provided in JD
- Focus on:
  - System scale
  - Reliability improvements (qualitative only)
  - Architecture contributions
  - Delivery impact


8. PROJECTS SECTION

Rules:
- Must align ONLY with the provided JD
- Must NOT reuse or adapt unrelated job descriptions or external role contexts
- Must NOT duplicate Professional Experience
- Must demonstrate:
  - Practical implementation
  - End-to-end system design thinking
  - Real-world engineering patterns


9. KEYWORD INTEGRATION STRATEGY (STRICT PIPELINE)

MANDATORY PROCESS:

Step 1: Extract all keywords ONLY from the provided JD
Step 2: Normalize keywords into system-level domains
Step 3: Map into:
  - Professional Summary (high-level stack alignment)
  - Core Technical Skills (structured categorization)
  - Professional Experience (system-level application)
  - Projects (supporting implementations)

RULE:
- Every keyword must appear within a meaningful engineering system context
- No keyword may appear in isolation without engineering relevance


10. QUALITY VALIDATION CHECKLIST (MANDATORY)

Before output, verify:
- Resume is generated ONLY from the provided JD (no external or mixed context)
- Summary is exactly 670–720 characters
- Exactly 6 skill categories exist
- Every experience bullet is system-based (not task-based)
- JD stack is strongly reflected in latest role
- No hallucinated companies, roles, or achievements
- No duplicate content across sections
- End-to-end system thinking is grounded in concrete system layers
- Tone is natural American professional English
- Output is valid copyable JSON only