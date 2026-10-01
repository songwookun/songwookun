<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=24&duration=2800&pause=900&color=7C3AED&center=true&vCenter=true&width=640&lines=AI+Application+Engineer;Make+AI+stronger.+Then+verify+it.;RAG+%C2%B7+Agents+%C2%B7+VLM+%C2%B7+LLM+Evaluation;Don't+trust+the+output.+Measure+it." alt="typing" />

### I make AI stronger — and I don't take its word for it.
**An AI application engineer who doubts, measures, and ships only what can be trusted**

<img src="https://komarev.com/ghpvc/?username=songwookun&label=PROFILE+VIEWS&color=7c3aed&style=flat" alt="views" />

[한국어](https://github.com/songwookun) · **English**

</div>

```python
class Woogeun(AIEngineer):
    motto = "Trust, but measure."

    def build(self, task):
        output = self.llm(task)                     # push what AI can do
        evidence = self.measure(output)             # measure it with data and sources, not plausibility
        return output if self.verify(evidence) else self.abstain()   # ship only what holds up
```

**`Generate → Doubt → Measure → Verify → Ship`** &nbsp;(and **Abstain** when the evidence is weak)

- **Push the capability** — search grounding · RAG · agents · multiple models
- **Doubt the output** — never take "measured" or "high accuracy" at face value; re-measure it
- **Keep the evidence** — store sources, scores and traces alongside every result
- **Stop when unsure** — say "not found" instead of a plausible guess

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white)
![RAG](https://img.shields.io/badge/RAG-7C3AED?style=flat-square)
![Agents](https://img.shields.io/badge/AI%20Agents-7C3AED?style=flat-square)
![VLM](https://img.shields.io/badge/VLM-7C3AED?style=flat-square)
![Pinecone](https://img.shields.io/badge/Pinecone-000000?style=flat-square&logo=pinecone&logoColor=white)
![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-425CC7?style=flat-square&logo=opentelemetry&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)

<details>
<summary><b>🔍 What I doubted and verified in each project</b></summary>

| Project | What the AI does | What I doubted and verified |
|---|---|---|
| ⌚ [**wrist-rag**](https://github.com/songwookun/wrist-rag) | Talk to an Apple Watch: it searches and writes a note, then answers only from your notes | A note without sources may be made up → **every note keeps the real search queries and original URLs**. In daily use with a real paid key |
| 🖼️ [**img-vlm-extractor**](https://github.com/songwookun/img-vlm-extractor) | A VLM extracts values from images | Extraction is easy; **trusting it is the problem** → VLM cross-checks + code arithmetic decide reliability |
| 📚 [**md-rag-chatbot**](https://github.com/songwookun/md-rag-chatbot) | Personal knowledge RAG chatbot | Tuning values the AI labeled "measured" were **re-measured by hand**; when to abstain was decided by experiment |
| 🧪 [**agent-eval-lab**](https://github.com/songwookun/agent-eval-lab) | AI agents complete tasks with tools | They behave differently on every run → **4-axis evaluation + OpenTelemetry traces** turn behavior into numbers |

More: [used-deal-analyzer](https://github.com/songwookun/used-deal-analyzer) (queue-based async + LLM price analysis) · [ai-corp](https://github.com/songwookun/ai-corp) (a multi-agent company of 8 AI employees)

</details>

<details>
<summary><b>📊 Languages</b></summary>

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=songwookun&layout=compact&langs_count=4&hide=shaderlab,html,css,c%23,asp.net,shell&exclude_repo=Survivor,BoomDash_2025,NetworkOmok,DragonFlightImitation,Play_Room_Studio,C-Study,ProblemSol2024,Hybrid-application&theme=transparent&hide_border=true&title_color=7c3aed" alt="top languages" />

</details>
