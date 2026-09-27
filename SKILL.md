---
name: genpark-personal-intent-anticipator-skill
description: GenPark AI Agent Skill - Proactive zero-prompt intent anticipation, workspace context telemetry, active application state analysis, and predictive micro-action staging.
version: 1.0.0
category: Service
author: GenPark AI Ecosystem (@alphaparkinc)
---

# GenPark Personal Intent Anticipator Skill Specification

## Core Directives
1. Maintain strict user privacy boundaries; context telemetry must not capture sensitive passwords, credentials, or private keys.
2. Provide deterministic confidence intervals for all predictive actions.
3. Require explicit confirmation if an action impact is non-reversible.

## MCP Tools
- **track_workspace_context**: Captures and aggregates active desktop telemetry, cursor focus, open application states, and recent clipboard events.
- **predict_user_intent_graph**: Synthesizes probabilistic intention graphs predicting the user's next 3 likely objectives with confidence scores.
- **prefetch_intent_context**: Pre-retrieves relevant documents, schema definitions, and model parameters before explicit user instruction.
