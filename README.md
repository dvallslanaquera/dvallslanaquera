<h3 align="center">Hola, this is David's repo</h3>
<p align="center">Senior AI/ML Engineer based in Tokyo, building with LLMs.</p>

<p align="center">
  <a href="https://www.linkedin.com/in/david-valls">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHBhdGggZmlsbD0id2hpdGUiIGQ9Ik0yMC40NSAyMC40NWgtMy41NnYtNS41N2MwLTEuMzMtLjAyLTMuMDQtMS44NS0zLjA0LTEuODUgMC0yLjE0IDEuNDUtMi4xNCAyLjk0djUuNjdIOS4zNFY5aDMuNDJ2MS41NmguMDVjLjQ4LS45IDEuNjQtMS44NSAzLjM3LTEuODUgMy42IDAgNC4yNyAyLjM3IDQuMjcgNS40NnY2LjI4ek01LjM0IDcuNDNhMi4wNiAyLjA2IDAgMSAxIDAtNC4xMiAyLjA2IDIuMDYgMCAwIDEgMCA0LjEyek03LjEyIDIwLjQ1SDMuNTVWOWgzLjU3djExLjQ1ek0yMi4yMiAwSDEuNzdDLjc5IDAgMCAuNzcgMCAxLjcydjIwLjU2QzAgMjMuMjMuNzkgMjQgMS43NyAyNGgyMC40NWMuOTggMCAxLjc4LS43NyAxLjc4LTEuNzJWMS43MkMyNCAuNzcgMjMuMiAwIDIyLjIyIDB6Ii8%2BPC9zdmc%2B&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="https://zenn.dev/davidvl">
    <img src="https://img.shields.io/badge/Zenn-3EA8FF?style=for-the-badge&logo=zenn&logoColor=white" alt="Zenn"/>
  </a>
  <a href="https://x.com/Standby_00">
    <img src="https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white" alt="X"/>
  </a>
  <a href="https://leetcode.com/u/Standby_00/">
  <img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" alt="LeetCode"/>
  </a>
</p>

AI Platform/MLOps engineer in Tokyo, about 10 years in. Currently deep in LLMOps, RAG and multi-agent systems. Spanish by blood, Tokyo resident by choice, bilingual in Japanese (N1) because quitting wasn't an option.

My favorite proverb: "If you want to go fast, go alone. If you want to go far, go together". Strong teams always win.

My philosophy as a MLOps Engineer:  I'd rather build a robust system that survives regressions and drifts, than one that just looks good in a demo and a Power Point.

When I'm not shipping RAG pipelines, I'm at the gym, at the piano, or being supervised by two kittens who consider my keyboard theirs.

---

### Project #1: [SkinGraph](https://github.com/dvallslanaquera/skingraph)

Checking whether a skincare product is safe or not during pregnancy or when a skin condition is present can be time consuming and confusing.

SkinGraph reads a photo of any skincare label and returns a bilingual, safety-checked recommendation. A LangGraph pipeline routes most images through Gemini Flash and falls back to Pro only when confidence drops, then grounds the extracted ingredients against a Qdrant registry using multilingual-e5-small embeddings. Safety conflicts are resolved by rules.


<p align="center">
  <video src="GITHUB_ATTACHMENT_URL" width="700" controls muted></video>
</p>
