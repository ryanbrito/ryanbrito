<img width="3168" height="792" alt="banner2" src="https://github.com/user-attachments/assets/7e8f33c0-0c59-4df8-b0e6-3bd8c08588dd" />

<br />

<div id="badges" align="center">
  <a href="https://www.linkedin.com/in/ryan-brito/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-blue?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn Badge"/>
  </a>
  <a href="mailto:ryanbragabrito@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email Badge"/>
  </a>
</div>

## Hi, I'm Ryan 👋

**Observability Engineer** at V8.Tech, embedded in a global insurance operation (Argentina, Brazil, US, Mexico).
I turn telemetry into decisions, and incidents into processes that run themselves.

- 📊 **99.985%** SLA/SLO compliance, computed automatically with Elasticsearch Transforms
- 🌎 **20+ applications** monitored across **4 countries**
- 🧭 **80+ alert rules** created, standardized and managed as code
- 🏅 Elastic Certified Kibana Analyst · 🎓 Data Science, FIAP
- 🗣️ Portuguese (native) · English (bilingual) · Spanish (professional)

## 🔭 What I do

- **Reliability (SRE):** I apply the practices from Google's SRE book: SLIs/SLOs, symptom-based alerting, incident response, post-incident analysis and toil reduction.
- **Observability at scale:** Elastic Stack, APM, synthetic monitoring and AKS dashboards, so the NOC sees problems before customers do.
- **Governance and standards:** alert rules as code (80+ reviewed), log and ingest standards, and a process for monitoring identities so cloud metrics don't go dark when secrets expire.
- **Automation:** a Python compliance checker that scores services against global standards, a rules-to-YAML tool that converts live Kibana rules to IaC in one run, and an incident flow from Slack to Elastic Actions to ServiceNow and Zenoss.
- **Business partnership:** I take part in business meetings and help shape business decisions, turning SLA and telemetry data into numbers stakeholders can act on.
- **Enablement:** sprint demos that end in decisions, guides, workshops and onboarding for engineers and SREs.

## 📈 Data

Two pipelines turn raw application logs into business-level SLA numbers. They feed the SLA dashboards the business reads and the alerts that tell teams to act before a breach.

- **Policies SLA: Transform and Pipeline.** Follows each policy operation (enrollment, update, payment, cancellation) from start to finish and compares it with the contractual time window. Ingest pipelines and Elasticsearch Transforms group the log events of each operation, remove duplicates and produce one record per operation with its SLA status. It feeds compliance dashboards by journey and early-warning alerts on operations at risk of breaching.
- **Claims SLA: Transform and Pipeline.** Calculates the SLA of every claim in business time only, with one working-hours calendar and with pauses (such as waiting for documents or medical exams) excluded. Each claim has one row with a clear state (awaiting start, pending within or out of SLA, completed within or out of SLA), and a 15-minute heartbeat keeps open claims at most ~17 minutes behind real time. It was validated against thousands of claims checked independently, and it feeds the business dashboards and the alerts that prevent SLA losses.
- **Data reconciliation:** compared hundreds of thousands of policy records across Power BI, SQL and Elastic to find exactly where the sources disagree.

## 🤖 AI

- **AI agent for root cause analysis:** an Elastic AI agent with ES|QL tools that investigates SLA breaches, so the first diagnosis takes minutes instead of manual digging.
- **Natural-language access to business data:** a chat interface over enterprise databases, built with RAG, MCP, Open WebUI and FastAPI.

## 🛠️ Tech stack

<a href="https://www.elastic.co/elasticsearch" target="_blank"><img src="https://img.shields.io/badge/Elasticsearch-005571?style=for-the-badge&logo=elasticsearch&logoColor=white" alt="Elasticsearch"/></a>
<a href="https://www.elastic.co/kibana" target="_blank"><img src="https://img.shields.io/badge/Kibana-005571?style=for-the-badge&logo=kibana&logoColor=white" alt="Kibana"/></a>
<a href="https://www.elastic.co/elastic-agent" target="_blank"><img src="https://img.shields.io/badge/Elastic%20Agent-005571?style=for-the-badge&logo=elastic&logoColor=white" alt="Elastic Agent"/></a>
<a href="https://opentelemetry.io" target="_blank"><img src="https://img.shields.io/badge/OpenTelemetry-425CC7?style=for-the-badge&logo=opentelemetry&logoColor=white" alt="OpenTelemetry"/></a>
<a href="https://www.dynatrace.com" target="_blank"><img src="https://img.shields.io/badge/Dynatrace-1496FF?style=for-the-badge&logo=dynatrace&logoColor=white" alt="Dynatrace"/></a>
<a href="https://azure.microsoft.com" target="_blank"><img src="https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white" alt="Azure"/></a>
<a href="https://kubernetes.io" target="_blank"><img src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white" alt="Kubernetes"/></a>
<a href="https://azure.microsoft.com/products/devops" target="_blank"><img src="https://img.shields.io/badge/Azure%20DevOps-0078D7?style=for-the-badge&logo=azuredevops&logoColor=white" alt="Azure DevOps"/></a>
<a href="https://www.docker.com" target="_blank"><img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker"/></a>
<a href="https://git-scm.com" target="_blank"><img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git"/></a>
<a href="https://www.linux.org" target="_blank"><img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" alt="Linux"/></a>
<a href="https://www.python.org" target="_blank"><img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"/></a>
<a href="https://dotnet.microsoft.com" target="_blank"><img src="https://img.shields.io/badge/.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white" alt=".NET"/></a>
<a href="https://fastapi.tiangolo.com" target="_blank"><img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" alt="FastAPI"/></a>
<a href="https://kafka.apache.org" target="_blank"><img src="https://img.shields.io/badge/Apache%20Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white" alt="Kafka"/></a>
<a href="https://pandas.pydata.org" target="_blank"><img src="https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="pandas"/></a>
<a href="https://www.postgresql.org" target="_blank"><img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL"/></a>
<a href="https://powerbi.microsoft.com" target="_blank"><img src="https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" alt="Power BI"/></a>
<a href="https://www.servicenow.com" target="_blank"><img src="https://img.shields.io/badge/ServiceNow-81B5A1?style=for-the-badge&logo=servicenow&logoColor=white" alt="ServiceNow"/></a>
<a href="https://www.elastic.co/generative-ai" target="_blank"><img src="https://img.shields.io/badge/Elastic%20AI-005571?style=for-the-badge&logo=elastic&logoColor=white" alt="Elastic AI"/></a>
<a href="https://arxiv.org/abs/2005.11401" target="_blank"><img src="https://img.shields.io/badge/RAG-6E40C9?style=for-the-badge" alt="RAG"/></a>
<a href="https://modelcontextprotocol.io" target="_blank"><img src="https://img.shields.io/badge/MCP-1F1F1F?style=for-the-badge&logo=modelcontextprotocol&logoColor=white" alt="MCP"/></a>
<a href="https://openwebui.com" target="_blank"><img src="https://img.shields.io/badge/Open%20WebUI-2D2D2D?style=for-the-badge&logo=openwebui&logoColor=white" alt="Open WebUI"/></a>

## 🌱 Currently

- Deepening my knowledge on cloud, infrastructure and machine learning
- Broadening my observability toolbox beyond Elastic

## 📫 Let's connect

[LinkedIn](https://www.linkedin.com/in/ryan-brito/) · [Email](mailto:ryanbragabrito@gmail.com)
