<!-- ============ HEADER ============ -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=210&section=header&text=Aditya%20Purohit&fontSize=52&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=AI%20%2F%20ML%20Engineer%20%C2%B7%20NLP%20%C2%B7%20Agentic%20Systems%20%C2%B7%20Full%20Stack&descSize=18&descAlignY=60" alt="Header" />
</p>

<p align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&pause=1200&color=2DD4BF&center=true&vCenter=true&width=760&lines=AI%2FML+Engineer+who+ships+end+to+end;Models+you+can+explain%2C+systems+you+can+audit;From+scikit-learn+to+LLM+agents%2C+with+guardrails;Hard+rules+first.+ML+second.+Always+auditable." alt="Typing SVG" />
  </a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white" />
  <img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white" />
  <img src="https://img.shields.io/badge/Neo4j-4581C3?style=for-the-badge&logo=neo4j&logoColor=white" />
</p>

---

## 🧬 `whoami`

```python
class AdityaPurohit:
    role      = "AI/ML Engineer & Full Stack Developer @ Microtech Solutions"
    based_in  = "Kolhapur, India 🇮🇳"
    education = "PG Diploma in Artificial Intelligence, IIT Jodhpur"
    focus     = [
        "Machine learning & decisioning systems",
        "NLP & LLM applications",
        "Agentic AI & orchestration",
        "Evaluation, guardrails & reliability",
    ]

    def build(self, problem):
        data  = self.validate(problem.data)        # trust, but verify the labels
        model = self.baseline_then_improve(data)   # simple and explainable first
        return self.add_guardrails(model)          # hard rules, critics, human review
```

> Whether it's a classifier or an LLM, I treat every model as something to **validate before it's trusted**, and I build systems that can explain every decision they make.

---

## 🎯 What I Work On

| | |
|:--|:--|
| 📊 **Machine Learning** | Predictive scoring and clustering with scikit-learn: model comparison, calibration, and explainable reason codes |
| 🗣️ **NLP & LLM Apps** | Embeddings, hybrid retrieval, grounding and hallucination detection |
| 🤖 **Agentic Systems** | Multi-agent workflows in LangGraph with parallel branches, critic loops and human-in-the-loop review |
| 🧪 **Evaluation & Safety** | Golden test sets, quality gates, compliance rules and audit trails |
| ⚙️ **Full Stack Engineering** | REST APIs, WebSockets, PostgreSQL, MongoDB, Redis and Neo4j |

---

## 📈 By the Numbers

| 🤖 Multi-Agent Decisioning | 🧠 RAG Platform |
|:--|:--|
| **0.863 ROC-AUC** on held-out data, against a **0.632** baseline | **2 / 13 → 13 / 13** answerable questions correct, with **100%** safety held throughout |
| **5,000 leads** processed end to end with **zero failures** | Refused-question latency **~2.4 s → under 4 ms** |
| **11 agents** with parallel branches, a critic loop and human review | Repeat questions served from Redis in **~1 ms** |

<sub>RAG figures come from my own 19-question golden evaluation set, which I treat as a regression suite rather than proof of real-world accuracy. The lead model was trained on simulated outcome labels, because the dataset's original labels carried no signal (ROC-AUC 0.50). I disclose that in the model card.</sub>

---

## 🏗️ How I Build AI Systems

```mermaid
flowchart LR
  A["1. Validate the data"] --> B["2. Baseline, then compare models"]
  B --> C["3. Hard rules before any model"]
  C --> D["4. Independent evaluation or critic"]
  D --> E{"Confident?"}
  E -->|yes| F["Act"]
  E -->|no| G["Escalate to a human, or refuse"]
  F --> H[("5. Audit trail")]
  G --> H
```

<details>
<summary><b>🔎 See it in practice: the multi-agent lead decisioning graph</b></summary>

```mermaid
flowchart LR
  L([Lead]) --> CX["Context<br/>Redis + Neo4j"]
  CX --> CG{"Compliance gate"}
  CG -->|"fails rules"| S["Suppress"]
  CG --> T["Lead triage<br/>scikit-learn"]
  CG --> CO["Campaign optimizer<br/>KMeans"]
  T --> R{"Decision router"}
  CO --> R
  R -->|"engage or sales handoff"| E["Engagement"]
  E --> QC{"Quality critic"}
  QC -->|"revise, max 3"| E
  QC -->|"pass"| CM["Commit"]
  R -->|"uncertain"| HR["Human review<br/>(graph paused)"]
  R -->|"low intent"| N["Nurture"]
```

</details>

<details>
<summary><b>🔎 See it in practice: the RAG platform pipeline</b></summary>

```mermaid
flowchart LR
  Q([Question]) --> G{"Input guards"}
  G -->|"injection or personal medical advice"| R1["Refuse"]
  G --> C{"Redis cache"}
  C -->|"hit, about 1 ms"| A([Answer])
  C -->|"miss"| H["Hybrid retrieval<br/>FAISS + BM25 + RRF"]
  H --> T{"Confidence gate"}
  T -->|"too low"| N["Not found"]
  T --> L["Generate from retrieved chunks only"]
  L --> V{"Claim-level grounding"}
  V -->|"unverified claim or number"| B["Block, quote the source instead"]
  V --> D["Risk-tiered decision"]
  D --> P[("PostgreSQL audit trail")]
```

</details>

---

## 🧭 Engineering Principles

- 🧪 **Validate the data before the model.** If the labels are noise, say so out loud.
- 🛡️ **Hard rules first, ML second.** Compliance checks run before any model is called.
- 🔍 **Never let the writer grade its own work.** An independent critic checks every draft.
- 🙋 **Escalate when unsure.** Borderline cases pause for a human instead of guessing.
- 📜 **Every decision leaves a trail** that can be replayed and audited.

---

## 🚀 Featured Work

<p align="center">
  <a href="https://github.com/adityapurohit-tech/multi-agent-lead-decisioning">
    <img width="48%" src="https://github-readme-stats.vercel.app/api/pin/?username=adityapurohit-tech&repo=multi-agent-lead-decisioning&theme=radical&hide_border=true" />
  </a>
  <a href="https://github.com/adityapurohit-tech/Regulatory-Grade-Risk-Aware-Enterprise-RAG-Platform">
    <img width="48%" src="https://github-readme-stats.vercel.app/api/pin/?username=adityapurohit-tech&repo=Regulatory-Grade-Risk-Aware-Enterprise-RAG-Platform&theme=radical&hide_border=true" />
  </a>
</p>
<p align="center">
  <a href="https://github.com/adityapurohit-tech/saasquatch-lead-scorer">
    <img width="31%" src="https://github-readme-stats.vercel.app/api/pin/?username=adityapurohit-tech&repo=saasquatch-lead-scorer&theme=radical&hide_border=true" />
  </a>
  <a href="https://github.com/adityapurohit-tech/AI-Expert-Call-Analyzer">
    <img width="31%" src="https://github-readme-stats.vercel.app/api/pin/?username=adityapurohit-tech&repo=AI-Expert-Call-Analyzer&theme=radical&hide_border=true" />
  </a>
  <a href="https://github.com/adityapurohit-tech/AI-Decision-Simulation-System">
    <img width="31%" src="https://github-readme-stats.vercel.app/api/pin/?username=adityapurohit-tech&repo=AI-Decision-Simulation-System&theme=radical&hide_border=true" />
  </a>
</p>

---

## 🛠️ Toolbox

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,flask,pytorch,tensorflow,sklearn,postgres,mongodb,redis,neo4j,aws,git&perline=11" alt="Tech Stack" />
</p>

<p align="center"><sub><b>Also:</b> LangChain · LangGraph · FAISS · BM25 · NLP · WebSockets · REST APIs</sub></p>

---

## 📊 Activity

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=adityapurohit-tech&show_icons=true&theme=radical&hide_border=true" alt="GitHub Stats" />
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=adityapurohit-tech&theme=react-dark&hide_border=true&area=true" alt="Contribution graph" />
</p>

---

## 🤝 Let's Connect

I'm open to AI / ML engineering roles where reliability matters as much as capability.

<p align="center">
  <a href="https://www.linkedin.com/in/aditya-purohit-77a287227/"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="mailto:adityapurohit2002@gmail.com"><img src="https://img.shields.io/badge/Email-Say%20hello-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=adityapurohit-tech&label=Profile%20views&color=2dd4bf&style=flat-square" alt="Profile views" />
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:2c5364,50:203a43,100:0f2027&height=110&section=footer" alt="Footer" />
</p>
