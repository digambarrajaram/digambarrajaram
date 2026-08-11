# Hi, I'm Digambar Rajaram 👋

**SRE & AI Platform Engineer** — I build at the intersection of cloud infrastructure and agentic AI systems.

2+ years in production at Protean eGov Technologies managing 1,500+ VMs, EKS clusters, and CI/CD pipelines for India's largest government platforms (NPS, PAN, TIN, eSign — 300M+ citizens). Now shipping LLM-powered, multi-agent systems on top of that infra foundation.

<p align="left">
  <a href="https://digambarrajaram.cloud"><img src="https://img.shields.io/badge/Portfolio-000000?style=flat&logo=vercel&logoColor=white"/></a>
  <a href="https://linkedin.com/in/digambarrajaram"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white"/></a>
  <a href="https://github.com/digambarrajaram"><img src="https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white"/></a>
  <a href="mailto:digambarrajaram2@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=flat&logo=gmail&logoColor=white"/></a>
</p>

---

## 🤖 What I'm Building Now

**Agentic AI & GenAI**
- Multi-agent systems with **LangGraph** + **AWS Bedrock** (supervisor + specialist agent patterns)
- Custom **MCP servers** (Python) for K8s and Terraform tooling
- **RAG pipelines**, vector databases, knowledge bases, and guardrails
- LLM observability with **LangSmith**; workflow automation with **N8N**

**Cloud & DevOps (Production)**
- Kubernetes on EKS — Terraform, Helm, IRSA/OIDC, GitOps with Argo CD + Kustomize
- CI/CD — Jenkins, GitHub Actions (OIDC), multi-environment pipelines
- Observability — ELK Stack, Prometheus, Grafana, ElastAlert2, CloudWatch
- IaC — Terraform across VMware vSphere and AWS

---

## 🚀 Featured Projects

| Project | What it does | Stack |
|---|---|---|
| [AWS Terraform Drift Reconciler](https://github.com/digambarrajaram/AWS-Terraform-Drift-Reconciler) | Automated drift-detection pipeline — LLM agent classifies Terraform plan drift vs. live AWS state, opens GitHub PRs with proposed fixes. Trivy security gate, cost estimation, rollback, multi-account support. | LangGraph · Bedrock (Nova Pro) · Terraform · Trivy · Supabase |
| [Kubernetes & Cloud Cost Copilot](https://github.com/digambarrajaram/k8s-cost-copilot) | Multi-agent system that diagnoses K8s incidents and reviews Terraform PRs for cost/security risk. Custom MCP servers for K8s and infra tooling. Eval harness + CI gating. | LangGraph · Bedrock · MCP · EKS · Terraform |
| [ShopAssist AI](https://aishoppingassistant-aofjpf74t-digambar-s-projects.vercel.app/) | Production AI shopping assistant with 5-layer guardrail stack, LangChain tool-calling on Bedrock, session persistence, and LangSmith tracing | LangChain · Bedrock · FastAPI · React · Supabase |
| [NutriBlood AI](https://nutriblood-ai-vercel-1-1yimalhb9-digambar-s-projects.vercel.app/) | Extracts biomarkers from blood report text/images via LLM and returns personalised Indian diet recommendations as structured JSON | Groq · FastAPI · Jinja2 |
| [MenuMind AI](https://menumind-ai-ylpc.onrender.com/) | Generates restaurant names, brand concepts, and curated menus via LangChain + Groq pipeline | LangChain · Groq · Streamlit |
| EKS GitOps Architecture | GitOps-ready EKS cluster: multi-AZ VPC, Argo CD, Kustomize overlays, IRSA/OIDC, EBS CSI, RBAC, Network Policies | Terraform · Argo CD · Kustomize · EKS |
| ELK Observability Platform | Production ELK stack on AWS EC2 with Logstash Grok pipelines, Kibana dashboards, ElastAlert2 (sub-5-min MTTD), X-Pack TLS + RBAC | ELK · Terraform · ElastAlert2 |

---

## 🛠️ Stack

```
Agentic AI     LangGraph · LangChain · LangSmith · MCP · N8N · Groq · Streamlit
Generative AI  AWS Bedrock (Claude, Nova) · RAG · Vector DBs · Knowledge Bases · Guardrails
DevOps         Jenkins · GitHub Actions · Terraform · Ansible · Helm · Argo CD · Kustomize
Containers     Docker · Kubernetes (EKS) · IRSA/OIDC · AWS Load Balancer Controller
AWS            Bedrock · EKS · EC2 · S3 · IAM · VPC · ALB · CloudWatch · Lambda · Route 53
Observability  ELK Stack · Prometheus · Grafana · ElastAlert2 · CloudWatch · LangSmith
```

---

📊 GitHub Stats
<p align="left"> <img height="165" src="https://github-readme-stats.vercel.app/api?username=digambarrajaram&show_icons=true&theme=default&hide_border=true&count_private=true&cache_seconds=1800"/> <img height="165" src="https://github-readme-stats-black-five-16.vercel.app/api/top-langs/?username=digambarrajaram&layout=compact&hide_border=true&cache_seconds=1800"/> </p> <!-- Fallback if the above doesn't render (Vercel free-tier rate limits are common): <p align="left"> <img src="https://img.shields.io/badge/Top_Language-Python-3776AB?style=flat&logo=python&logoColor=white"/> <img src="https://img.shields.io/badge/Top_Language-TypeScript-3178C6?style=flat&logo=typescript&logoColor=white"/> <img src="https://img.shields.io/github/followers/digambarrajaram?style=flat&label=Followers"/> </p> -->

---

## 📌 Engineering Principles

- **Problem-first, tool-second** — pick the right abstraction, not the familiar one
- **Operate what you build** — I've been on-call for platforms serving 300M+ users
- **Evals over vibes** — agent code gets a test harness, not just a demo
- **Automate the toil** — if you do it twice, script it; if you do it at scale, Terraform it

---

<p align="left"><i>Open to SRE / AI Platform Engineer roles — Pune, Bengaluru, Mumbai, Hyderabad, Delhi NCR, or remote.</i></p>
