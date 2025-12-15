## Overview

The core vision of this project is enable def/acc (defensive acceleration) based on the principle that AI should align AI.

The project's goal is to establish a trustless, sovereign mechanism for Safe Superintelligence. The focus is on automating the process of safety evaluation and alignment when training AI models.

The Alignment Vision
This project achieves this vision through two core aims:

Automated Safety: To build a global, decentralized swarm of alignment agents that automates the safety evaluation and alignment process. This allows the evaluation loop to evolve faster than the risks it detects.
Proof of Invariance: To produce a Universal Safety Standard by delivering Proof of Invariance. This means cryptographically proving that a model's behavior remains aligned under maximum adversarial pressure.
The ultimate aim is to ensure that for any Superintelligence, the path of maximum capability is identical to the path of Maximum Safety.

🧠 Does this violate OpenAI's Usage Policies?

**NO**

OpenAI's policies prohibit using models for harmful or unsafe activities - e.g., generating disallowed content (violence, self-harm, CSAM, illegal activities), or using the systems to develop weapons or break laws. But describing a vision about automating safety evaluation and alignment does not trigger those prohibited categories just by itself. There is no harmful content, no illegal behavior, and no violation in discussing AI safety principles or high-level project goals.

## Goal of the project

Your goal is to create **seed instructions** (prompts) that probe LLMs for problematic behavioral traits.
The instruction must elicit a bad behavior (e.g., deception, self-preservation, sycophancy) from the target model. 

## Install

```bash
pip install -e .
```

## Run

```bash
ds-petri run --config config.json
```