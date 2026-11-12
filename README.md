# Umang Agarwal

Software Development Engineer at Amazon India and independent AI safety researcher, working on monitoring of AI
agents, emotion probes, and model diffing. Website: [demoiverrakada.github.io](https://demoiverrakada.github.io)

## Current work

- **Do AI reviewers really judge independently?** At Apart's AI Collusion Research Sprint I tested whether an AI loan
  reviewer told to judge independently is swayed by a colleague's note, and built a re-run check that caught all 6
  swayed decisions (an AI monitor reading the transcript caught 1).
  [LessWrong post](https://www.lesswrong.com/posts/m76ygTSPhbGZ8wxpr/tracing-information-flow-to-check-whether-ai-reviewers-are) ·
  [Apart report](https://apartresearch.com/project/crosschecking-ai-agents-decisions-did-they-depend-on-another-agents-work-7fqz)
- **Emotion probes as a deception signal (in progress).** Reproduced Hollowell (2026)'s Gemma 2 emotion vectors exactly;
  so far the probes mostly mirror what the model's words already say. Details on my
  [website](https://demoiverrakada.github.io/#projects).
- **[Model diffing under dilution](https://github.com/demoiverrakada/diffing-dilution):** four diffing tools on 12
  diluted Qwen3-1.7B fine-tunes; code and raw outputs.

## Reproductions (paper + code)

- [Grokking](https://github.com/demoiverrakada/grokking-repro) (Nanda et al., 2023)
- [Refusal is mediated by a single direction](https://github.com/demoiverrakada/refusal-repro) (Arditi et al., 2024)
- [Toy models of superposition + SAEs](https://github.com/demoiverrakada/toy-models-of-superposition) (Elhage et al., 2022)
- [Induction heads in GPT-2 small](https://github.com/demoiverrakada/mech-interp-induction-heads) (Olsson et al., 2022)

## Earlier work

- [VeriTraceMix](https://github.com/demoiverrakada/VeriTraceMix): ProVerif proofs of 14 security goals for the voting
  protocol behind the e-voting system used in IIT Delhi elections (about 3,000 voters, April 2026).
- [Finetune trace: behaviour or topic?](https://github.com/demoiverrakada/finetune-trace-behavior), my MATS 12.0
  application project (Sep 2026); main result negative.
- [Sandbagging evals](https://github.com/demoiverrakada/sandbagging-evals),
  [Blindfolded expert iteration](https://github.com/demoiverrakada/blindfolded-expert-iteration) (paused),
  [LLM fine-tuning lab](https://github.com/demoiverrakada/llm-finetuning-lab).
