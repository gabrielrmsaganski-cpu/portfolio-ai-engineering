# Portfolio Architecture

## Intent

The portfolio is structured as an ecosystem, not as isolated demo repos. Each repository represents a major engineering capability area and together they show consistent thinking across product architecture, automation, AI integration, and operations.

## Portfolio Map

```mermaid
flowchart TD
    A[GitHub Pages Portfolio] --> B[Legal Intelligence]
    A --> C[Fintech Operations]
    A --> D[Automation Systems]
    A --> E[AI Systems]
    A --> F[Fintech Execution]

    B --> B1[LAW Juridico Monitor]
    B --> B2[LAW Hub Legacy Workflow]

    C --> C1[OWN API Integrations]
    C --> C2[Webhook Inbox]
    C --> C3[Settlement and Transaction Sync]
    C --> C4[AI Copilot]

    D --> D1[AION Signal Factory]
    D --> D2[Task Schedulers]
    D --> D3[Windows Runbooks]
    D --> D4[Bedrock Project Builders]

    E --> E1[NexusGraph Connectors]
    E --> E2[LLM Causal Inference]
    E --> E3[Telegram Delivery]

    F --> F1[DerivNovo]
    F --> F2[Aion Flux]
    F --> F3[Risk and Execution Controls]
```

## Design Principles

- Favor systems with real boundaries: API, UI, scheduler, worker, persistence, and integrations
- Show applied AI as one component inside a broader product architecture
- Prefer operational maturity over experimental novelty
- Preserve original engineering intent while curating public-safe source

## Evidence Base

The repository selection and descriptions are grounded in the local scan documented in [docs/local-project-scan.md](C:\Users\Administrator\gabriel-saganski\portfolio-ai-engineering\docs\local-project-scan.md).

## Delivery Pattern

Each curated repository includes:

- `README.md` for recruiter-facing context
- `architecture.md` for engineering depth
- `docs/` for source lineage and operational notes
- `screenshots/` for UI captures or visual system maps

## Publishing Model

These repos are prepared for manual push to `github.com/gabrielrmsaganski-cpu/*` and for the public site at `https://gabrielrmsaganski-cpu.github.io/`.
