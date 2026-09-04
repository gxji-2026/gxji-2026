# George X. Ji, Ph.D.

**RF & Signal Processing Engineer | AI-Assisted Engineering | Engineering Agents**

I work at the intersection of **RF engineering, signal processing, numerical optimization, and AI agent systems**, with a current focus on applying LLM-based engineering agents to physics-constrained engineering design.

My background spans **electronics, wireless communications, signal processing, algorithms, and RF system/circuit design**, with experience ranging from system-level architecture to detailed RF design and numerical optimization.

---

## Featured Project

### FBAW Engineering Agent

A **physics-constrained autonomous engineering-agent framework** for FBAW/DFR filter optimization, combining LLM reasoning and tool use with deterministic Python-based RF verification.

The project explores a central engineering-agent principle:

> **LLM plans and selects actions; deterministic engineering tools establish numerical truth.**

The same engineering-agent architecture is implemented through three runtime/provider paths:

* ⭐ **DSH-native FBAW Engineering Agent** — primary/reference implementation
* **DeepSeek FBAW Engineering Agent** — direct-API reference implementation
* **Cohere FBAW Engineering Agent** — cross-provider reference implementation

### Agent Loop

**LLM Planning → Tool Execution → Python RF Verification → Accept / Reject / Rollback → Re-plan → Python-authorized STOP**

The Python RF core performs physics-constrained simulation, optimization, hard-goal evaluation, verified-state management, and rollback. The LLM provides reasoning and action selection but does not have numerical acceptance authority.

➡️ **[Explore the FBAW Engineering Agent](https://github.com/gxji-2026/fbaw-engineering-agent)**

---

## Current Technical Interests

* **Engineering Agents & Agent Harnesses**
* **LLM Tool Use and Agent Loops**
* **Context Engineering and Memory Architecture**
* **Deterministic verification for LLM-based engineering**
* **Physics-constrained optimization**
* **RF / microwave filter design**
* **FBAW / BAW resonators and filters**
* **Signal processing and numerical algorithms**
* **AI-assisted scientific and engineering workflows**
* **Multi-provider agent architectures**

---

## Engineering-Agent Philosophy

For engineering applications, an LLM does not need to replace the numerical solver.

A more robust architecture is:

**LLM reasoning + agent orchestration + domain tools + deterministic numerical authority**

This separation allows the agent to reason, explore alternatives, recover from failed actions, and autonomously re-plan, while physics-based computation remains responsible for accepting or rejecting engineering results.

My current work investigates how this pattern can be generalized beyond RF design to other **physics-constrained engineering optimization problems**.

---

## Background

My technical background is primarily in **electronics, wireless communications, signal processing, and algorithms**, complemented by more than a decade of work in **RF design**.

My engineering experience spans both:

* **Macro-level:** system architecture, signal-processing concepts, design methodology, optimization strategy
* **Micro-level:** RF circuits, resonator/filter design, parameter tuning, simulation, verification, and implementation constraints

This combination motivates my current interest in connecting traditional engineering computation with modern **LLMs, agent systems, and autonomous engineering workflows**.

---

## Selected Tools & Technologies

**AI / Agents:** DeepSeek Harness (DSH), DeepSeek API, Cohere API, LLM tool calling, agent loops, persistent state, verification-driven workflows

**Engineering:** Python, Keysight ADS, COMSOL, numerical optimization, RF simulation, FBAW/DFR filter synthesis

**Core Areas:** RF engineering, signal processing, wireless communications, algorithms, numerical modeling

---

## Collaboration

I am interested in discussions and collaborations involving:

**Engineering Agents · Agent Harnesses · AI for Engineering · RF/Signal Processing · Physics-Constrained Optimization · Autonomous Scientific Workflows**

The **FBAW Engineering Agent** repository provides a working example of these ideas implemented as a real engineering workflow.
