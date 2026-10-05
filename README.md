<p align="center">
  <img src="assets/banner.png" width="100%" alt="Muhammad Danial Aslam — Backend &amp; Agentic AI Engineer"/>
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&duration=3600&pause=900&color=58A6FF&center=true&vCenter=true&width=850&height=55&lines=Models+propose.+Policy+decides+what+commits.;MCP+tool+servers+%C2%B7+role-filtered+toolsets;Google+ADK+%C2%B7+Vertex+AI+%C2%B7+Gemini+%C2%B7+BigQuery+vector+search" alt="Models propose. Policy decides what commits."/>
</p>

<p align="center">
  <a href="https://danialaslam04.github.io"><img src="https://img.shields.io/badge/Portfolio-0A0A0B?style=for-the-badge&logo=googlechrome&logoColor=C6F135" alt="Portfolio"/></a>
  <a href="https://www.linkedin.com/in/danial04/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:danialaslam04@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
  <a href="assets/Muhammad-Danial-Aslam-Resume.pdf"><img src="https://img.shields.io/badge/Resume-3FB9A5?style=for-the-badge&logo=readdotcv&logoColor=white" alt="Resume (PDF)"/></a>
</p>

---

## 👨‍💻 &nbsp;About Me

Software engineer with three years of experience designing and delivering production backend systems and agentic AI applications on Google Cloud. Skilled in translating complex business requirements into production-grade software, working across Java/Spring Boot, Trillo Workbench, and Python/FastAPI to build REST APIs, async workflows, and third-party integrations.

---

## 🚀 &nbsp;What I'm Building

> Client platforms, so the repos are private — but this is the work.

### 🏦 &nbsp;Business-Acquisition Marketplace

A Spring Boot domain backend paired with a FastAPI service running **five LLM agents on Google ADK**. Stripe subscription billing, Plaid-backed verification, and three distinct roles — buyers, brokers, and admins — each seeing a different slice of the system.

### 🩺 &nbsp;Concierge Care Platform

Matches aging-adult clients with field staff through an **onboarding agent**, a **task-planning agent**, and a **pod matching engine**, wired into Gusto Embedded Payroll and Checkr background checks.

### 🚚 &nbsp;Multi-Tenant Drayage TMS

An **LLM pipeline that ingests delivery orders straight from email** — extracting and validating the structured data, running credit checks, and creating loads automatically across the order-to-delivery lifecycle.

---

## 🧩 &nbsp;How I Build Agents

**Models propose. Deterministic code executes.** The same pattern across all three platforms —
an agent can reason freely, but it can never reach past the boundary its caller was given, and a
deterministic policy — not the model — decides which writes commit on their own and which stop:

<p align="center">
  <img src="assets/agent-pattern.png" width="100%" alt="Execution pattern: the caller carries identity, the agent proposes but never executes, a role-filtered toolset limits what it can see, the MCP tool server propagates identity per call, and a deterministic policy classifies each write — low-risk writes commit autonomously while high-risk writes hold at a gate for an explicit approve or reject."/>
</p>

Underneath: **Vertex AI** and **Gemini** for inference, routed through **LiteLLM**; **BigQuery
vector search** backing RAG and semantic discovery; **GKE** for orchestration and **Redis** for
caching and rate limiting.

---

## 🛠️ &nbsp;Tech Stack

<div align="center">

**Backend**

<table>
  <tr>
    <td align="center" width="205"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" height="52" alt="Java"/><br/><sub><b>Java</b></sub></td>
    <td align="center" width="205"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/spring/spring-original.svg" height="52" alt="Spring Boot"/><br/><sub><b>Spring Boot</b></sub></td>
    <td align="center" width="205"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" height="52" alt="Python"/><br/><sub><b>Python</b></sub></td>
    <td align="center" width="205"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/fastapi/fastapi-original.svg" height="52" alt="FastAPI"/><br/><sub><b>FastAPI</b></sub></td>
  </tr>
</table>

**Cloud &amp; Infrastructure**

<table>
  <tr>
    <td align="center" width="136"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/googlecloud/googlecloud-original.svg" height="52" alt="Google Cloud"/><br/><sub><b>Google Cloud</b></sub></td>
    <td align="center" width="136"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/kubernetes/kubernetes-original.svg" height="52" alt="Kubernetes"/><br/><sub><b>Kubernetes</b></sub></td>
    <td align="center" width="136"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original.svg" height="52" alt="Docker"/><br/><sub><b>Docker</b></sub></td>
    <td align="center" width="136"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/redis/redis-original.svg" height="52" alt="Redis"/><br/><sub><b>Redis</b></sub></td>
    <td align="center" width="136"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original.svg" height="52" alt="PostgreSQL"/><br/><sub><b>PostgreSQL</b></sub></td>
    <td align="center" width="136"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original.svg" height="52" alt="MySQL"/><br/><sub><b>MySQL</b></sub></td>
  </tr>
</table>

**Agentic AI &amp; LLM**

<table>
  <tr>
    <td align="center" width="136"><img src="https://cdn.simpleicons.org/google/4285F4" height="52" alt="Google ADK"/><br/><sub><b>Google ADK</b></sub></td>
    <td align="center" width="136"><img src="https://cdn.simpleicons.org/modelcontextprotocol/8B949E" height="52" alt="MCP"/><br/><sub><b>MCP</b></sub></td>
    <td align="center" width="136"><img src="https://cdn.simpleicons.org/googlegemini/8E75B2" height="52" alt="Gemini"/><br/><sub><b>Gemini</b></sub></td>
    <td align="center" width="136"><img src="https://cdn.simpleicons.org/googlecloud/4285F4" height="52" alt="Vertex AI"/><br/><sub><b>Vertex AI</b></sub></td>
    <td align="center" width="136"><img src="https://cdn.simpleicons.org/claude/D97757" height="52" alt="Claude"/><br/><sub><b>Claude</b></sub></td>
    <td align="center" width="136"><img src="https://cdn.simpleicons.org/googlebigquery/669DF6" height="52" alt="BigQuery"/><br/><sub><b>BigQuery</b></sub></td>
  </tr>
</table>

**Tools**

<table>
  <tr>
    <td align="center" width="205"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/git/git-original.svg" height="52" alt="Git"/><br/><sub><b>Git</b></sub></td>
    <td align="center" width="205"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postman/postman-original.svg" height="52" alt="Postman"/><br/><sub><b>Postman</b></sub></td>
    <td align="center" width="205"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/intellij/intellij-original.svg" height="52" alt="IntelliJ"/><br/><sub><b>IntelliJ</b></sub></td>
    <td align="center" width="205"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/jira/jira-original.svg" height="52" alt="Jira"/><br/><sub><b>Jira</b></sub></td>
  </tr>
</table>

</div>

## 🎓 &nbsp;Education &amp; Certifications

<div align="center">

**BS Computer Science** — International Islamic University Islamabad

<sub>GOOGLE CLOUD CERTIFICATIONS</sub>

<p>
  <img src="https://img.shields.io/badge/Large_Language_Models-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white" alt="Introduction to Large Language Models — Google Cloud"/>
  <img src="https://img.shields.io/badge/Generative_AI-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white" alt="Introduction to Generative AI — Google Cloud"/>
  <img src="https://img.shields.io/badge/Responsible_AI-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white" alt="Introduction to Responsible AI — Google Cloud"/>
  <img src="https://img.shields.io/badge/Computer_Vision-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white" alt="Computer Vision Fundamentals — Google Cloud"/>
  <img src="https://img.shields.io/badge/Recommendation_Systems-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white" alt="Recommendation Systems — Google Cloud"/>
</p>

</div>

---

## 🔥 &nbsp;GitHub Stats

<p align="center">
  <img src="https://streak-stats.demolab.com?user=DanialAslam04&theme=dark&background=0D1117&border=30363D&ring=58A6FF&fire=FF6B35&currStreakLabel=58A6FF&hide_border=false" alt="GitHub Streak"/>
</p>

---

## 📬 &nbsp;Open To

<p align="center">
  <b>Backend and agentic-AI engineering roles — open to remote, hybrid, or onsite.</b>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/danial04/"><img src="https://img.shields.io/badge/Message_me_on_LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="Message me on LinkedIn"/></a>
  <a href="mailto:danialaslam04@gmail.com"><img src="https://img.shields.io/badge/danialaslam04@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="danialaslam04@gmail.com"/></a>
</p>

<p align="center">
  <img src="assets/footer.png" width="100%" alt=""/>
</p>
