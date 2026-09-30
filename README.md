Hi, I'm Nidhish 👋
I'm a BPM and workflow automation developer. I've noticed the same thing everywhere I've worked: the work rarely gets stuck in the code. It gets stuck in the process around it. Approvals bouncing between teams, forms waiting in someone's inbox, the same data typed into three places. That's the part I like fixing.

🔹 4 years at Saint-Gobain building workflow apps on Bonita BPM: BPMN 2.0 processes, DMN decision tables, and the Java / Spring Boot and REST / SOAP services behind them (~20% less manual effort) 🔹 MSc Advanced Computer Science, University of Sussex (Merit) 🔹 Now advising Shiftelio on its workflows: mapping how things really run and finding the bottlenecks 📍 Brighton, UK · open to relocation

🛠️ What I build here
I learn best by doing, so these are the projects I built to understand something properly. Each one has a README that explains the why, not just the how.

Project	What it is	Stack
⚙️ durable-orchestrator	A small workflow engine that survives being killed mid-run. It saves progress to PostgreSQL after every step and picks the job back up from the exact step, without redoing finished work. The example process is a loan approval with a human approval wait state.	Java 21 · PostgreSQL · Gradle
📊 bpm-process-intelligence-sla-analytics	Treats 141k IT-incident events as a process-mining log to answer why tickets miss SLA. Finding: every handoff costs you, and 0 → 5+ reassignments drops SLA attainment from 78% to 14%.	Python · SQL star schema (DuckDB) · Power BI · DAX
🛡️ ai-grc-copilot	Checks company policies against NIST AI RMF and SOC 2, flags gaps and cites the exact passage. Rules engine for the black-and-white checks, a local LLM + retrieval for the judgment calls. 100% needs-review recall, 0 false "you're fine" answers on the test set.	Python · local LLM (Ollama) · RAG
✂️ TokenOptimizationTool	Makes LLM prompts leaner and shows a receipt of what you saved. Pure, testable text rules with 90+ tests. Live demo	Python · tiktoken · pytest · Streamlit
🧰 Toolbox
Process & workflow: BPMN 2.0 · DMN · Bonita BPM · Power Automate · Power Apps Backend: Java · Spring Boot · REST / SOAP APIs · OAuth2 / SSO Data: SQL · PostgreSQL · SQL Server · Python Delivery: Git · GitLab CI/CD · Docker · Linux AI-assisted dev: Claude Code is my everyday pair programmer

💬 Say hi
I'm looking for BPM, workflow automation, low-code or Java backend roles. If you're working on process automation, I'd love to hear what you're building.

LinkedIn · nadenidhish22@gmail.com
