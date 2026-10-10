<!-- ============ HEADER ============ -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=230&section=header&text=Aditya%20Purohit&fontSize=54&fontColor=ffffff&animation=fadeIn&fontAlignY=36&desc=AI%20%2F%20ML%20Engineer%20%C2%B7%20NLP%20%C2%B7%20Agentic%20Systems%20%C2%B7%20Full%20Stack&descSize=18&descAlignY=58" alt="Header" />
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

<p align="center">
  <img src="https://img.shields.io/badge/📍_Kolhapur,_India-0f2027?style=flat-square&labelColor=0f2027&color=2dd4bf" />
  <img src="https://img.shields.io/badge/🎓_PG_Diploma_in_AI-IIT_Jodhpur-0f2027?style=flat-square&labelColor=0f2027&color=2dd4bf" />
  <img src="https://img.shields.io/badge/🟢_Open_to_AI%2FML_roles-0f2027?style=flat-square&labelColor=0f2027&color=22c55e" />
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

## ⚡ Impact at a Glance

<p align="center">
  <img src="https://img.shields.io/badge/Lead%20model%20ROC--AUC-0.863%20(baseline%200.632)-2dd4bf?style=for-the-badge&labelColor=0f2027" />
  <img src="https://img.shields.io/badge/Leads%20processed-5%2C000%20%C2%B7%20zero%20failures-22c55e?style=for-the-badge&labelColor=0f2027" />
</p>
<p align="center">
  <img src="https://img.shields.io/badge/Answerable%20questions%20correct-2%2F13%20%E2%86%92%2013%2F13-a78bfa?style=for-the-badge&labelColor=0f2027" />
  <img src="https://img.shields.io/badge/Safety-100%25%20held%20throughout-f59e0b?style=for-the-badge&labelColor=0f2027" />
</p>
<p align="center">
  <img src="https://img.shields.io/badge/Cached%20answers-~1%20ms-38bdf8?style=for-the-badge&labelColor=0f2027" />
  <img src="https://img.shields.io/badge/Refusals-~2.4%20s%20%E2%86%92%20under%204%20ms-fb7185?style=for-the-badge&labelColor=0f2027" />
</p>

<sub>RAG figures come from my own 19-question golden evaluation set, which I treat as a regression suite rather than proof of real-world accuracy. The lead model was trained on simulated outcome labels, because the dataset's original labels carried no signal (ROC-AUC 0.50). I disclose that in the model card.</sub>

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

## 🏗️ How I Build AI Systems

```mermaid
flowchart LR
  A["1 · Validate the data"] --> B["2 · Baseline, then compare models"]
  B --> C["3 · Hard rules before any model"]
  C --> D["4 · Independent evaluation or critic"]
  D --> E{"Confident?"}
  E -->|yes| F["Act"]
  E -->|no| G["Escalate to a human, or refuse"]
  F --> H[("5 · Audit trail")]
  G --> H
  classDef step fill:#0f2027,stroke:#2dd4bf,color:#e6fffb,stroke-width:1.5px
  classDef decide fill:#3b2a0a,stroke:#f59e0b,color:#ffffff,stroke-width:1.5px
  classDef human fill:#2a1f4d,stroke:#a78bfa,color:#ffffff,stroke-width:1.5px
  class A,B,C,D,F step
  class E decide
  class G,H human
```

---

## 🚀 Project Spotlights

### 🤖 Multi-Agent Lead Decisioning &nbsp;·&nbsp; [View repo](https://github.com/adityapurohit-tech/multi-agent-lead-decisioning)

| | |
|:--|:--|
| **Problem** | Marketing teams make repetitive triage and campaign decisions that have to be consistent, explainable and safe to automate. |
| **Approach** | An 11-agent LangGraph workflow. A compliance gate runs before any model. Lead triage (logistic regression with reason codes) and campaign clustering (KMeans) run in parallel. A critic loop is capped at 3 revisions, and borderline leads pause the graph for human review. Redis holds fast state and frequency caps, and Neo4j holds the lead, campaign and decision graph. |
| **Result** | 0.863 ROC-AUC against a 0.632 baseline, and 5,000 leads processed with zero failures. |

<img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square" /> <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white" /> <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" /> <img src="https://img.shields.io/badge/Neo4j-4581C3?style=flat-square&logo=neo4j&logoColor=white" /> <img src="https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white" /> <img src="https://img.shields.io/badge/WebSockets-010101?style=flat-square" />

<details>
<summary><b>🔎 See the agent graph</b></summary>

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
  classDef core fill:#0f2027,stroke:#2dd4bf,color:#e6fffb,stroke-width:1.5px
  classDef gate fill:#3b2a0a,stroke:#f59e0b,color:#ffffff,stroke-width:1.5px
  classDef human fill:#2a1f4d,stroke:#a78bfa,color:#ffffff,stroke-width:1.5px
  class L,CX,T,CO,E,CM,N,S core
  class CG,R,QC gate
  class HR human
```

</details>

### 🧠 Regulatory-Grade RAG Platform &nbsp;·&nbsp; [View repo](https://github.com/adityapurohit-tech/Regulatory-Grade-Risk-Aware-Enterprise-RAG-Platform)

| | |
|:--|:--|
| **Problem** | Most RAG demos look impressive but quietly hallucinate. In a regulated or healthcare setting, a wrong answer isn't acceptable. |
| **Approach** | Hybrid retrieval (FAISS + BM25 fused with Reciprocal Rank Fusion), a confidence gate that skips the model when nothing relevant is found, and claim-level grounding that blocks any unverified claim or number. Redis handles caching and rate limiting, and every decision is written to a PostgreSQL audit trail. |
| **Result** | Answerable questions went from 2 of 13 to 13 of 13 correct on my golden set, with 100% safety held throughout. Refusals dropped from about 2.4 s to under 4 ms. |

<img src="https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white" /> <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white" /> <img src="https://img.shields.io/badge/FAISS-0467DF?style=flat-square" /> <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" /> <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" /> <img src="https://img.shields.io/badge/WebSockets-010101?style=flat-square" />

<details>
<summary><b>🔎 See the pipeline</b></summary>

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
  classDef core fill:#0f2027,stroke:#2dd4bf,color:#e6fffb,stroke-width:1.5px
  classDef gate fill:#3b2a0a,stroke:#f59e0b,color:#ffffff,stroke-width:1.5px
  classDef stop fill:#3a1212,stroke:#ef4444,color:#ffffff,stroke-width:1.5px
  classDef audit fill:#2a1f4d,stroke:#a78bfa,color:#ffffff,stroke-width:1.5px
  class Q,A,H,L,D core
  class G,C,T,V gate
  class R1,N,B stop
  class P audit
```

</details>

### 📦 More Projects

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

## 🧭 Engineering Principles

- 🧪 **Validate the data before the model.** If the labels are noise, say so out loud.
- 🛡️ **Hard rules first, ML second.** Compliance checks run before any model is called.
- 🔍 **Never let the writer grade its own work.** An independent critic checks every draft.
- 🙋 **Escalate when unsure.** Borderline cases pause for a human instead of guessing.
- 📜 **Every decision leaves a trail** that can be replayed and audited.

---

## 🗺️ What's Next on My List

- 🔬 An **NLI entailment model** as a second grader, to catch negation flips like "is covered" turning into "is not covered"
- 📄 **OCR** for scanned PDFs, and a **semantic cache** to raise the cache hit rate
- ✍️ An **LLM drafting step** in the agent system, with the independent critic left exactly as it is
- 🔌 Going deeper on agent protocols (**MCP** and **A2A**)

---

## 🛠️ Toolbox

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,flask,pytorch,tensorflow,sklearn,postgres,mongodb,redis,neo4j,aws,git&perline=11" alt="Tech Stack" />
</p>

<p align="center"><sub><b>Also:</b> LangChain · LangGraph · FAISS · BM25 · NLP · WebSockets · REST APIs</sub></p>

<p align="center">
  <img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=adityapurohit-tech&layout=compact&theme=radical&hide_border=true&exclude_repo=sanskrit-english-nmt,AI-Driven-Multi-Agent-Marketing-System" alt="Top languages" />
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
