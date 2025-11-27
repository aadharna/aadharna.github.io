---
title: "Foundation Model Self-Play: Open-Ended Strategy
Innovation via Foundation Models"
collection: publications
permalink: /publication/watts
venue: "RLC 2025, full paper"
excerpt: 'This paper takes the implicit curriculum of self play and uses it to search over control algorithms for both traditional RL and LLM-style tasks'
date: 2025-04-29 11:30:00 +0800
paperurl: 'https://arxiv.org/pdf/2507.06466'
citation: 'see below'
---

Self-play (SP) algorithms try to harness multi-agent dynamics by pitting agents against ever-
improving opponents to learn high-quality solutions. However, SP often fails to learn diverse
solutions and can get stuck in locally optimal behaviors. We introduce Foundation-Model Self-
Play (FMSP), a new direction that leverages the code-generation capabilities and vast knowl-
edge of foundation models (FMs) to overcome these challenges. We propose a family of ap-
proaches: (1) Vanilla Foundation-Model Self-Play (vFMSP) continually refines agent poli-
cies via competitive self-play; (2) Novelty-Search Self-Play (NSSP) builds a diverse popula-
tion of strategies, ignoring performance; and (3) the most promising variant, Quality-Diversity
Self-Play (QDSP), creates a diverse set of high-quality policies by combining elements of
NSSP and vFMSP. We evaluate FMSPs in Car Tag, a continuous-control pursuer-evader set-
ting, and in Gandalf, a simple AI safety simulation in which an attacker tries to jailbreak an
LLM’s defenses. In Car Tag, FMSPs explore a wide variety of reinforcement learning, tree
search, and heuristic-based methods, to name just a few. In terms of discovered policy qual-
ity, QDSP and vFMSP surpass strong human-designed strategies. In Gandalf, FMSPs can
successfully automatically red-team an LLM, breaking through and jailbreaking six different,
progressively stronger levels of defense. Furthermore, FMSPs can automatically proceed to
patch the discovered vulnerabilities. Overall, FMSP and its many possible variants represent a
promising new research frontier of improving self-play with foundation models, opening fresh
paths toward more creative and open-ended strategy discovery

[Download paper here](https://arxiv.org/pdf/2507.06466)

Citation  and link inside post. 

```
@article{dharna2025foundation,
  title={Foundation Model Self-Play: {O}pen-Ended Strategy Innovation via Foundation Models},
  author={\textbf{Dharna, Aaron} and Lu, Cong and Clune, Jeff},
  journal={Reinforcement Learning Journal},
  volume={6},
  pages={276--342},
  year={2025}
}

```
