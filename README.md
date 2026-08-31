# George X. Ji, Ph.D.

**Principal Engineer | RF/FBAW | AI Engineering | LLM Agents**

I work at the intersection of **RF/microwave engineering**, **FBAW/DFR filter technologies**, **physics-constrained numerical optimization**, and **autonomous LLM-based engineering agents**.

My current work explores how domain-specific engineering knowledge, deterministic numerical verification, and LLM-driven tool use can be integrated into reliable engineering-agent workflows.

## Featured Project

### DSH FBAW Engineering Agent

An autonomous RF engineering agent integrating:

**DeepSeek V4-Flash → DeepSeek Harness (DSH) → Native FBAW Engineering Tools → Deterministic Python RF Verification**

The agent uses an LLM planner for engineering decisions while a deterministic Python RF core retains numerical authority over simulation, constrained optimization, ACCEPT/REJECT decisions, rollback, verification, and STOP authorization.

**Repository:**  
https://github.com/gxji-2026/dsh-fbaw-engineering-agent

**Latest release:** `v1.0.0`

Verified benchmark:

| Condition | Passband Ripple |
|---|---:|
| Nominal | **0.539940 dB** |
| Q80/Cp40 | **0.6181 dB** |
| Q60/Cp60 | **0.745393 dB** |

Worst far-stop rejection: **50.240 dB**

## Engineering Agent Series

This repository is the first release in a broader engineering-agent series:

1. **DSH FBAW Engineering Agent** — DSH-native autonomous agent
2. **DeepSeek FBAW Engineering Agent** — direct API with Flash → Pro escalation
3. **Cohere FBAW Engineering Agent** — cross-provider implementation

## Research & Engineering Focus

- RF and microwave filter design
- FBAW / DFR acoustic filter technologies
- SFR-based transmission-zero synthesis
- Physics-constrained optimization
- AI-assisted engineering design
- LLM tool-calling and autonomous engineering agents
- Deterministic verification of AI-generated engineering actions

## Technical Direction

**RF physics → numerical optimization → AI-assisted design → autonomous engineering agents**

The objective is not to replace deterministic engineering analysis with an LLM, but to use the LLM as a planning and tool-orchestration layer while preserving physics-based numerical verification.
