<div align="center">

<!-- ═══════════════════════════ HEADER ═══════════════════════════ -->

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00274C,50:1B4B7A,100:FFCB05&height=210&section=header&text=Rajdeep%20Mukherjee&fontSize=52&fontColor=FFFFFF&animation=fadeIn&fontAlignY=35&desc=World%20Models%20%C2%B7%20Reinforcement%20Learning%20%C2%B7%20Reliable%20Agents&descSize=18&descAlignY=55" width="100%"/>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&duration=3500&pause=800&color=FFCB05&center=true&vCenter=true&width=760&lines=I+build+agents+that+remember%2C+reason%2C+and+act.;And+I+study+why+they+fail.;World+models+%7C+RL+%7C+Multimodal+agents+%7C+Rigorous+evaluation;M.S.E.+CSE+%40+University+of+Michigan+%C2%B7+ex-AWS)](https://rajdeeepm.github.io/)

<br>

[![Portfolio](https://img.shields.io/badge/Portfolio-rajdeeepm.github.io-00274C?style=for-the-badge&logo=googlechrome&logoColor=white)](https://rajdeeepm.github.io/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Rajdeep_Mukherjee-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/rajdeep-mukherjee-cs752004/)
[![Google Scholar](https://img.shields.io/badge/Google_Scholar-Publications-4285F4?style=for-the-badge&logo=googlescholar&logoColor=white)](https://scholar.google.com/citations?user=q5MaIsUAAAAJ)
[![Email](https://img.shields.io/badge/Email-rajdeepm%40umich.edu-FFCB05?style=for-the-badge&logo=gmail&logoColor=00274C)](mailto:rajdeepm@umich.edu)

</div>

<br>

<!-- ═══════════════════════════ THE PET ═══════════════════════════ -->

<img src="assets/aircontrol-pet_animation.svg" width="100%" alt="The AirControl pet on patrol"/>

---

## Research thesis

> **An intelligent agent should do more than predict a plausible next action.** It should understand the situation it is in, remember what matters, anticipate how the world may change, and recover when its assumptions are wrong.

My work sits at the intersection of **reinforcement learning, multimodal AI, world models, memory, and computer-use agents** — building agents that remain reliable over long horizons and under distribution shift, not merely systems that look impressive on a benchmark.

<br>

## Research interests

<table>
<tr>
<td width="50%" valign="top">

### Deep learning & representation learning
Hierarchical/compositional representation learning; self-/unsupervised and multimodal learning; deep generative modeling for structured, reusable features; reliability under distribution shift.

</td>
<td width="50%" valign="top">

### Reinforcement learning for autonomous agents
Deep RL for sequential decision-making under partial observability (POMDPs); hierarchical/temporal abstraction and skill learning; model-based + offline RL; memory-augmented agents and exploration in sparse-reward environments.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### Strategic reasoning & multiagent systems
Computational game theory and learning in competitive/cooperative settings; opponent modeling; empirical game-theoretic analysis and agent-based simulation; incentive-aware decision-making with connections to market/mechanism design and AI safety in strategic environments.

</td>
<td width="50%" valign="top">

### Trustworthy NLP & language agents
Controllable and factual language generation; summarization, reasoning, and information extraction/argument mining; evaluation of reliability/safety (hallucination, bias); human-centered NLP for education and accessibility.

</td>
</tr>
</table>

<br>

## Right now

```python
class Rajdeep:
    def __init__(self):
        self.role       = "M.S.E. CSE @ University of Michigan"
        self.research   = ["world models for agentic systems",
                           "situational representation learning",
                           "uncertainty, reversibility & stakes-aware action",
                           "reliable computer-use agents"]
        self.exploring  = ["model-based RL", "memory", "post-training",
                           "evaluations that expose failures aggregate metrics hide"]
        self.previously = "AWS SageMaker AI — shipped a production agentic LLM system"
        self.building   = ["AirControl — the robot above is its pet",
                           "MealMap — a decision engine for what to eat next"]
        self.foundation = ["probability & statistics", "Bayesian ML",
                           "optimization", "mathematics minor"]
```

<br>

## What I optimize for

**Research that survives contact with reality.** Every system I build ships with an evaluation harness before it ships with a demo.

| Principle | In practice |
|-----------|-------------|
| **Measurable claims** | WebShop 45% → 52%, WebArena 15% → 24% — reported with baselines, not vibes |
| **Production rigor** | Agentic LLM system at AWS: 24x workflow speedup, 99%+ accuracy, architecture reused across adjacent teams |
| **Failure analysis first** | Preregistered constraints, failure taxonomies, confidence intervals — finding where agents break before claiming where they work |
| **Mathematical grounding** | Probability, Bayesian inference, and optimization as the substrate for modeling uncertainty and sequential decisions — not an afterthought |
| **Speed of iteration** | From idea to trained model to ablation on a single GPU; strong bias toward building over deliberating |

<br>

## Selected work

| Project | What I built / studied | Result |
|---------|------------------------|--------|
| **Memory-Augmented Multimodal Web Agent** | Screenshot + speech + reasoning + retrieval + browser-action pipeline with long-term vector memory | **WebShop 45% → 52%** · **WebArena 15% → 24%** |
| **AWS SageMaker Ground Truth** | Agentic LLM config generation, multi-model eval harness, synthetic data, PEFT, quantization, RAG tooling | **24x faster**, **99%+ accuracy** in internal eval |
| **Aero-LLM** | Distributed LLM framework for secure UAV communication and intelligent decision-making; led team, designed architecture, fine-tuned with SFT + RLHF | **IEEE ICCCN 2024** |
| **Net-GPT** | LLM-powered man-in-the-middle chatbot for UAV network security research; 95%+ next-packet prediction accuracy | **ACM/IEEE EdgeSP 2023** |

<br>

## Questions I keep returning to

```text
How should an agent represent the situation it is actually in?
Can a learned world model help it recover when the interface or task is unfamiliar?
What should long-term memory retain, revise, or forget?
When should an agent stop and ask, instead of guessing and acting?
How do we distinguish genuine reasoning from benchmark-shaped pattern matching?
What evaluations reveal failures that aggregate success rates conceal?
```

These questions also shape my writing series, **Diary of an ML Researcher**, where I turn deceptively simple AI questions into concrete research problems.

<br>

## Publications

1. **Aero-LLM: A Distributed Framework for Secure UAV Communication and Intelligent Decision-Making**
   <br>*IEEE International Conference on Computer Communications and Networks (ICCCN), 2024*

2. **Net-GPT: A LLM-Empowered Man-in-the-Middle Chatbot for Unmanned Aerial Vehicle**
   <br>*ACM/IEEE Symposium on Edge Computing — EdgeSP, 2023*

3. **Heterogeneous Generative Dataset for Unmanned Aerial Systems**
   <br>*IEEE MOST, 2023*

<div align="center">

[**See my publications on Google Scholar →**](https://scholar.google.com/citations?user=q5MaIsUAAAAJ)

</div>

<br>

## Tools I reach for

<div align="center">

**Research & ML**

<img src="https://skillicons.dev/icons?i=python,pytorch,tensorflow,sklearn,opencv&theme=dark" alt="ML tools"/>

<img src="https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat-square&logo=huggingface&logoColor=111111" alt="Hugging Face"/> <img src="https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white" alt="CUDA"/> <img src="https://img.shields.io/badge/Weights_&_Biases-FFBE00?style=flat-square&logo=weightsandbiases&logoColor=111111" alt="W&B"/> <img src="https://img.shields.io/badge/FAISS-0467DF?style=flat-square&logo=meta&logoColor=white" alt="FAISS"/> <img src="https://img.shields.io/badge/RAG-8A2BE2?style=flat-square" alt="RAG"/>

**Systems & performance**

<img src="https://skillicons.dev/icons?i=cpp,c,java,linux,bash,docker,kubernetes,aws,git&theme=dark" alt="systems tools"/>

**Web & product**

<img src="https://skillicons.dev/icons?i=ts,js,html,css,react,threejs,fastapi,flask&theme=dark" alt="web tools"/>

<img src="https://img.shields.io/badge/React_Three_Fiber-000000?style=flat-square&logo=react&logoColor=61DAFB" alt="React Three Fiber"/> <img src="https://img.shields.io/badge/REST_APIs-005571?style=flat-square" alt="REST APIs"/> <img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white" alt="SQL"/>

</div>

<br>

## Beyond the terminal

Swimmer, keyboard player, and aspiring long-distance triathlete.

Different arenas, same instinct: **pick a difficult problem, understand the system, and keep iterating.**

---

<div align="center">

### Let's build agents that still work when the benchmark ends.

Always happy to talk research, ambitious AI systems, open-source collaboration, or early-stage product ideas.

[![Email](https://img.shields.io/badge/Email-rajdeepm%40umich.edu-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:rajdeepm@umich.edu)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/rajdeep-mukherjee-cs752004/)
[![Portfolio](https://img.shields.io/badge/Portfolio-Visit-00274C?style=flat-square&logo=googlechrome&logoColor=white)](https://rajdeeepm.github.io/)
[![Scholar](https://img.shields.io/badge/Scholar-Read-4285F4?style=flat-square&logo=googlescholar&logoColor=white)](https://scholar.google.com/citations?user=q5MaIsUAAAAJ)

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:FFCB05,50:1B4B7A,100:00274C&height=120&section=footer" width="100%"/>

</div>
