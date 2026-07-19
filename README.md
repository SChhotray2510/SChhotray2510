# Sourav Chhotray
## AI QA Engineer / Agentic AI Developer

👋 Hi, I build and break AI systems for a living. I turn complex healthcare workflows into robust, scalable, and agentic AI pipelines.

---

### Key Skills
- Agentic AI Development: LangChain, LangGraph, LlamaIndex, CrewAI, AutoGen, MCP
- AI Safety Testing: Guardrails AI
- MCP Integration: MCP Server, Claude MCP
- Prompt & LLM Testing: Promptfoo, DeepEval
- RAG Evaluation: RAGAS, LangSmith
- API Development: FastAPI, SQLAlchemy, Pydantic, Uvicorn, OpenAPI/Swagger
- API Testing: Python Requests, Postman, Playwright API
- Automation Framework: PyTest, Page Object Model, Data-Driven Framework, Hybrid Framework
- Backend Development: Python, FastAPI, SQLAlchemy, Microservices
- Build & Test Execution: Jenkins Pipeline, PyTest, Command-Line Execution
- CI/CD: Jenkins, GitHub Actions
- Cloud Platform: AWS, EC2, Bedrock, S3, RDS, CloudWatch
- Containerization: Docker, Docker Compose
- Data Handling: JSON, CSV, Excel, Pandas
- Database & Query Language: SQL, MySQL, PostgreSQL, SQLAlchemy, Vector Databases
- Development Tools: VS Code, PyCharm, GitHub Copilot, Postman
- Locator Validation: Playwright Inspector, Trace Viewer, Codegen
- Monitoring: LangSmith, Application Logs
- Programming & Scripting: Python, JavaScript, Unix Shell Scripting
- Test Reporting: Allure Report, PyTest HTML Report, Jenkins Test Reports
- UI Automation Testing: Playwright, Selenium WebDriver
- Version Control: Git, GitHub

### Technical Skills
- LLM & RAG Application Engineering: Prompt Engineering, Tool Calling, Function Calling, Structured Output, LLM Integration, Document Loading, Chunking, Embedding Generation, Vector Search, Retrieval, Response Generation
- Multi-Agent & Agentic AI Testing: Agent Orchestration, Agent Communication, Task Delegation, Memory and Workflow Management, Multi-Agent Workflow Testing, Tool-Calling Validation, Memory Testing, Context Validation, Agent Behaviour Testing
- MCP Development & Integration: MCP Server Development, MCP Tool Call Validation, MCP Context Injection Testing, MCP Client-Server Integration, Agent Integration
- LLM & RAG Evaluation: Hallucination Testing, Regression Testing, Response Quality Validation, Retrieval Accuracy, Context Relevance, Faithfulness, Answer Relevancy
- API & Backend Development: RESTful API Development, REST API Validation, API Schema Validation, Database Integration, Authentication, Exception Handling, Microservices, OpenAPI/Swagger
- AI Safety & Guardrails: Prompt Injection Testing, Toxicity Validation, Bias Testing, Sensitive Data Protection, Guardrails AI

### Profile Summary
Agentic AI Test Engineer and Developer with 3 Years of Expertise in LLM Testing, RAG Validation, Multi-Agent Workflow Testing, UI Automation and API Automation.

1. Seasoned AI QA Automation Engineer cum Agentic AI Developer bringing 3+ years of Healthcare domain experience in testing, automation, and AI application development.
2. Balanced professional profile — 70% quality engineering and 30% backend/Agentic AI development — strengthened by 1.5 years of practical development experience.
3. Comprehensive understanding of Healthcare systems and standards — EHR, EMR, FHIR, HL7, PHI, ePHI, HIPAA, DICOM, PACS — along with patient registration, appointments, clinical records, imaging, insurance, and data exchange workflows.
4. Ability to perform full-spectrum Agentic AI testing on Healthcare applications — chatbot validation, clinical RAG evaluation, retrieval checks, hallucination detection, PHI protection, prompt safety, tool-calling validation, agent memory testing, and multi-agent workflow validation — and capable of certifying AI quality across accuracy, groundedness, privacy, HIPAA compliance, and guardrail enforcement.
5. Strong framework engineering capability — scalable UI automation with Python, JavaScript, Playwright, Selenium, Pytest, Page Object Model, reusable utilities, data-driven testing, and Allure reporting.
6. Demonstrated ability to automate Healthcare business flows end to end — registration, login, appointments, consultations, EHR/EMR updates, clinical notes, prescriptions, lab reports, insurance verification, billing, and record access.
7. Thorough knowledge of Healthcare API testing — Playwright API, Python Requests, Postman, REST Assured, OpenAPI, JWT, schema validation, chaining, negative testing — with FHIR resource validation (Patient, Practitioner, Appointment, Encounter, Observation, Medication, Claim, DiagnosticReport, DocumentReference).
8. Good understanding of DICOM/PACS imaging validation — upload, retrieval, metadata, patient-study mapping, access control, and secure transmission of diagnostic images.
9. Advanced capability in Agentic AI testing (LLM validation, prompts, RAG, hallucination, tool-calling, agent memory, guardrails, multi-agent, AI regression) using Promptfoo, DeepEval, RAGAS, LangSmith, TruLens, Guardrails, and OpenTelemetry, with knowledge of Playwright MCP for AI-assisted automation.
10. Development capability in backend APIs — FastAPI, SQLAlchemy, Uvicorn, Pydantic, JWT, OpenAPI documentation, SQL, MySQL, and ChromaDB.
11. Strong knowledge of Agentic AI and RAG development — LangChain, LangGraph, LlamaIndex, CrewAI, MCP, Microsoft AutoGen, and AWS Bedrock.
12. Ability to engineer AI agents with custom tools, function calling, memory, conditional routing, retry mechanisms, and human-in-the-loop workflows, plus RAG pipelines with vector databases (ChromaDB) and embeddings.
13. Sound knowledge of cloud, CI/CD, containerization, observability, and performance testing — AWS EC2, S3, Lambda, Bedrock, GitHub, Docker, Jenkins, OpenTelemetry, and k6.

---

### Selected Experience

#### EMS Dispatch Decision-Support & Hospital Routing Agent (Ambulance Management System)
- Client: Confidential — EU Regional Emergency Medical Services (Germany)
- Chatbot: MedicMate
- Tools: LangGraph, MCP for CAD/fleet-telemetry APIs, RAG over dispatch protocols & hospital capability directory, pytest, Grafana
- Summary: Agent supports dispatchers — suggesting nearest appropriate unit using live fleet telemetry via MCP, recommending destination hospitals from RAG over the capability directory (stroke/STEMI/trauma centers), and auto-drafting pre-arrival notifications to receiving EDs. Dispatchers confirm every recommendation; the agent never dispatches autonomously.
- Responsibilities:
    - Developed unit-suggestion and destination-recommendation agents (confirm-gated).
    - Built MCP tools for CAD status, GPS telemetry, and notification drafts.
    - Validated recommendations against dispatcher-adjudicated historical calls.
    - Tested degraded-GPS and telemetry-loss fallback behavior.
    - Ran latency SLA testing for time-critical recommendation paths.

#### Care-Gap Outreach & Patient Engagement Automation Platform (Healthcare CRM)
- Client: Confidential — US Multi-Specialty Provider Network
- Chatbot: ReachRight
- Tools: LangChain, MCP for CRM/campaign APIs, RAG over approved outreach content & care-gap definitions, Selenium, Langfuse
- Summary: Agent runs care-gap outreach — identifying patients due for screenings via MCP CRM queries, personalizing messages strictly from approved content libraries via RAG, handling scheduling replies conversationally, and logging dispositions back to CRM. Consent and communication-preference rules are enforced on every send. Screening completion up 28%.
- Responsibilities:
    - Built outreach and reply-handling agents with approved-content-only generation.
    - Implemented CRM MCP tools for cohort query, send, and disposition logging.
    - QA'd consent/opt-out enforcement with exhaustive preference test matrices.
    - Validated care-gap cohort logic against quality-team SQL baselines.
    - Automated multichannel (SMS/email/portal) conversational regression.

#### ONC Certification / FHIR g(10) Conformance Testing (Interoperability)
- Client: Confidential — US EHR Vendor (certification program)
- Environment: FHIR R4 US Core, Inferno test kit, SMART launch, Postman
- Summary: Prepared and executed conformance testing for ONC g(10) certification — US Core resource support, SMART App Launch (standalone and EHR launch), bulk data export, and token lifecycle requirements — using the Inferno test suite and internal API regression packs.
- Responsibilities:
    - Ran Inferno sequences and triaged failures to development with root cause.
    - Built supplemental REST Assured packs for US Core search parameters.
    - Tested SMART launch contexts, scopes, and refresh-token behavior.
    - Validated bulk-export (Flat FHIR) job lifecycle and NDJSON outputs.
    - Maintained traceability from certification criteria to test evidence.

---

### Education
- Institute of Technical Education and Research – Bhubaneshwar: B.Tech
- Loyola School – Bhubaneshwar: ICSE

---
🔗 [souravchhotray40@gmail.com] | [+91-9937891011]
