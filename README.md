<!-- ================= HEADER ================= -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:22d3ee,50:a78bfa,100:f472b6&height=190&section=header&text=Aakash%20Siwach&fontSize=58&fontColor=ffffff&fontAlignY=36&desc=Project%20Lead%20%C2%B7%20SDE%20II%20%C2%B7%20Backend%20%26%20AI%20Engineer&descSize=18&descAlignY=58&animation=fadeIn" alt="Aakash Siwach" width="100%" />
</p>

<p align="center">
  <a href="https://aakashsiwach.github.io/">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&duration=3000&pause=900&color=22D3EE&center=true&vCenter=true&width=640&lines=Java+%C2%B7+Spring+Boot+microservices;Python+%C2%B7+FastAPI+%C2%B7+AI+agents;RAG+over+codebases+with+cited+answers;Payment+systems+%C2%B7+3DS+%C2%B7+PCI+DSS;Leading+a+team+of+9%2B+engineers" alt="Typing intro" />
  </a>
</p>

<p align="center">
  <a href="https://aakashsiwach.github.io/"><img src="https://img.shields.io/badge/Portfolio-aakashsiwach.github.io-0b1220?style=flat-square&logo=githubpages&logoColor=22d3ee&labelColor=0b1220" alt="Portfolio" /></a>
  <a href="https://www.linkedin.com/in/aakashsiwach/"><img src="https://img.shields.io/badge/LinkedIn-aakashsiwach-0b1220?style=flat-square&logo=linkedin&logoColor=0A66C2&labelColor=0b1220" alt="LinkedIn" /></a>
  <a href="https://aakashsiwach.github.io/assets/Aakash_Siwach_Resume.pdf"><img src="https://img.shields.io/badge/Resume-PDF-0b1220?style=flat-square&logo=readdotcv&logoColor=34d399&labelColor=0b1220" alt="Resume" /></a>
  <a href="mailto:aakashsiwach19@gmail.com"><img src="https://img.shields.io/badge/Email-Say%20hi-0b1220?style=flat-square&logo=gmail&logoColor=EA4335&labelColor=0b1220" alt="Email" /></a>
  <img src="https://img.shields.io/badge/Status-Open%20to%20opportunities-34d399?style=flat-square&labelColor=0b1220" alt="Open to opportunities" />
</p>

---

## 👋 About me

```yaml
name:      Aakash Siwach
role:      Project Lead & SDE II @ Innostax Software Labs
location:  Gurugram, India  ·  remote-friendly
experience: 5+ years  ·  leading 9+ engineers & QAs
focus:     [Java / Spring Boot, Python / FastAPI, RAG, AI agents, MCP, LLM evals]
building:  CodeAtlas  →  RAG for Java codebases with file-and-line citations
```

- 🏥 **Leading Tendable** — a cloud quality-inspection and auditing platform for health & social care (React Remix, Kotlin, Swift, Rails + QA). Code review, prioritisation, deployments and releases.
- 🤖 **Building QA Scanner** — AI agents crawl a site with Playwright to generate test cases and find bugs, vulnerabilities and SEO issues. Moved from a Node.js monolith to Python/FastAPI microservices with parallel multi-model runs, an MCP server, evals and Langfuse.
- 🧭 **Built CodeAtlas** — an open-source, evaluation-driven RAG assistant for Java/Spring Boot codebases (details below).
- 💳 **Previously** — led the global payment flow for Bancstac (VISA, Mastercard, Amex, UnionPay, JCB, 3DS, PCI DSS) on Spring Boot microservices, cutting gateway latency by ~20%.

---

## 🚀 Featured project — [CodeAtlas](https://github.com/aakashsiwach/codeatlas-rag)

<table>
<tr>
<td width="58%" valign="top">

**Retrieval-augmented answers about Java/Spring Boot codebases, with file-and-line citations.**

Ask *"What breaks if I change the `Owner` entity?"* or *"Which services call `/orders/{id}`?"* and get an answer that cites the exact files, methods and doc sections it used — or an honest *"I don't know"* when retrieval confidence is too low.

- 🌳 **Code-aware chunking** with tree-sitter (classes, methods, Spring stereotypes, endpoints, Feign clients)
- 🔀 **Hybrid retrieval** — BM25 with a code tokenizer + Qdrant vectors, fused with RRF
- 🎯 **Cross-encoder reranking** that also drives the refusal threshold
- 🕸️ **Code graph** (NetworkX) for change-impact and caller/callee questions
- 📏 **Eval harness** — 64-question set with a held-out test split, recall@k / MRR / faithfulness
- ⚡ Incremental indexing, GitHub webhook re-index, FastAPI + streaming, React/TS UI

</td>
<td width="42%" valign="top">

**Held-out test split · recall@5**

| Setup | recall@5 | MRR |
|---|:---:|:---:|
| Naive chunks + vector | 0.704 | 0.627 |
| AST + hybrid + rerank + graph | **0.812** | **0.702** |

**Change-impact questions:** 0.417 → **0.850** recall@5

<sub>Retrieval only, PetClinic @ `500158f`, k = 5. Full methodology in the repo.</sub>

<p>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" />
<img src="https://img.shields.io/badge/Qdrant-DC244C?style=flat-square&logo=qdrant&logoColor=white" />
<img src="https://img.shields.io/badge/tree--sitter-1F2937?style=flat-square" />
<img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" />
<img src="https://img.shields.io/badge/Claude%20%7C%20OpenAI%20%7C%20Bedrock-6E56CF?style=flat-square" />
</p>

</td>
</tr>
</table>

<p align="center">
  <a href="https://github.com/aakashsiwach/codeatlas-rag">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=aakashsiwach&repo=codeatlas-rag&theme=tokyonight&hide_border=true&bg_color=0b1220&title_color=22d3ee&icon_color=a78bfa" alt="CodeAtlas repo card" />
  </a>
  <a href="https://github.com/aakashsiwach/aakashsiwach.github.io">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=aakashsiwach&repo=aakashsiwach.github.io&theme=tokyonight&hide_border=true&bg_color=0b1220&title_color=22d3ee&icon_color=a78bfa" alt="Portfolio repo card" />
  </a>
</p>

---

## 🧠 Tech stack

<p align="center"><b>Languages & backend</b><br/><br/>
  <img src="https://skillicons.dev/icons?i=java,spring,python,fastapi,ts,js,nodejs,rabbitmq,elasticsearch&theme=dark" alt="Languages and backend" />
</p>
<p align="center"><b>Frontend</b><br/><br/>
  <img src="https://skillicons.dev/icons?i=react,remix,nextjs,angular,vue,html,css&theme=dark" alt="Frontend" />
</p>
<p align="center"><b>Data, cloud & DevOps</b><br/><br/>
  <img src="https://skillicons.dev/icons?i=postgres,mysql,mongodb,redis,aws,docker,jenkins,githubactions,git&theme=dark" alt="Data, cloud and DevOps" />
</p>
<p align="center"><b>AI & testing</b><br/><br/>
  <img src="https://img.shields.io/badge/RAG-0b1220?style=for-the-badge&logo=databricks&logoColor=22d3ee" />
  <img src="https://img.shields.io/badge/AI_Agents-0b1220?style=for-the-badge&logo=probot&logoColor=a78bfa" />
  <img src="https://img.shields.io/badge/MCP-0b1220?style=for-the-badge&logo=anthropic&logoColor=f472b6" />
  <img src="https://img.shields.io/badge/LLM_Evals-0b1220?style=for-the-badge&logo=checkmarx&logoColor=34d399" />
  <img src="https://img.shields.io/badge/Langfuse-0b1220?style=for-the-badge&logo=grafana&logoColor=fbbf24" />
  <img src="https://img.shields.io/badge/Qdrant-0b1220?style=for-the-badge&logo=qdrant&logoColor=DC244C" />
  <img src="https://img.shields.io/badge/Playwright-0b1220?style=for-the-badge&logo=playwright&logoColor=2EAD33" />
  <img src="https://img.shields.io/badge/Cypress-0b1220?style=for-the-badge&logo=cypress&logoColor=white" />
  <img src="https://img.shields.io/badge/Selenium-0b1220?style=for-the-badge&logo=selenium&logoColor=43B02A" />
</p>
<p align="center"><sub>Currently going deeper on <b>LangGraph</b>, multi-agent orchestration and <b>Kubernetes</b>.</sub></p>

---

## 💼 Experience

| | Role | Company | Period |
|:---:|---|---|---|
| 🟢 | **SDE II / Project Lead** | Innostax Software Labs | Jun 2025 – Present |
| ⚪ | Software Development Engineer I | Innostax Software Labs | Nov 2022 – Jun 2025 |
| ⚪ | Associate Software Engineer | Innostax Software Labs | May 2022 – Nov 2022 |
| ⚪ | Software Developer | Paramarsh Informatics | Jan 2022 – May 2022 |
| ⚪ | Software Trainee | Paramarsh Informatics | Jun 2021 – Dec 2021 |

<details>
<summary><b>📈 Selected impact</b></summary>
<br/>

- ⚡ ~20% lower payment-gateway latency; 20% faster transactions at 18% lower cost for a Sri Lankan banking client
- 🧳 SafariNow: ~32% less system complexity and ~78% gain in customer satisfaction
- 🚀 TravelStart: ~30–40% faster with Hibernate second-level caching
- 🌐 Innostax website: ~40% faster after removing ~187 KiB unused CSS and ~87 KiB unused JS
- 🏫 Built and maintain [neweraworldschool.in](https://neweraworldschool.in/)
- ✍️ Articles on the [Innostax blog](https://innostax.com/author/aakash)

🎓 MCA — Dewan Institute of Management Studies, Meerut · BCA — CCS University, Meerut
</details>

---

## 📊 GitHub stats

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=aakashsiwach&show_icons=true&include_all_commits=true&theme=tokyonight&hide_border=true&bg_color=0b1220&title_color=22d3ee&icon_color=a78bfa&text_color=e7ecf5" alt="GitHub stats" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=aakashsiwach&layout=compact&theme=tokyonight&hide_border=true&bg_color=0b1220&title_color=22d3ee&text_color=e7ecf5" alt="Top languages" />
</p>
<p align="center">
  <img src="https://streak-stats.demolab.com?user=aakashsiwach&theme=tokyonight&hide_border=true&background=0b1220&ring=a78bfa&fire=f472b6&currStreakLabel=22d3ee" alt="GitHub streak" />
</p>

---

<p align="center">
  <a href="https://aakashsiwach.github.io/"><img src="https://img.shields.io/badge/Visit%20my%20portfolio-22d3ee?style=for-the-badge&logo=githubpages&logoColor=0b1220" alt="Portfolio" /></a>
  <a href="https://aakashsiwach.github.io/interview/"><img src="https://img.shields.io/badge/Interview%20Prep%20Hub-a78bfa?style=for-the-badge&logo=bookstack&logoColor=0b1220" alt="Interview prep" /></a>
  <a href="https://www.linkedin.com/in/aakashsiwach/"><img src="https://img.shields.io/badge/Let's%20connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
</p>

<p align="center"><i>Building today. Improving tomorrow. Contributing along the way.</i></p>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:f472b6,50:a78bfa,100:22d3ee&height=110&section=footer" alt="" width="100%" />
