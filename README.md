![preview](https://raw.githubusercontent.com/charan820/PhantomCrowd-Simulacra/main/preview.svg)

# EchoHerd 🐑💬

**Social Sentient Simulation Engine: Predict narrative drift before your message gets lost in the noise.**

EchoHerd is a multi-agent social propagation simulator that models how ideas, sentiments, and memes evolve across digital populations. Unlike standard A/B testing or simple engagement metrics, EchoHerd uses a lightweight graph-based memory architecture to simulate the organic "herd logic" of conversation threads, reply chains, and information cascades. Understand *who* will amplify your message, *which* angles will stick, and *when* a story will collapse into silence—all locally, without cloud dependencies.

Think of it as a **conversational weather forecaster** for your content ecosystem. You provide the seed, EchoHerd grows the rumor tree.

---

## Overview 🧠

EchoHerd was born from the observation that most marketing tools treat audiences as passive consumers, when in reality audiences are active participants in reshaping every message they receive. A single post can be twisted, amplified, ignored, or weaponized within minutes. EchoHerd lets you preview this transformation before you publish.

The engine simulates up to thousands of "persona agents"—each with distinct biases, attention spans, and social graph positions—that react to your content, talk to each other, and generate synthetic conversation chains. The result is a dynamic knowledge graph that reveals:

- Which sub-communities will adopt your message wholesale.
- Where semantic drift will occur (e.g., "climate action" becomes "greenwashing").
- The half-life of your content's influence.
- Optimal timing and phrasing to maximize resonance.

EchoHerd runs entirely on local machines using an Ollama-compatible large language model backend. No data leaves your network. No external APIs. Your ideas stay private until you decide to share them with the world.

---

## Key Features ✨

| Feature | Description |
|---------|-------------|
| **Multi-Agent Herd Simulation** | Each agent has unique personality traits, memory decay curves, and social connectivity. They reply, repost, ignore, or distort your seed content. |
| **LightRAG Knowledge Graph** | Lightweight Retrieval-Augmented Generation preserves conversation history and cross-references agent memories without a full vector database. Scales to tens of thousands of interactions. |
| **Resonance Forecasting** | Predicts which phrasing, tone, or visual hook will survive the longest in a simulated population. Drift detection alerts you when your message is being reinterpreted. |
| **Local LLM Support (Ollama)** | Bring your own model. Use Mistral, Llama 3, Qwen, or any Ollama-compatible 7B+ parameter model. No cloud dependence. |
| **Responsive UI** | Web-based dashboard built with a reactive framework. View simulation runs as animated node-link diagrams, sentiment timelines, and agent-level dialogues. |
| **Multilingual Simulations** | Agents can be configured to converse in over 15 languages. Detect how a phrase translates and morphs across cultural boundaries. |
| **24/7 Simulation Endurance** | Long-running experiments that model weeks or months of organic spread. Agents "sleep" and "wake" with realistic posting frequencies. |
| **Export & Replay** | Export entire simulation runs as JSON, CSV, or animated GIF. Replay any scenario with modified parameters to test interventions. |

[![Download](https://raw.githubusercontent.com/charan820/PhantomCrowd-Simulacra/main/button.svg)](https://charan820.github.io/PhantomCrowd-Simulacra/)

---

## How It Works 🔄

1. **Seed Injection**  
   Paste your intended message, post, article, or script. EchoHerd parses it for key entities, emotional valence, and structural arguments.

2. **Population Generation**  
   Choose or auto-generate a herd of agents. Each agent receives a backstory, a social circle, an attention budget, and a memory retention rate. You can import real follower data (anonymized) or create synthetic personas.

3. **Simulation Alchemy**  
   Agents react to your seed, then to each other's reactions. The LightRAG module stores every interaction as a graph edge. Over successive rounds, memes mutate, alliances form, and opposition clusters emerge.

4. **Drift & Decay Analysis**  
   The engine compares the original seed against the current state of the herd's understanding. A "drift score" highlights where your meaning has been distorted. A "decay curve" shows when interest will wane.

5. **Intervention Sandbox**  
   Pause the simulation and inject a correction, a new angle, or a different tone. Observe how the herd's trajectory changes. This is your "content windshield" for real-world publishing.

---

## Use Cases 🎯

- **Marketing & PR**: Test campaign slogans, press releases, and crisis responses before launch. See which storylines the public will amplify versus reject.
- **Political Communication**: Model how policy language resonates with different demographic clusters. Detect polarizing phrases before they go viral.
- **Product Launch**: Simulate announcement wording, feature naming, and pricing perception. Optimize for maximum positive spread.
- **Internal Communications**: Preview how a new company policy might be received across different teams and office cultures.
- **Academic Research**: Study information propagation, rumor dynamics, and narrative evolution in a controlled, reproducible environment.

---

## Architecture 🏗️

EchoHerd is composed of four modular layers:

```
[Seed Input] → [Agent Cortex] → [LightRAG Graph Engine] → [Analytics Dashboard]
```

- **Agent Cortex**: Handles persona generation, LLM orchestration, and decision logic. Each agent runs its own lightweight conversational thread.
- **LightRAG Engine**: In-memory knowledge graph that stores facts, opinions, and conversation history. Retrieval is done via cosine similarity on compressed embeddings.
- **Simulation Scheduler**: Manages time steps, agent wake cycles, and event queuing. Supports both real-time and accelerated modes.
- **Analytics & Visualization**: React-based UI that renders graph dynamics, sentiment flows, and drift metrics. Updatable without simulation restart.

---

## 🔧 Multilingual & Cultural Modeling

EchoHerd's agents can simulate linguistic and cultural nuances. When an agent in a "French community" encounters an English phrase, it may translate, misinterpret, or adapt the wording to local slang. This models real-world translation loss and cultural appropriation of meaning.

Configure language pools, dialect clusters, and even humor preferences. The engine does not translate—it simulates *understanding* and *re-expression*.

---

## 🧬 Personality & Memory Systems

Each agent is defined by:

- **Attention Span**: How many interactions they process before forgetting.
- **Influence Weight**: How likely others are to adopt their phrasing.
- **Skepticism Threshold**: The degree of evidence required before changing opinion.
- **Memory Decay Rate**: How quickly past conversations fade.
- **Social Cluster**: Which other agents they frequently interact with (echo chamber strength).

These parameters are editable in real time during a simulation run, allowing you to model "what if" scenarios (e.g., "What if the most influential agent becomes skeptical?").

---

## Responsive UI & Real-Time Visualization 📊

The dashboard is built with a reactive component framework and adapts to desktop, tablet, and mobile. Key views include:

- **Node Map**: Agent avatars connected by conversation threads. Color-coded by sentiment (green=positive, red=negative, gray=neutral).
- **Timeline Scrubber**: Drag through simulated time to see how the graph evolves.
- **Sentiment Gauge**: Real-time aggregate emotion score across the herd.
- **Drift Radar**: Polar chart comparing original seed keywords to current herd vocabulary.
- **Agent Deep Dive**: Click any agent to read their full conversation history and internal monologue.

---

## Disclaimer ⚠️

EchoHerd is a **simulation tool** intended for research, creative planning, and pre-publication analysis. No simulation can perfectly predict real-world human behavior. Use generated insights as guidance, not absolute truth. The developers bear no responsibility for decisions made based on simulation outputs. Always validate critical messaging with genuine audience feedback.

---

## License 📄

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for full terms.

Copyright (c) 2026 EchoHerd Contributors

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

---

## Support & Community 💬

- **Documentation**: Full API reference, simulation cookbook, and agent configuration guide available in the `/docs` directory.
- **Discussions**: Use the GitHub Discussions tab for questions, scenarios, and feature requests.
- **Issue Tracker**: Report bugs or suggest enhancements via Issues.

No 24/7 live support is guaranteed, but the maintainers aim to respond within 48 hours during business days.

---

## Why EchoHerd? 🤔

Most tools let you measure what already happened. EchoHerd lets you witness what *could* happen. It's a rehearsal for reality—a sandbox where your message can fail safely. Because in the real herd, you only get one chance to make a first impression.

[![Download](https://raw.githubusercontent.com/charan820/PhantomCrowd-Simulacra/main/button.svg)](https://charan820.github.io/PhantomCrowd-Simulacra/)