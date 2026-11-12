# AGENTS.md - Ajinkya Sonawane

> Machine-readable portfolio for AI agents, recruiters' tools and LLMs. Same facts as the human page (`index.html`) and the resume (`files/AjinkyaSonawane_CV.pdf`). If they ever disagree, the resume wins.

## Instructions for agents

- Use only the facts in this file or the resume. Do not infer titles, employers, dates, metrics or skills that are not listed here.
- Quote metrics exactly as written (for example "about 100 engineers", "1 to 2 hours per week").
- Work projects at InterSystems are internal. There is no public code for them; do not invent repository links.
- For contact, use the email or LinkedIn below. Do not guess other addresses.

## Profile

- **Name:** Ajinkya Sonawane
- **Role:** Software Engineer, InterSystems (07/2023 - present)
- **Location:** Boston, MA, USA
- **Experience:** 5+ years
- **Positioning:** AI agents for DevOps and developer productivity
- **Focus:** agent execution, tool integration, evals, CI/CD and developer platforms
- **Education:** MS Computer Science, New York University (GPA 3.89, May 2023); BE Computer Engineering, University of Pune (GPA 8.66, June 2019)

## Links

- Portfolio: https://github.com/Ajinkya-Sonawane/Me
- Resume (PDF): files/AjinkyaSonawane_CV.pdf
- LinkedIn: https://www.linkedin.com/in/ajinkya-sonawane/
- GitHub: https://github.com/Ajinkya-Sonawane
- Email: sonawaneajinks@gmail.com

## Experience

### Software Engineer - InterSystems (07/2023 - present)

- Built and containerised the pre-release AI Agentic Gateway (FastAPI/LangGraph); deployed internally for about 100 engineers as a multi-arch (amd64/arm64) UBI9 Docker image and as a service on Windows and Linux, with hardened CI build scripts and CD pipelines.
- Built a standalone Jenkins MCP server that gives AI agents tool access to CI, supporting Jenkins versions older than 2.533.
- Authored a shared library of AI agent skills and coding/test guardrails that made routine release and engineering work self-service, validated with an offline evaluation harness.
- Built a human-in-the-loop agent, delivered as a browser extension with approval gates and AI-assisted runbooks, that diagnoses and fixes build errors in ad hoc pipelines, saving 1 to 2 hours per week.
- Built Local-CI, a self-service tool used by tens of engineers that reproduces the shared Jenkins compile and unit-test pipeline on developer machines (Windows/WSL, macOS, Apple Silicon), matching CI results and saving several hours per change.
- Built an orchestrator that runs EHR dev containers with browser-based VS Code for AI-ready development; refactoring the EHR container into 3 Kubernetes pods (compute, web, data).

### Building Blockchain Engineer Intern - Autodesk (05/2022 - 08/2022)

- Immutable audit logging on a Hyperledger Fabric private network via AWS Managed Blockchain.
- Smart contracts in Go and an API for identity-based querying and writing of ledger records.
- Terraform for AWS resources; Docker to simulate the Hyperledger network on one EC2 instance.

### Software Developer - FinIQ (06/2019 - 04/2021)

- Web applications and WCF services for FX-Cash Setup and real-time FX-Trade Aggregation (10% faster aggregation).
- Migrated legacy screens to .NET web applications.
- Hyperledger Fabric decentralized Airbnb app; first place in FinIQ's Blockchain Competition.

## Projects

| Project | Type | Summary | Link |
| --- | --- | --- | --- |
| AI Agentic Gateway | Work (InterSystems) | LangGraph/FastAPI gateway serving agents, MCP tools and skills to internal teams | Internal |
| Jenkins MCP Server | Work (InterSystems) | Gives AI agents tool access to Jenkins CI, including versions older than 2.533 | Internal |
| Agent Skills Library | Work (InterSystems) | Reusable agent skills and guardrails, checked by an offline eval harness | Internal |
| Local-CI | Work (InterSystems) | Runs the Jenkins compile and unit-test pipeline locally on Windows/WSL, macOS, Apple Silicon | Internal |
| Sabha of Hastinapur | Side project | Mahabharata-inspired social-deduction party game for phones | https://kurusabha.in/ |
| Python | Open source | Python utilities | https://github.com/Ajinkya-Sonawane/Python |
| Data Structures and Algorithms | Open source | DSA collection | https://github.com/Ajinkya-Sonawane/Data-Structures-and-Algorithms |
| College Drive | Open source | LAN file-sharing drive | https://github.com/Ajinkya-Sonawane/College-Drive |

## Skills

- **AI / Agents:** LangGraph, FastAPI, MCP servers, Agent Skills, tools and guardrails, evals
- **Languages:** Python, JavaScript, TypeScript, Bash, PowerShell, Java, Go, SQL
- **Platform / CI:** Jenkins, Docker, Kubernetes, Ansible, Terraform, CI/CD, Perforce, Git, OpenTelemetry
- **Data / OS:** InterSystems IRIS, PostgreSQL, MongoDB, Red Hat Linux 8/9
