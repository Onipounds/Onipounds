Femi Adebiyi Onisile
Software engineer — Python| Backend| Cloud / DevOps| and Operational-Technology Software.
I build reliable, well-tested software where code meets physical systems: state estimation, sensor fusion, industrial monitoring, and the APIs and dashboards around them  and I deploy it to the cloud with infrastructure-as-code and CI/CD. MSc in Automation & Robotics; founder and lead engineer at Sentinel Robotics Group, building a cyber-physical integrity-monitoring platform for industrial control systems.
London, UK · open to software engineering roles (backend, cloud / DevOps, OT/industrial, ML/AI).
Selected work
A device-to-dashboard pipeline for industrial telemetry,estimate the state, read the machine, detect the fault, serve the data, visualise it live, and deploy it to the cloud:
Project	What it does
ekf-sensor-fusion	Extended Kalman Filter for nonlinear sensor fusion; cuts tracking error ~62% versus raw measurements.
s7-live-monitor	Reads live tags from a Siemens S7-1500 PLC over the S7 protocol, logs them, and dashboards them.
ics-anomaly-detector	Anomaly detection on a real industrial sensor benchmark (rolling z-score vs Isolation Forest).
telemetry-api	FastAPI + SQLAlchemy service to ingest and query sensor telemetry. Containerised with Docker, deployed to AWS ECS Fargate via Terraform, with a CI/CD pipeline (GitHub Actions) that builds, pushes to ECR, and validates infrastructure on every push.
telemetry-dashboard	Live FastAPI + Chart.js dashboard — ▶ live demo
And, aimed at AI / LLM work:
Project	What it does
rag-doc-qa	Retrieval-augmented document Q&A — TF-IDF retrieval with grounded, cited answers (optional LLM generation).
agent-loop	A small AI agent harness — tool-calling loop, memory, and a two-layer self-verification step (grounding + re-computation) so the agent checks its own work instead of hallucinating. Offline-testable; exposes its tools as an MCP server.
Every repository has a test suite and continuous integration across Python 3.10–3.12.
Tech
Python · FastAPI · SQLAlchemy · SQL · Docker · AWS (ECS Fargate, ECR) · Terraform · CI/CD (GitHub Actions) · scikit-learn · NumPy · MATLAB / Simulink · Siemens S7 / PLCs · Anthropic Claude API · MCP · Git
Find me
LinkedIn — femi-onisile
