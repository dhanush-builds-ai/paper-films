# Paper Films

Research papers, explained as short self-playing films for engineers.

**Watch:** https://dhanush-builds-ai.github.io/paper-films/

Each film is a single HTML page that plays on its own. It covers the problem, the core idea, how the method works step by step, the evidence, and how to use it. The wording is simplified, but the paper's methods and numbers are kept exactly as stated, and every caption cites the section or table it comes from.

## Films

| Film | Paper | Length |
|------|-------|--------|
| [AgentGarten: Code Worlds for Evolving Agents](https://dhanush-builds-ai.github.io/paper-films/agentgarten/) | arXiv 2610.12374 | 18 min |
| [SelfSearch: Reward-Free Search for Self-Improving Agents](https://dhanush-builds-ai.github.io/paper-films/selfsearch/) | arXiv 2609.37968 | 19 min |
| [Mistral 7B](https://dhanush-builds-ai.github.io/paper-films/mistral7b/) | arXiv 2310.06825 | 20 min |
| [LLaMA: Open and Efficient Foundation Language Models](https://dhanush-builds-ai.github.io/paper-films/llama/) | arXiv 2302.13971 | 21 min |
| [GLiNER2: Efficient Multi-Task Information Extraction](https://dhanush-builds-ai.github.io/paper-films/gliner2/) | arXiv 2507.18546 | 19 min |

Every film has the same eight chapters: Overview, The problem, The core idea, How it works, Evidence, Using it, The authors' thinking and Glossary. You can pause, jump between chapters, or play at up to 4× speed.

## Layout

```
index.html        home page
<film>/index.html one self-contained page per film
assets/           posters and card images
```

There is no build step. GitHub Pages serves the repository root as-is.

## Run locally

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000. Opening `index.html` directly from disk also works, but serving it matches how GitHub Pages loads the images.

## Credit

Each paper belongs to its authors; each film cites it.
