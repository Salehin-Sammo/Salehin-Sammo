<h1 align="center">Nazmus Salehin Sammo</h1>

<p align="center">
  <b>AI &amp; Cloud Engineer</b>&nbsp;·&nbsp;Multi-Agent AI Systems&nbsp;·&nbsp;Post-Quantum Cryptography<br/>
  <sub>Melbourne, Australia</sub>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/nsammo"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:nsalehin2002@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email"/></a>
</p>

---

I build production AI systems and the cloud underneath them — multi-agent orchestration on Azure AI Foundry, Copilot Studio agents wired into Microsoft Graph and Power Automate, privacy-preserving RAG over sensitive documents, and the Terraform, identity, and observability that keep it all standing.

Getting a model to work once is the easy 20%. The 80% that decides whether it survives is everything after: infrastructure that stays up, Azure spend that doesn't run away, and environments that rebuild from nothing. Good AI architecture is mostly good system architecture with the model placed at the right seam.

I red-team the agents I build before they ship — prompt injection, permission escalation, one agent leaking what another holds. Better I break it in testing than an attacker breaks it in production.

### 🔭 Currently

- **Master of Research (AI & Data Analytics)** @ Melbourne Institute of Technology — *Post-Quantum Cryptography migration for Australian payments infrastructure*
- **AI & Full-Stack Engineer** @ Endeavour Consultants — shipping production Azure / .NET platforms end-to-end

### 🧪 Research

**Post-Quantum Cryptography** — Benchmarking PQC migration for Australia's real-time payment rails (NPP, RITS/RTGS, SWIFT) against NIST FIPS&nbsp;203–206. A discrete-event Monte Carlo simulation over 80M+ transaction events (`liboqs`) finds **Falcon-512** and **ML-DSA-44** are the only NIST candidates that fit both the message-size and sub-2s settlement constraints, while **SPHINCS+** collapses under ISO&nbsp;20022 size limits. First paper published and covered by industry press; follow-on work formalises a cryptographic DoS amplification and the downgrade gap that opens during uneven migration.

**Quantum Machine Learning** — Grounded in a systematic review of 800+ papers. The honest finding at current hardware scale: classical methods keep pace. In *Parity-Augmented Kernels*, a classical model matches quantum kernel methods at **1,000–10,000× less compute**; *The Encoding Cliff* shows classical dequantization wins at every compute budget tested.

> Two clocks, one decade. Quantum probably won't beat classical ML soon — it almost certainly breaks classical cryptography this decade. The AI systems we deploy now are still running when that second clock runs out. That gap is where I work.

### 🚀 Selected Work

| Project | Stack |
|---|---|
| **Tilt** — cloud-native education platform | Azure · .NET 9 · Next.js · 11 Terraform modules · Azure AI Document Intelligence · Copilot Studio + Direct Line · Microsoft Graph |
| **CRM Platform** — replaced manual ops org-wide | ASP.NET Core · Next.js · PostgreSQL · JWT RBAC · AWS (ECS/RDS/S3) via Terraform · AWS Textract OCR + multi-country MRZ passport parsing |
| **Clinical summarisation** (Your Community Health) | On-prem BERT fine-tuning (50% → 80% accuracy) · RAG over EMR records · Flask microservice |
| **[BioMRC](https://github.com/Salehin-Sammo/BioMRC)** — medical QA research | BERT fine-tuning on CPGQA / SQuAD · Swinburne undergraduate research |

### 💻 Tech

**Languages**  
![C#](https://img.shields.io/badge/C%23-239120?style=flat-square&logo=csharp&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

**Cloud & AI**  
![Microsoft Azure](https://img.shields.io/badge/Microsoft_Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![Azure OpenAI](https://img.shields.io/badge/Azure_OpenAI-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![AI Foundry](https://img.shields.io/badge/AI_Foundry-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![Document Intelligence](https://img.shields.io/badge/Document_Intelligence-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![Copilot Studio](https://img.shields.io/badge/Copilot_Studio-0078D4?style=flat-square&logo=microsoft&logoColor=white)

**Frameworks**  
![.NET](https://img.shields.io/badge/.NET-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![ASP.NET Core](https://img.shields.io/badge/ASP.NET_Core-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)

**Data**  
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Azure SQL](https://img.shields.io/badge/Azure_SQL-0078D4?style=flat-square&logo=microsoftsqlserver&logoColor=white)
![Cosmos DB](https://img.shields.io/badge/Cosmos_DB-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)

**ML / AI**  
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)

**DevOps & IaC**  
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Azure DevOps](https://img.shields.io/badge/Azure_DevOps-0078D7?style=flat-square&logo=azuredevops&logoColor=white)

### 📜 Certifications

![Azure Solutions Architect Expert](https://img.shields.io/badge/Azure_Solutions_Architect-Expert-0078D4?style=flat-square&logo=microsoft&logoColor=white)
![Azure Administrator](https://img.shields.io/badge/Azure_Administrator-AZ--104-0078D4?style=flat-square&logo=microsoft&logoColor=white)
![AI Apps & Agents Developer](https://img.shields.io/badge/AI_Apps_%26_Agents_Developer-AI--103-0078D4?style=flat-square&logo=microsoft&logoColor=white)
![Agentic AI Solutions Architect](https://img.shields.io/badge/Agentic_AI_Solutions_Architect-AB--100-0078D4?style=flat-square&logo=microsoft&logoColor=white)
![Cisco CCNA](https://img.shields.io/badge/Cisco_CCNA-1BA0D7?style=flat-square&logo=cisco&logoColor=white)

---

<p align="center"><sub>📫 <a href="https://www.linkedin.com/in/nsammo">linkedin.com/in/nsammo</a> · nsalehin2002@gmail.com</sub></p>
