<img src="https://capsule-render.vercel.app/api?type=slice&color=0:0f0c29,50:3b0764,100:7c3aed&height=260&section=header&text=Imtiaz%20Khan&fontSize=75&fontColor=ffffff&fontAlignY=48&fontAlign=30&desc=AI%20Architect%20%E2%80%94%20Agentic%20Systems%20%C2%B7%20LLM%20Infrastructure%20%C2%B7%20Enterprise%20RAG&descSize=16&descColor=ddd6fe&descAlignY=66&descAlign=30&animation=twinkling&stroke=a78bfa&strokeWidth=2" width="100%"/>

<div align="center">

<a href="https://github.com/ImtiazKhanDS">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=24&duration=2500&pause=1000&color=A78BFA&center=true&vCenter=true&width=800&lines=%F0%9F%8F%86+2%C3%97+AWS+GenAI+Innovation+Hackathon+Winner;%F0%9F%9A%80+Building+REX+%E2%80%94+Enterprise+AI+%40+Rackspace;%F0%9F%A7%A0+LangGraph+%C2%B7+MCP+%C2%B7+RAG+%C2%B7+AWS+Bedrock;%E2%9A%A1+12%2B+Years+Shipping+AI+at+Scale" alt="Typing SVG"/>
</a>

<br/><br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/imtiaz-khan-ai-enthusiast-54257bbb)
[![Twitter](https://img.shields.io/badge/X%2FTwitter-000000?style=for-the-badge&logo=x&logoColor=white)](https://twitter.com/imtiazkhan_ds)
[![Portfolio](https://img.shields.io/badge/Portfolio-FF5722?style=for-the-badge&logo=google-chrome&logoColor=white)](https://datascienceportfol.io/ImtiazKhan)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:imtiaz.khan.bds@gmail.com)

<br/>

![](https://img.shields.io/badge/⚡_Experience-12%2B_Years-7c3aed?style=flat-square&labelColor=1e1b4b)
&nbsp;
![](https://img.shields.io/badge/🏆_AWS_Hackathons-2×_Winner-f59e0b?style=flat-square&labelColor=1e1b4b)
&nbsp;
![](https://img.shields.io/badge/🏢_Currently-Rackspace-0ea5e9?style=flat-square&labelColor=1e1b4b)
&nbsp;
![](https://img.shields.io/badge/🌍_Based_in-Andhra_Pradesh,_India-10b981?style=flat-square&labelColor=1e1b4b)
&nbsp;
![Profile Views](https://komarev.com/ghpvc/?username=ImtiazKhanDS&style=flat-square&color=7c3aed&label=👁️+Profile+Views&abbreviated=true)

</div>

---

<table>
<tr>
<td width="58%" valign="top">

## 🧠 &nbsp; About Me

AI Architect at **Rackspace** designing and shipping production-grade intelligent systems. I focus on the hard problems — agent reliability at scale, RAG retrieval accuracy, LLM observability, and the infrastructure fabric that holds it all together.

Currently building **REX** (Rackspace Expert), an enterprise AI assistant on AWS Bedrock + LangGraph + MCP, and **FLO**, the document ingestion pipeline powering REX's retrieval layer.

**What I've shipped:**

- 🏥 &nbsp; RAG for clinical trials @ H1 Life Sciences → secured **IQVIA** deal, onboarded **Novartis & Eli Lilly**
- 🔐 &nbsp; PII/PHI detection @ Palo Alto Networks → **false positives: 15% → 7%**
- 📄 &nbsp; Clinical doc review @ Novartis → **16 hrs → 4 hrs**
- 🎓 &nbsp; GenAI on Netacad @ Cisco → **5 language** multilingual query engine
- 📊 &nbsp; Fraud ML @ Deloitte → **8% fraud reduction**, complaint triage **20 hrs → 2 min**

</td>
<td width="42%" valign="top">

## 🏆 &nbsp; Awards

<div align="center">

<img src="https://img.shields.io/badge/AWS_GenAI_Innovation_Center-Partner_Hackathon-FF9900?style=for-the-badge&logo=amazon-aws&logoColor=white"/>

<br/><br/>

<table>
<tr>
<td align="center">

**🥇 MCP Track**
<br/>
<sub>Model Context Protocol</sub>
<br/>
<img src="https://img.shields.io/badge/Winner-MCP_Architecture-7c3aed?style=flat-square"/>

</td>
<td align="center">

**🥇 Agentic AI Track**
<br/>
<sub>Multi-Agent Orchestration</sub>
<br/>
<img src="https://img.shields.io/badge/Winner-Agentic_Systems-7c3aed?style=flat-square"/>

</td>
</tr>
</table>

<br/>

![Rackspace](https://img.shields.io/badge/Rackspace_×_AWS-Recognized_for_Innovation-FF9900?style=flat-square&logo=amazon-aws&logoColor=white)

</div>

</td>
</tr>
</table>

---

## 🏗️ &nbsp; How I Architect AI Systems

```mermaid
flowchart LR
    U([👤 Enterprise User]) --> AG

    subgraph AGENT ["🤖  Agent Layer  —  LangGraph + MCP"]
        AG[Planner] --> T1[RAG Tool]
        AG --> T2[LLM Tool]
        AG --> T3[MCP Tool]
    end

    subgraph RETRIEVAL ["🔍  Retrieval Layer"]
        T1 --> OS[(OpenSearch)]
        T1 --> VDB[(Milvus / Pinecone)]
        FLO[FLO Pipeline] -->|embed + index| OS
    end

    subgraph LLM ["🧠  LLM Layer  —  AWS Bedrock"]
        T2 --> CL[Claude]
        T2 --> GP[GPT-4]
        T2 --> LL[Llama 3.1]
    end

    subgraph OBS ["📡  Observability"]
        AG -.->|trace| AP[Arise Phoenix]
        AG -.->|eval| LS[LangSmith]
    end

    T1 --> AG
    T2 --> AG
    T3 --> AG
    AG --> U

    style AGENT fill:#1e1b4b,stroke:#7c3aed,color:#ddd6fe
    style RETRIEVAL fill:#0c1a2e,stroke:#0ea5e9,color:#bae6fd
    style LLM fill:#1a0a2e,stroke:#a855f7,color:#e9d5ff
    style OBS fill:#0a1f1a,stroke:#10b981,color:#a7f3d0
```

---

## ⚡ &nbsp; Tech Stack

<div align="center">

<table>
<tr>
<td align="center" width="33%">

**🤖 &nbsp; Agents & LLMs**

[![](https://skillicons.dev/icons?i=python,pytorch&theme=dark)](https://skillicons.dev)

![LangGraph](https://img.shields.io/badge/LangGraph-111827?style=flat-square&logo=langchain&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![MCP](https://img.shields.io/badge/MCP_Protocol-7c3aed?style=flat-square)
![Claude](https://img.shields.io/badge/Anthropic_Claude-191919?style=flat-square&logo=anthropic&logoColor=white)
![OpenAI](https://img.shields.io/badge/GPT--4-412991?style=flat-square&logo=openai&logoColor=white)
![Bedrock](https://img.shields.io/badge/AWS_Bedrock-FF9900?style=flat-square&logo=amazon-aws&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![LlamaIndex](https://img.shields.io/badge/LlamaIndex-6E44FF?style=flat-square)
![Sema4](https://img.shields.io/badge/Sema4-0ea5e9?style=flat-square)

</td>
<td align="center" width="33%">

**🗄️ &nbsp; Retrieval & Data**

[![](https://skillicons.dev/icons?i=postgres,docker&theme=dark)](https://skillicons.dev)

![OpenSearch](https://img.shields.io/badge/OpenSearch-005EB8?style=flat-square&logo=opensearch&logoColor=white)
![Elasticsearch](https://img.shields.io/badge/Elasticsearch-005571?style=flat-square&logo=elasticsearch&logoColor=white)
![Milvus](https://img.shields.io/badge/Milvus-00A1EA?style=flat-square)
![Pinecone](https://img.shields.io/badge/Pinecone-000000?style=flat-square)
![pgvector](https://img.shields.io/badge/pgvector-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![AWS KB](https://img.shields.io/badge/AWS_KnowledgeBase-FF9900?style=flat-square&logo=amazon-aws&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Pydantic](https://img.shields.io/badge/Pydantic-E92063?style=flat-square)

</td>
<td align="center" width="33%">

**📡 &nbsp; Infra & Observability**

[![](https://skillicons.dev/icons?i=aws,kubernetes,gcp,azure&theme=dark)](https://skillicons.dev)

![Arise Phoenix](https://img.shields.io/badge/Arize_Phoenix-6B21A8?style=flat-square)
![LangSmith](https://img.shields.io/badge/LangSmith-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![Superset](https://img.shields.io/badge/Apache_Superset-20A6C9?style=flat-square&logo=apache&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat-square)
![CircleCI](https://img.shields.io/badge/CircleCI-343434?style=flat-square&logo=circleci&logoColor=white)
![EKS](https://img.shields.io/badge/AWS_EKS-FF9900?style=flat-square&logo=amazon-eks&logoColor=white)

</td>
</tr>
</table>

</div>

---

## 🚀 &nbsp; Featured Projects

<div align="center">
<table>
<tr>
<td align="center" width="50%">
<a href="https://github.com/ImtiazKhanDS/MCPEval">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=ImtiazKhanDS&repo=MCPEval&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=a78bfa&icon_color=a78bfa&text_color=c9d1d9&description_lines_count=2"/>
</a>
</td>
<td align="center" width="50%">
<a href="https://github.com/ImtiazKhanDS/ai-research-agent">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=ImtiazKhanDS&repo=ai-research-agent&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=a78bfa&icon_color=a78bfa&text_color=c9d1d9&description_lines_count=2"/>
</a>
</td>
</tr>
<tr>
<td align="center" width="50%">
<a href="https://github.com/ImtiazKhanDS/PDFAgent">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=ImtiazKhanDS&repo=PDFAgent&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=a78bfa&icon_color=a78bfa&text_color=c9d1d9&description_lines_count=2"/>
</a>
</td>
<td align="center" width="50%">
<a href="https://github.com/ImtiazKhanDS/ai-architect">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=ImtiazKhanDS&repo=ai-architect&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=a78bfa&icon_color=a78bfa&text_color=c9d1d9&description_lines_count=2"/>
</a>
</td>
</tr>
</table>
</div>

---

## 📊 &nbsp; GitHub Stats

<div align="center">

<img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=ImtiazKhanDS&theme=tokyonight" width="95%"/>

<br/>

<table>
<tr>
<td>
<img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=ImtiazKhanDS&theme=tokyonight"/>
</td>
<td>
<img src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=ImtiazKhanDS&theme=tokyonight"/>
</td>
<td>
<img src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=ImtiazKhanDS&theme=tokyonight"/>
</td>
<td>
<img src="https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=ImtiazKhanDS&theme=tokyonight&utcOffset=5.5"/>
</td>
</tr>
</table>

<br/>

<img src="https://streak-stats.demolab.com?user=ImtiazKhanDS&theme=tokyonight&hide_border=true&background=0D1117&ring=A78BFA&fire=A78BFA&currStreakLabel=A78BFA&sideLabels=A78BFA&dates=c9d1d9" width="55%"/>

<br/><br/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=ImtiazKhanDS&bg_color=0d1117&color=a78bfa&line=7c3aed&point=ddd6fe&area=true&hide_border=true&area_color=1e1b4b" width="95%"/>

<br/>

<img src="https://github-profile-trophy.vercel.app/?username=ImtiazKhanDS&theme=tokyonight&no-frame=true&no-bg=true&column=7" width="95%"/>

</div>

---

## 🐍 &nbsp; Contribution Graph

<div align="center">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/ImtiazKhanDS/ImtiazKhanDS/output/github-snake-dark.svg"/>
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/ImtiazKhanDS/ImtiazKhanDS/output/github-snake.svg"/>
  <img alt="github-snake" src="https://raw.githubusercontent.com/ImtiazKhanDS/ImtiazKhanDS/output/github-snake-dark.svg" width="95%"/>
</picture>
</div>

---

<div align="center">

<br/>

*"The hardest part of AI architecture isn't the model — it's everything around it."*

<br/>

[![Let's Connect](https://img.shields.io/badge/Let's_Build_Something_Together-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/imtiaz-khan-ai-enthusiast-54257bbb)

<br/>

</div>

<img src="https://capsule-render.vercel.app/api?type=slice&color=0:7c3aed,50:3b0764,100:0f0c29&height=180&section=footer&reversal=true&fontColor=ffffff" width="100%"/>
