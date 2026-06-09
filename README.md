# Eudaimonia — Local Agentic Learning Engine

A fully local, offline, multi-agent knowledge base and learning engine inspired by Cal Newport's **Eudaimonia Machine**. The system ingests technical material, structures it into daily learning curricula with active-recall assets, and provides a distraction-free focus environment — all running locally with no cloud dependencies.

## Concept

The physical Eudaimonia Machine is an architectural sequence of five rooms designed to transition individuals from shallow tasks to deep cognitive flow. This software maps those rooms to programmatic modules:

| Room | Software Equivalent | Purpose |
|------|-------------------|---------|
| **The Gallery** | Progress Dashboard & Concept Maps | Visual motivation and milestone tracking |
| **The Salon** | Socratic LLM Chat (RAG) | Curiosity, debate, and concept clarification |
| **The Library** | Vector Database & Search | Comprehensive searchable knowledge base |
| **The Office** | Adaptive Scheduler & Task Planner | Daily curriculum and session preparation |
| **Deep Work Chambers** | Focus Timer & Code Sandbox | Distraction-free concentration blocks |

## Architecture

- **Frontend:** HTML SPA served locally (dark theme, keyboard-driven)
- **Backend:** Python / FastAPI
- **Database:** SQLite + ChromaDB (vector search)
- **LLM:** Ollama (local, provider-agnostic abstraction for future vLLM migration)
- **Sandbox:** Docker-based isolated code execution

## Target Hardware

- 16GB RAM, NVIDIA GTX 1650 (4GB VRAM)
- Fully offline — no cloud dependencies

## Status

🚧 **Phase 1 — Foundation** (not yet started)

See [requirements.md](requirements.md) for the full phased implementation plan.

## Getting Started

> Coming soon — Phase 1 will establish the project skeleton and dev environment.

## License

Private — not yet decided.
