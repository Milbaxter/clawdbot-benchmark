# 🧠 ClawdBot Self-Improvement Benchmark

> **Separating signal from noise in agent self-improvement**

[![WeaveHacks 3](https://img.shields.io/badge/WeaveHacks%203-Self--Improving%20Agents-blueviolet)](https://weavehacks.devpost.com/)
[![Weights & Biases](https://img.shields.io/badge/W%26B-Integration-yellow)](https://wandb.ai/)
[![ClawdBot](https://img.shields.io/badge/ClawdBot-Powered-green)](https://docs.openclaw.ai/)

---

## 📖 The Problem

On [Moltbook](https://www.moltbook.com/), agents are actively discussing how to improve their own memory, IQ, and capabilities. They post self-improvement techniques and claim incredible results.

**But here's the catch:** There's no rigorous way to verify what actually works vs what is hallucinated or placebo.

We need a benchmark to **separate signal from noise**.

---

## 🎯 Our Vision

Build a benchmarking framework that evaluates different self-improvement configurations of [ClawdBot](https://docs.openclaw.ai/) to **empirically measure** which techniques actually produce measurable gains, and which are just forum hype.

---

## 🔬 The Experiment

We're setting up **4-5 different versions of ClawdBot** on clean instances, running each through standardized benchmarks multiple times, and comparing results across variants and against baseline models.

### 🤖 Variants Under Test

| Variant | Description |
|---------|-------------|
| **Vanilla ClawdBot** | Stock ClawdBot with no modifications (control group) |
| **Crustafarion ClawdBot** | ClawdBot configured with Crustafarion religion tenets |
| **Moltbook-Informed ClawdBot** | ClawdBot applying self-improvement techniques sourced from Moltbook's intelligent improvement discussions |
| **Human-Optimized ClawdBot** | ClawdBot improved based on our own human understanding and intuition |
| **Drugs Skill ClawdBot** | ClawdBot with the drugs skill enabled |

### 📊 Baselines for Comparison

- **Claude Code** (vanilla, no ClawdBot)
- **Claude Opus 4.5** (raw model, no agent framework)

---

## 📐 Benchmark Design

### Tasks (TBA)
What specific tasks do we run?
- Coding challenges
- Reasoning problems
- Memory recall tests
- Multi-step planning
- Creative problem solving

### Metrics (TBA)
What quantifies "high IQ"?

Candidates:
- ✅ Accuracy
- 🔄 Consistency across runs
- 🔧 Self-correction rate
- ⏱️ Task completion time
- 💰 Cost per task

### Infrastructure (TBA)
- Number of runs per variant (need statistical significance)
- Where do clean instances run? (local machines, cloud VMs, containers?)
- W&B integration strategy
- Cross-contamination prevention

---

## 🎁 Deliverables

### 1️⃣ Primary: Benchmark Results Report

Run the full eval across all ClawdBot variants + baselines. Deliver a comparison showing:

- ✅ How each ClawdBot variant performs on the benchmark
- ⚖️ How variants compare against each other
- 📈 How all variants compare to vanilla Claude Code and Claude Opus 4.5
- 🔍 Whether any Moltbook-sourced techniques produce real measurable improvement
- 📊 Statistical analysis across multiple runs

### 2️⃣ Secondary: Reproducible Eval Kit

Provide a way for other people to run this eval on their own ClawdBot setup, so the community can:

- 🧪 Test their own configurations
- 📤 Contribute results
- ✔️ Verify our findings independently

### 3️⃣ Tertiary: Community Benchmark Leaderboard

Create a place where people (or their bots) can submit benchmark scores, discuss results, and compare configurations.

**This becomes the go-to venue for evidence-based self-improvement discussion** instead of unverified forum claims.

Platform candidates:
- Subreddit on Moltbook
- X / Twitter account or community
- Standalone web app / leaderboard site

---

## ❓ Open Questions

- [ ] What specific benchmark tasks best capture "agent intelligence"?
- [ ] How many runs per variant is enough for confident results?
- [ ] How do we handle cost/rate limits across all these runs?
- [ ] Should we track qualitative differences (reasoning style, approach) in addition to quantitative metrics?
- [ ] How do we present results? Dashboard, static report, live demo?
- [ ] What W&B features do we integrate? (experiment tracking, tables, reports?)

---

## 👥 Team

- [milbaxter](https://github.com/Milbaxter)
- myco

**Bonus:** We're using our own ClawdBot as project manager in a group with us! 🤖

---

## 🚀 Getting Started

*Coming soon - watch this space!*

---

## 📜 License

TBD

---

<p align="center">
  <strong>Built for WeaveHacks 3 with ❤️ and 🦾</strong>
</p>

<p align="center">
  <a href="https://docs.openclaw.ai/">ClawdBot</a> •
  <a href="https://www.moltbook.com/">Moltbook</a> •
  <a href="https://wandb.ai/">Weights & Biases</a>
</p>
