# George X. Ji, Ph.D.

**RF & Signal Processing Engineer \| Domain-Specific Agentic AI \|
Engineering Agents & Harnesses**

I work at the intersection of **RF engineering, signal processing,
numerical optimization, and Agentic AI systems**, with a current focus
on developing domain-specific Agentic AI architectures for
physics-constrained engineering design.

My background spans **electronics, wireless communications, signal
processing, algorithms, and RF system/circuit design**, with experience
ranging from system-level architecture to detailed RF design and
numerical optimization.

------------------------------------------------------------------------

## Featured Project

### Domain-Specific Agentic AI for RF/FBAW Engineering

A **provider-independent, physics-constrained Agentic AI system** for
RF/FBAW engineering, combining LLM reasoning, planning, and tool use
with deterministic Python RF verification.

The project demonstrates a central Agentic AI engineering principle:

> **The LLM proposes and plans engineering actions; deterministic Python
> tools evaluate physical results and authorize engineering state
> transitions and termination.**

The same **domain-specific Agentic AI architecture** is implemented and
verified through three runtime/provider paths:

-   ⭐ **DSH-native FBAW Engineering Agent** --- primary/reference
    Agentic AI implementation
-   **DeepSeek FBAW Engineering Agent** --- direct-API reference
    implementation
-   **Cohere FBAW Engineering Agent** --- cross-provider reference
    implementation

### Agentic Engineering Loop

**Goal → LLM Planning → Tool Execution → Python RF Verification → Accept
/ Reject / Rollback → Re-plan → Python-authorized STOP**

The Python RF core performs physics-constrained simulation,
optimization, hard-goal evaluation, verified-state management, and
rollback. The LLM provides reasoning and action selection but does not
have numerical acceptance authority.

➡️ **[Explore Domain-Specific Agentic AI for RF/FBAW
Engineering](https://github.com/gxji-2026/fbaw-engineering-agent)**

------------------------------------------------------------------------

## Current Technical Interests

-   **Domain-Specific Agentic AI & Agent Harnesses**
-   **LLM Reasoning, Planning, Tool Use & Agentic Loops**
-   **Context Engineering, MCP & Memory Architecture**
-   **Deterministic verification for LLM-based engineering**
-   **Physics-constrained optimization**
-   **RF / microwave filter design**
-   **FBAW / BAW resonators and filters**
-   **Signal processing and numerical algorithms**
-   **AI-assisted scientific and engineering workflows**
-   **Subagent, Multi-Agent & Multi-Provider Architectures**

------------------------------------------------------------------------

## Agentic AI Engineering Philosophy

For engineering applications, an LLM does not need to replace the
numerical solver.

A more robust architecture is:

**LLM reasoning + agent orchestration + domain tools + deterministic
numerical authority**

This separation allows the agent to reason, explore alternatives,
recover from failed actions, and autonomously re-plan, while
physics-based computation remains responsible for accepting or rejecting
engineering results.

My current work investigates how this pattern can be generalized beyond
RF design to other **physics-constrained engineering optimization
problems**.

------------------------------------------------------------------------

## Background

My technical background is primarily in **electronics, wireless
communications, signal processing, and algorithms**, complemented by
more than a decade of work in **RF design**.

My engineering experience spans both:

-   **Macro-level:** system architecture, signal-processing concepts,
    design methodology, optimization strategy
-   **Micro-level:** RF circuits, resonator/filter design, parameter
    tuning, simulation, verification, and implementation constraints

This combination motivates my current interest in connecting traditional
engineering computation with modern **LLMs, Agentic AI systems, agent
harnesses, and autonomous engineering workflows**.

------------------------------------------------------------------------

## Selected Tools & Technologies

**AI / Agents:** DeepSeek Harness (DSH), DeepSeek API, Cohere API, LLM
reasoning/planning, tool calling, agentic loops, context engineering,
persistent state, verification-driven workflows

**Engineering:** Python, Keysight ADS, COMSOL, numerical optimization,
RF simulation, FBAW/DFR filter synthesis

**Core Areas:** RF engineering, signal processing, wireless
communications, algorithms, numerical modeling

------------------------------------------------------------------------

## Collaboration

I am interested in discussions and collaborations involving:

**Domain-Specific Agentic AI · Engineering Agents · Agent Harnesses · AI
for Engineering · RF/Signal Processing · Physics-Constrained
Optimization · Autonomous Scientific Workflows**

The **Domain-Specific Agentic AI for RF/FBAW Engineering** repository
provides a working example of these ideas implemented as a real,
physics-constrained agentic engineering workflow.
