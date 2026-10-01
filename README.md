<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=24&duration=2800&pause=900&color=7C3AED&center=true&vCenter=true&width=640&lines=AI+Application+Engineer;Make+AI+stronger.+Then+verify+it.;RAG+%C2%B7+Agents+%C2%B7+VLM+%C2%B7+LLM+Evaluation;Don't+trust+the+output.+Measure+it." alt="typing" />

### AI를 더 강하게 쓰되, 그냥 믿지 않는다.
**의심하고, 재보고, 믿을 수 있는 결과만 내보내는 AI 애플리케이션 엔지니어**

<img src="https://komarev.com/ghpvc/?username=songwookun&label=PROFILE+VIEWS&color=7c3aed&style=flat" alt="views" />

**한국어** · [English](https://github.com/songwookun/songwookun/blob/main/README.en.md)

</div>

```python
class Woogeun(AIEngineer):
    motto = "Trust, but measure."

    def build(self, task):
        output = self.llm(task)                     # AI의 능력은 최대한 끌어올리고
        evidence = self.measure(output)             # 그럴듯함 대신 실측과 출처로 재본 뒤
        return output if self.verify(evidence) else self.abstain()   # 믿을 수 있을 때만 내보낸다
```

**`Generate → Doubt → Measure → Verify → Ship`** &nbsp;(근거가 약하면 **Abstain**)

- **능력은 끌어올린다** — 검색 그라운딩 · RAG · 에이전트 · 멀티 모델
- **결과는 의심한다** — "실측", "정확도 높음"을 그대로 받지 않고 직접 재본다
- **근거를 남긴다** — 출처 · 점수 · trace를 결과와 함께 저장한다
- **모르면 멈춘다** — 그럴듯한 답 대신 "없다"고 말하게 만든다

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
<summary><b>🔍 프로젝트마다 무엇을 의심하고 확인했나</b></summary>

| Project | AI가 하는 일 | 내가 의심하고 확인한 것 |
|---|---|---|
| ⌚ [**wrist-rag**](https://github.com/songwookun/wrist-rag) | 애플워치에 말하면 검색해서 노트를 쓰고, 내 노트로만 답하는 RAG | 출처 없는 노트는 지어낸 것일 수 있다 → **실제 검색어와 원문 URL을 노트에 남김**. 실제 유료 키로 매일 사용 중 |
| 🖼️ [**img-vlm-extractor**](https://github.com/songwookun/img-vlm-extractor) | VLM이 이미지에서 값을 추출 | 뽑는 것보다 **믿어도 되는지가 문제** → VLM 교차검증 + 코드 검산으로 신뢰도 판정 |
| 📚 [**md-rag-chatbot**](https://github.com/songwookun/md-rag-chatbot) | 개인 지식 RAG 챗봇 | AI가 "실측"이라 써둔 튜닝값을 **직접 다시 재고**, 언제 답을 보류할지 실험으로 결정 |
| 🧪 [**agent-eval-lab**](https://github.com/songwookun/agent-eval-lab) | AI 에이전트가 도구를 쓰며 작업 수행 | 같은 프롬프트에도 매번 다르게 움직인다 → **4축 평가 + OpenTelemetry trace**로 행동을 숫자로 측정 |

More: [used-deal-analyzer](https://github.com/songwookun/used-deal-analyzer) (큐 기반 비동기 + LLM 시세 분석) · [ai-corp](https://github.com/songwookun/ai-corp) (8명의 AI 직원 멀티 에이전트 시뮬레이터)

</details>

<details>
<summary><b>📊 Languages</b></summary>

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=songwookun&layout=compact&langs_count=4&hide=shaderlab,html,css,c%23,asp.net,shell&exclude_repo=Survivor,BoomDash_2025,NetworkOmok,DragonFlightImitation,Play_Room_Studio,C-Study,ProblemSol2024,Hybrid-application&theme=transparent&hide_border=true&title_color=7c3aed" alt="top languages" />

</details>
