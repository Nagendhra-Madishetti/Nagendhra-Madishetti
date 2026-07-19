<div align="center">

![Nagendhra Madishetti](assets/banner.svg)

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&duration=2600&pause=700&color=E50914&center=true&vCenter=true&width=640&lines=I+build+memory+for+machines.;RAG+with+a+brain%3A+pip+install+ragbrain;Agents+that+remember+what+they+knew%2C+and+when.;I+also+find+the+bugs%3A+CVE-2026-48121)](https://github.com/Nagendhra-Madishetti/ragbrain)

</div>

## 🔴 NOW STREAMING

<table>
<tr>
<td width="55%" valign="top">

### RAGBrain · the bi-temporal RAG platform

Every AI agent today forgets. **RAGBrain remembers what it knew, and when it knew it** - and can prove both. Facts live on two time axes, corrections supersede instead of overwrite, and you can replay the system's beliefs at any past moment without later knowledge leaking in.

[![PyPI](https://img.shields.io/badge/pip_install-ragbrain-E50914?style=for-the-badge&logo=pypi&logoColor=white&labelColor=141414)](https://pypi.org/project/ragbrain/)
[![Live demo](https://img.shields.io/badge/▶_interactive_replay-live-E50914?style=for-the-badge&labelColor=141414)](https://nagendhra-madishetti.github.io/ragbrain/replay.html)

`100% on as-of questions` where vector RAG scores `0%` - measured, reproducible, content-hashed.

</td>
<td width="45%" valign="top">

[![RAGBrain](https://github-readme-stats.vercel.app/api/pin/?username=Nagendhra-Madishetti&repo=ragbrain&bg_color=141414&title_color=E50914&text_color=b3b3b3&icon_color=E50914&border_color=303030)](https://github.com/Nagendhra-Madishetti/ragbrain)

<img src="https://github.com/Nagendhra-Madishetti/ragbrain/raw/main/docs/media/replay-demo.gif" alt="System-time replay demo" width="100%">

</td>
</tr>
</table>

## 📺 TRENDING NOW

<div align="center">

[![open-design](https://github-readme-stats.vercel.app/api/pin/?username=Nagendhra-Madishetti&repo=open-design&bg_color=141414&title_color=E50914&text_color=b3b3b3&icon_color=E50914&border_color=303030)](https://github.com/Nagendhra-Madishetti/open-design)
[![memory-bank](https://github-readme-stats.vercel.app/api/pin/?username=Nagendhra-Madishetti&repo=memory-bank&bg_color=141414&title_color=E50914&text_color=b3b3b3&icon_color=E50914&border_color=303030)](https://github.com/Nagendhra-Madishetti/memory-bank)

[![Immortal](https://github-readme-stats.vercel.app/api/pin/?username=Nagendhra-Madishetti&repo=Immortal&bg_color=141414&title_color=E50914&text_color=b3b3b3&icon_color=E50914&border_color=303030)](https://github.com/Nagendhra-Madishetti/Immortal)
[![mlflow](https://github-readme-stats.vercel.app/api/pin/?username=Nagendhra-Madishetti&repo=mlflow&bg_color=141414&title_color=E50914&text_color=b3b3b3&icon_color=E50914&border_color=303030)](https://github.com/Nagendhra-Madishetti/mlflow)

</div>

## 🎬 CONTINUE WATCHING

| | Episode | Progress |
|---|---|---|
| ✅ | **RAGBrain v0.1.0** shipped to PyPI with CI-enforced replay invariant | `██████████` 100% |
| ▶️ | **Launch season**: benchmark story, interactive demo, community posts | `███████░░░` 70% |
| 🔜 | **Next episode**: learned memory operations - fine-tuned extraction and consolidation | `██░░░░░░░░` 20% |

## 🍿 MY LIST · the modern AI infra stack

<div align="center">

[![Stack](https://skillicons.dev/icons?i=python,pytorch,fastapi,docker,kubernetes,redis,neo4j,postgres,react,nextjs,ts,tailwind,gcp,aws,githubactions,linux&perline=8&theme=dark)](https://github.com/Nagendhra-Madishetti/ragbrain)

`RAG pipelines` · `temporal knowledge graphs` · `vector search` · `agent memory` · `LLM orchestration` · `evaluation at scale` · `self-hosted inference`

</div>

## 🏆 CRITICS' ACCLAIM

- 🛡️ **CVE-2026-48121** - found and reported a NoSQL injection enabling cross-tenant data access in LangGraph's memory checkpointer (`langchain-ai/langgraphjs`, credited reporter)
- 🎨 **Open Design** - collaborator and maintainer on [nexu-io/open-design](https://github.com/nexu-io/open-design), 465 commits of feature work across 136 branches
- 🧠 **RAGBrain** - the only RAG platform in its benchmark that answers "what did we believe last March" and proves it
- 🎓 MS in Computer Science, University at Albany, SUNY

## 📼 PREVIOUSLY ON @Nagendhra-web

My earlier account (now retired) earned its badges the hard way:

`🤠 Quickdraw` · `🦈 Pull Shark ×2` · `👥 Pair Extraordinaire` · `🌟 Starstruck`

## 📊 RATINGS

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=Nagendhra-Madishetti&show_icons=true&bg_color=141414&title_color=E50914&text_color=ffffff&icon_color=E50914&border_color=303030&hide_rank=false" alt="GitHub stats" height="165">
<img src="https://streak-stats.demolab.com?user=Nagendhra-Madishetti&background=141414&ring=E50914&fire=E50914&currStreakLabel=E50914&sideLabels=ffffff&sideNums=ffffff&currStreakNum=ffffff&dates=b3b3b3&border=303030" alt="Streak" height="165">

</div>

## 🎞️ BEHIND THE SCENES

<details>
<summary><b>🧠 The RAGBrain story: why bi-temporal memory</b></summary>
<br>

Ask any RAG system "where is Acme headquartered?" and it answers. Ask "where was it headquartered in 2020?" and vector RAG fails. Ask "what did we believe in 2021, before the 2022 correction arrived?" and everything fails - except a bi-temporal ledger.

RAGBrain stamps every fact with two independent time axes: when it was true in the world, and when the system learned it. Corrections expire old facts and stamp what superseded them - nothing is ever silently overwritten. That makes answers auditable: every claim carries citations, validity windows, and confidence labels, and a CI-enforced invariant guarantees that replaying the past never leaks later knowledge backward.

Try it: [the interactive replay](https://nagendhra-madishetti.github.io/ragbrain/replay.html) · `pip install ragbrain`

</details>

<details>
<summary><b>🛡️ The CVE story: breaking agent memory to make it safer</b></summary>
<br>

While building memory systems I audit them too. In LangGraph's MongoDB checkpointer I found a NoSQL parameter injection that allowed cross-tenant data access - one agent's memory readable from another tenant's session. Reported responsibly, fixed by the maintainers, published as CVE-2026-48121 with reporter credit.

Memory layers hold the most sensitive data an agent has. They deserve adversarial attention.

</details>

<details>
<summary><b>🎨 The Open Design work</b></summary>
<br>

Open Design is a local-first, open-source design platform (19 skills, 71 brand-grade design systems). I contribute as a collaborator and maintainer: 465 commits across 136 working branches - features like the critique theater pipeline, e2e automation suites, and preview infrastructure.

</details>

## 📬 GET IN TOUCH

<div align="center">

[![Email](https://img.shields.io/badge/nagendhra.madishetti24@gmail.com-141414?style=for-the-badge&logo=gmail&logoColor=E50914)](mailto:nagendhra.madishetti24@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-141414?style=for-the-badge&logo=linkedin&logoColor=E50914)](https://www.linkedin.com/in/nagendhramadishetti/)
[![PyPI](https://img.shields.io/badge/PyPI_·_ragbrain-141414?style=for-the-badge&logo=pypi&logoColor=E50914)](https://pypi.org/project/ragbrain/)

<sub>Are you still watching? · New York, NY · he/him</sub>

</div>
