<div align="center">
  <img src="./assets/banner.svg" alt="" width="100%" />
</div>

<br/>

<div align="center">
  <img src="https://readme-typing-svg.demolab.com?font=IBM+Plex+Mono&weight=500&size=22&duration=2800&pause=900&color=58A6FF&center=true&vCenter=true&width=640&lines=Building+systems+that+behave+under+pressure;Real-time+infra,+routing,+and+failure-aware+design;Applied+AI+with+guardrails,+not+guesswork" alt="" />
</div>

<div align="center">

Systems focused engineer working on real time infrastructure, simulation, and LLM safety pipelines

</div>

<br/>

---

### Focus

- Designing systems that don't break under load routing, backpressure, real time state
- Building simulation first tools to reason about system behaviour instead of guessing
- Exploring LLM pipelines under adversarial conditions (injection, leakage, noisy inputs)
- Prioritising observability and reproducibility over surface level features

---

Systems > features. Focus on behaviour, trade offs, and failure modes.

### Selected work

**[System Decision Simulator](https://github.com/sinhaaarushi/System-Decision-Simulator)**

| | |
| --- | --- |
| **Problem** | Simulating real time task routing decisions under load with measurable trade offs |
| **Solution** | Tick-based simulator with **WebSocket** live feed, **metrics**, **replay**, **seeded RNG**, twin strategy compare, JSON export. |
| **Stack** | Node, Express, `ws`, React, Vite, TypeScript, Vitest, GitHub Actions |

**[AUTODRIVE](https://github.com/sinhaaarushi/AUTODRIVE)**

| | |
| --- | --- |
| **Problem** | Simulating autonomous driving requires coordinating perception, decision making, and control across multiple models |
| **Solution** | Built a multi model pipeline combining computer vision and decision logic to simulate real time driving behavior |
| **Stack** | Python, computer vision, deep learning, simulation pipeline |

**[rag-product-support-chatbot](https://github.com/sinhaaarushi/rag-product-support-chatbot)**

| | |
| --- | --- |
| **Problem** | Product support systems struggle to retrieve accurate, context aware information from large knowledge bases |
| **Solution** | Implemented a RAG pipeline using retrieval + generation to answer queries with improved relevance and context |
| **Stack** | Python, OpenSearch, HuggingFace, retrieval pipelines |

**[AI-Collections-Agent-Simulator](https://github.com/sinhaaarushi/AI-Collections-Agent-Simulator)**

| | |
| --- | --- |
| **Problem** | Coordinating multiple agents for decision making and task handling lacks clear modeling and evaluation under different conditions |
| **Solution** | Built an agent based simulation system to model interactions, decision flows, and outcomes across multiple agents in a controlled environment |
| **Stack** | Python, agent logic, simulation workflows, backend processing |

### Currently building

- Increasing realism and control in task routing simulation (latency, queue behavior)
- Strengthening AUTODRIVE decision pipeline across perception → action flow
- Studying system behavior under failure and uneven load conditions

### Metrics

<div align="center">
  <img height="145" src="https://github-readme-stats.vercel.app/api?username=sinhaaarushi&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=false&line_height=24&hide_rank=true&hide=stars,prs,issues,contribs" alt="GitHub stats" />
  <img height="145" src="https://streak-stats.demolab.com/?user=sinhaaarushi&theme=tokyonight&hide_border=true" alt="Streak" />
</div>

### Thinking about

- Where simulation replaces intuition in system design
- How LLM systems fail silently in production
- Making infra decisions observable, not assumed

### Stack (compact)

<div align="center">
  <img src="https://skillicons.dev/icons?i=ts,js,nodejs,react,py,git,docker,linux&theme=dark" alt="Tech stack" />
</div>
