<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&color=0:1e1b4b,50:4f46e5,100:0ea5e9&height=170&section=header&text=Sri%20Edara&fontSize=50&fontColor=ffffff&fontAlignY=42&desc=AI%20Evaluation%20%C2%B7%20LLM%20Autograders%20%C2%B7%20Data%20Quality&descAlignY=68&descSize=20&animation=fadeIn" />

<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=19&duration=3200&pause=900&color=4F46E5&center=true&vCenter=true&width=620&lines=How+do+we+know+the+AI+is+right%3F;LLM+autograders+%26+rubrics;Human+%E2%86%94+LLM+judge+calibration;Evaluation+as+a+release+quality+gate" alt="Typing SVG" />

<p>
  <a href="https://substack.com/@sriedara1"><img src="https://img.shields.io/badge/Substack-FF6719?style=for-the-badge&logo=substack&logoColor=white" /></a>
  <img src="https://img.shields.io/badge/Dublin,_CA-111827?style=for-the-badge&logo=googlemaps&logoColor=white" />
  <img src="https://komarev.com/ghpvc/?username=edara-code&style=for-the-badge&color=4f46e5&label=Profile+Views" />
</p>

</div>

---

### 👩‍💻 About me

I'm working on evaluating AI systems and the data behind them: designing rubrics and evaluation sets, collecting and checking human labels, and comparing LLM autograders with human ratings to see where they can be relied on.
- 🎯 **Focus:** evaluating conversational AI, LLMs, and speech systems
- 💡 **Principle:** a metric is only useful if it predicts real-world quality and people trust it
- 🔁 **Approach:** measure → diagnose failures → fix → re-measure → gate the release
- ✍️ **Writing:** notes on evaluation and data quality on [Substack](https://substack.com/@sriedara1)

---

### 🧭 What I bring

| Area | What it involves |
|---|---|
| 🤖 **LLM autograders & rubrics** | Rubric design, evaluation set development, and calibrating an LLM autograder against human ratings |
| 📊 **Metrics that mean something** | Cohen's kappa for human–LLM agreement (including the kappa paradox), error rates, and checking that findings hold on larger, harder samples |
| 📚 **Grounded, factual responses** | Groundedness, citation accuracy, and hallucination rate for retrieval-based (RAG) answers |
| 🎙️ **Conversational & speech quality** | Intent, transcription, and speaker annotation, plus speech recognition accuracy |
| ✅ **Quality gates** | Golden sets, sampling audits, annotator scorecards, and CI quality gates (GitHub Actions) that block regressions before release |

---

### 🔬 Featured work: [annotation-eval-lab](https://github.com/edara-code/annotation-eval-lab)

An end-to-end lab for building trustworthy evaluation, from human annotation to automated grading and release gates.

| Layer | What it covers |
|---|---|
| **Human annotation** | Image, audio/voice, text, and video labeling with clear guidelines and QA checks |
| **Speech evaluation** | Comparing automatic transcripts with human ones (WER) |
| **LLM evaluation** | Rubric ratings, preference judgments, and a Claude autograder calibrated against human ratings with Cohen's kappa, then re-tested on harder prompts |
| **RAG evaluation** | Groundedness, citation accuracy, and hallucination rate |
| **Translation quality** | Human error annotation compared with automatic scores |
| **Quality framework** | Golden sets, sampling audits, annotator scorecards, and CI quality gates with GitHub Actions |
| **Red teaming** *(separate repo)* | Find failures, fix, re-scan, and lock in regression tests |

<a href="https://github.com/edara-code/annotation-eval-lab"><img src="https://img.shields.io/badge/View_project-4f46e5?style=for-the-badge&logo=github&logoColor=white" /></a>

<sub>Built mainly with Python and Label Studio.</sub>
