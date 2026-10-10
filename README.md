<!-- ============ HEADER ============ -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=230&section=header&text=Aditya%20Purohit&fontSize=54&fontColor=ffffff&animation=fadeIn&fontAlignY=36&desc=AI%20%2F%20ML%20Engineer%20%C2%B7%20NLP%20%C2%B7%20Agentic%20Systems%20%C2%B7%20Full%20Stack&descSize=18&descAlignY=58" alt="Header" />
</p>

<p align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=22&pause=1500&color=14B8A6&center=true&vCenter=true&width=780&height=40&lines=AI%2FML+Engineer+who+ships+end+to+end;Models+you+can+explain%2C+systems+you+can+audit;From+scikit-learn+to+LLM+agents%2C+with+guardrails;Hard+rules+first.+ML+second.+Always+auditable." alt="Typing SVG" />
  </a>
</p>

<p align="center">
  <img height="34" src="https://img.shields.io/badge/Kolhapur%2C%20India-21262d?style=for-the-badge" />
  <img height="34" src="https://img.shields.io/badge/PG%20Diploma%20in%20AI%20%C2%B7%20IIT%20Jodhpur-1f3a5f?style=for-the-badge" />
  <img height="34" src="https://img.shields.io/badge/Open%20to%20AI%2FML%20roles%20and%20projects-166534?style=for-the-badge" />
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/aditya-purohit-77a287227/"><img height="42" src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0A66C2" /></a>
  <a href="mailto:adityapurohit2002@gmail.com"><img height="42" src="https://img.shields.io/badge/Email-Say%20hello-30363d?style=for-the-badge&logo=gmail&logoColor=white&labelColor=30363d" /></a>
</p>

---

## 💡 What I Bring

| 🧠 Trustworthy LLM Apps | 📊 Explainable ML | 🤖 Agentic AI Systems |
|:--|:--|:--|
| **AI that proves its answers.** Every claim is traced back to a source, and when it can't be verified, the system says so instead of guessing. | **Predictions you can defend.** Calibrated scores with plain-English reasons, so every decision can be explained to a stakeholder. | **Automation with judgment.** Parallel agents, an independent critic and a human in the loop for the calls that matter. |

---

## 🧬 `whoami`

```python
class AdityaPurohit:
    role      = "AI/ML Engineer"
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

<table align="center">
  <tr>
    <td align="center" width="33%"><br/><img height="50" src="https://img.shields.io/badge/0.863-0f766e?style=for-the-badge" alt="0.863" /><br/><br/><b>ROC-AUC</b><br/>lead model, against a 0.632 baseline<br/><br/></td>
    <td align="center" width="33%"><br/><img height="50" src="https://img.shields.io/badge/5%2C000-1d4ed8?style=for-the-badge" alt="5%2C000" /><br/><br/><b>Leads processed</b><br/>end to end, with zero failures<br/><br/></td>
    <td align="center" width="33%"><br/><img height="50" src="https://img.shields.io/badge/11-6d28d9?style=for-the-badge" alt="11" /><br/><br/><b>Agents working together</b><br/>parallel branches, critic loop, human review<br/><br/></td>
  </tr>
  <tr>
    <td align="center" width="33%"><br/><img height="50" src="https://img.shields.io/badge/13%20%2F%2013-0f766e?style=for-the-badge" alt="13%20%2F%2013" /><br/><br/><b>Answerable questions correct</b><br/>up from 2 / 13, with safety held at 100%<br/><br/></td>
    <td align="center" width="33%"><br/><img height="50" src="https://img.shields.io/badge/~1%20ms-1d4ed8?style=for-the-badge" alt="~1%20ms" /><br/><br/><b>Cached answers</b><br/>Redis, cleared automatically when documents change<br/><br/></td>
    <td align="center" width="33%"><br/><img height="50" src="https://img.shields.io/badge/%3C%204%20ms-6d28d9?style=for-the-badge" alt="%3C%204%20ms" /><br/><br/><b>Refusal latency</b><br/>down from 2.4 s, because the model is never called<br/><br/></td>
  </tr>
</table>

<p align="center"><sub>RAG figures come from my own 19-question golden evaluation set, which I treat as a regression suite rather than proof of real-world accuracy. The lead model was trained on simulated outcome labels, because the dataset's original labels carried no signal (ROC-AUC 0.50). I disclose that in the model card.</sub></p>

---

## 🎬 See It in Action

<sub>🟩 green = the outcome &nbsp;·&nbsp; 🟥 red = something the system rejected</sub>

**🧠 RAG platform: when the answer isn't in the documents**

```diff
  ❯ Q: How many languages are interpreter services available in?
    ├─ input guards ... passed
    ├─ cache .......... miss
    ├─ retrieval ...... best match is below the 0.40 confidence threshold
    ├─ generation ..... NOT CALLED (the model never gets the chance to guess)
+   └─ reply .......... "Not found in sources"                    ⏱ under 4 ms
```

**🧠 RAG platform: when the model is wrong and the system catches it**

```diff
  ❯ Q: Does the discharge protocol apply to patients who leave against medical advice?
-   ├─ model's own answer ... "no"      ✗ can't be verified against the source
    ├─ grounding check ...... rejected
+   └─ reply ................ the exact source sentence instead:
+                             "This protocol does not apply to patients who leave against
+                              medical advice; those patients follow Protocol CL-DS-07."
```

**🤖 Multi-agent system: a hot lead, and a borderline one**

```diff
  ❯ Hot lead  →  triage 0.83 (Hot) · 4 callback requests vs an average of 1.6 · 0 unsubscribes
-   ├─ Engagement draft 1 ... CTA "Get Audit"      ✗ critic: hot leads need a meeting CTA
+   ├─ Engagement draft 2 ... meeting CTA          ✓ critic passed
+   └─ route ................ sales handoff

  ❯ Borderline lead  →  triage 0.594 (just under the 0.6 Hot threshold)
    └─ route ................ ⏸ graph paused for a human decision (LangGraph interrupt)
```

<sub>Demo runs use synthetic healthcare documents and synthetic lead data. No real patient or customer data.</sub>

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
  classDef safe fill:#2a1f4d,stroke:#a78bfa,color:#ffffff,stroke-width:1.5px
  class A,B,C,D,F step
  class E decide
  class G,H safe
```

---

## 🚀 Project Spotlights

### 🤖 Multi-Agent Lead Decisioning &nbsp;·&nbsp; [View repo](https://github.com/adityapurohit-tech/multi-agent-lead-decisioning)

| | |
|:--|:--|
| **Problem** | Marketing teams make repetitive triage and campaign decisions that have to be consistent, explainable and safe to automate. |
| **Approach** | An 11-agent LangGraph workflow. A compliance gate runs before any model. Lead triage (logistic regression with reason codes) and campaign clustering (KMeans) run in parallel. A critic loop is capped at 3 revisions, and borderline leads pause the graph for human review. Redis holds fast state and frequency caps, and Neo4j holds the lead, campaign and decision graph. |
| **Result** | 0.863 ROC-AUC against a 0.632 baseline, and 5,000 leads processed with zero failures. |

<img height="26" src="https://img.shields.io/badge/LangGraph-1f3a5f?style=flat" /> <img height="26" src="https://img.shields.io/badge/scikit--learn-1f3a5f?style=flat&logo=scikitlearn&logoColor=white" /> <img height="26" src="https://img.shields.io/badge/Redis-1f3a5f?style=flat&logo=redis&logoColor=white" /> <img height="26" src="https://img.shields.io/badge/Neo4j-1f3a5f?style=flat&logo=neo4j&logoColor=white" /> <img height="26" src="https://img.shields.io/badge/Flask-1f3a5f?style=flat&logo=flask&logoColor=white" /> <img height="26" src="https://img.shields.io/badge/WebSockets-1f3a5f?style=flat" />

<details>
<summary><b>🔎 See the agent graph</b></summary>

```mermaid
flowchart LR
  L([Lead]) --> CX["Context<br/>Redis + Neo4j"]
  CX --> CG{"Compliance gate"}
  CG -->|"fails rules"| S["Suppressed<br/>(model never called)"]
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
  classDef safe fill:#2a1f4d,stroke:#a78bfa,color:#ffffff,stroke-width:1.5px
  class L,CX,T,CO,E,CM,N core
  class CG,R,QC gate
  class S,HR safe
```

<sub>🟦 Teal = steps · 🟧 Amber = checkpoints · 🟪 Purple = safe stops, where the system holds back on purpose</sub>

</details>

### 🧠 Regulatory-Grade RAG Platform &nbsp;·&nbsp; [View repo](https://github.com/adityapurohit-tech/Regulatory-Grade-Risk-Aware-Enterprise-RAG-Platform)

| | |
|:--|:--|
| **Problem** | Most RAG demos look impressive but quietly hallucinate. In a regulated or healthcare setting, a wrong answer isn't acceptable. |
| **Approach** | Hybrid retrieval (FAISS + BM25 fused with Reciprocal Rank Fusion), a confidence gate that skips the model when nothing relevant is found, and claim-level grounding that blocks any unverified claim or number. Redis handles caching and rate limiting, and every decision is written to a PostgreSQL audit trail. |
| **Result** | Answerable questions went from 2 of 13 to 13 of 13 correct on my golden set, with 100% safety held throughout. Refusals dropped from about 2.4 s to under 4 ms. |

<img height="26" src="https://img.shields.io/badge/Flask-1f3a5f?style=flat&logo=flask&logoColor=white" /> <img height="26" src="https://img.shields.io/badge/LangChain-1f3a5f?style=flat&logo=langchain&logoColor=white" /> <img height="26" src="https://img.shields.io/badge/FAISS-1f3a5f?style=flat" /> <img height="26" src="https://img.shields.io/badge/Redis-1f3a5f?style=flat&logo=redis&logoColor=white" /> <img height="26" src="https://img.shields.io/badge/PostgreSQL-1f3a5f?style=flat&logo=postgresql&logoColor=white" /> <img height="26" src="https://img.shields.io/badge/WebSockets-1f3a5f?style=flat" />

<details>
<summary><b>🔎 See the pipeline</b></summary>

```mermaid
flowchart LR
  Q([Question]) --> G{"Input guards"}
  G -->|"injection or personal medical advice"| R1["Request declined"]
  G --> C{"Redis cache"}
  C -->|"hit, about 1 ms"| A([Answer])
  C -->|"miss"| H["Hybrid retrieval<br/>FAISS + BM25 + RRF"]
  H --> T{"Confidence gate"}
  T -->|"too low"| N["Replies: not in the documents<br/>(model never called)"]
  T --> L["Generate from retrieved chunks only"]
  L --> V{"Claim-level grounding"}
  V -->|"unverified claim or number"| B["Answer withheld,<br/>source sentence shown instead"]
  V --> D["Risk-tiered decision"]
  D --> P[("PostgreSQL audit trail")]
  classDef core fill:#0f2027,stroke:#2dd4bf,color:#e6fffb,stroke-width:1.5px
  classDef gate fill:#3b2a0a,stroke:#f59e0b,color:#ffffff,stroke-width:1.5px
  classDef safe fill:#2a1f4d,stroke:#a78bfa,color:#ffffff,stroke-width:1.5px
  class Q,A,H,L,D core
  class G,C,T,V gate
  class R1,N,B,P safe
```

<sub>🟦 Teal = steps · 🟧 Amber = checkpoints · 🟪 Purple = safe stops. These are the system refusing on purpose, not errors.</sub>

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

## 🤝 Work With Me

I'm open to AI / ML engineering roles and select project collaborations.

| What I can build | What you get |
|:--|:--|
| 📄 **Document Q&A (RAG) with guardrails** | Answers that cite the exact source, or a clear "not found" instead of a guess |
| 📊 **Predictive scoring & decisioning** | Calibrated scores with plain-English reasons for every decision |
| 🤖 **Multi-agent workflows** | Automation that pauses for human approval on borderline cases |
| 🧪 **Evaluation & quality gates for LLM apps** | Measurable accuracy and safety numbers before anything ships |
| ⚙️ **Full-stack AI apps** | Flask / REST / WebSocket backends with audit trails and live dashboards |

**How I work**

| 1 · Understand | 2 · Validate | 3 · Build | 4 · Measure |
|:--|:--|:--|:--|
| The decision and its risks | The data, before any model | The smallest working version, with tests | Show you the numbers |

<p align="center">
  <a href="mailto:adityapurohit2002@gmail.com?subject=Let%27s%20talk%20about%20a%20project"><img height="46" src="https://img.shields.io/badge/Start%20a%20conversation-2563eb?style=for-the-badge&logo=gmail&logoColor=white" /></a>
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

**Languages & ML**

<img height="30" src="https://img.shields.io/badge/Python-1f3a5f?style=flat&logo=python&logoColor=white" /> <img height="30" src="https://img.shields.io/badge/scikit--learn-1f3a5f?style=flat&logo=scikitlearn&logoColor=white" /> <img height="30" src="https://img.shields.io/badge/PyTorch-1f3a5f?style=flat&logo=pytorch&logoColor=white" /> <img height="30" src="https://img.shields.io/badge/TensorFlow-1f3a5f?style=flat&logo=tensorflow&logoColor=white" /> <img height="30" src="https://img.shields.io/badge/NLP-1f3a5f?style=flat" />

**LLM & Agents**

<img height="30" src="https://img.shields.io/badge/LangChain-4c3a7a?style=flat&logo=langchain&logoColor=white" /> <img height="30" src="https://img.shields.io/badge/LangGraph-4c3a7a?style=flat" /> <img height="30" src="https://img.shields.io/badge/FAISS-4c3a7a?style=flat" /> <img height="30" src="https://img.shields.io/badge/BM25-4c3a7a?style=flat" /> <img height="30" src="https://img.shields.io/badge/Embeddings-4c3a7a?style=flat" />

**Backend & Data**

<img height="30" src="https://img.shields.io/badge/Flask-14532d?style=flat&logo=flask&logoColor=white" /> <img height="30" src="https://img.shields.io/badge/REST%20APIs-14532d?style=flat" /> <img height="30" src="https://img.shields.io/badge/WebSockets-14532d?style=flat" /> <img height="30" src="https://img.shields.io/badge/PostgreSQL-14532d?style=flat&logo=postgresql&logoColor=white" /> <img height="30" src="https://img.shields.io/badge/MongoDB-14532d?style=flat&logo=mongodb&logoColor=white" /> <img height="30" src="https://img.shields.io/badge/Redis-14532d?style=flat&logo=redis&logoColor=white" /> <img height="30" src="https://img.shields.io/badge/Neo4j-14532d?style=flat&logo=neo4j&logoColor=white" />

**Cloud & Tools**

<img height="30" src="https://img.shields.io/badge/AWS-7c4a03?style=flat" /> <img height="30" src="https://img.shields.io/badge/Git-7c4a03?style=flat&logo=git&logoColor=white" />

---

## 🎓 Education & Learning

- **Post-Graduate Diploma in Artificial Intelligence**, IIT Jodhpur (2025 – 2026)
- **AI & ML Bootcamp**, Udemy
- **AI Engineer** and **AI / Data Scientist** tracks, OneRoadmap

---

## 📫 Let's Connect

<p align="center">
  <a href="https://www.linkedin.com/in/aditya-purohit-77a287227/"><img height="42" src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0A66C2" /></a>
  <a href="mailto:adityapurohit2002@gmail.com"><img height="42" src="https://img.shields.io/badge/Email-Say%20hello-30363d?style=for-the-badge&logo=gmail&logoColor=white&labelColor=30363d" /></a>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=adityapurohit-tech&label=Profile%20views&color=1f3a5f&style=flat-square" alt="Profile views" />
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:2c5364,50:203a43,100:0f2027&height=110&section=footer" alt="Footer" />
</p>
