# Adaptive Early‑Warning Agent for Cardiac Events

## Short description
Adaptive Early‑Warning Agent for Cardiac Events monitors wearable PPG/HRV, detects candidate anomalies locally, verifies suspected arrhythmias via an MCP ECG verification service, and escalates confirmed events to clinicians with encrypted, auditable provenance.

## Table of contents
- [Overview](#overview)
- [Quickstart (run locally)](#quickstart-run-locally)
- [Configuration (MCP + secrets)](#configuration-mcp--secrets)
- [Project structure](#project-structure)
- [CI / Tests](#ci--tests)
- [Demo & Judging checklist](#demo--judging-checklist)
- [Contributing](#contributing)
- [License](#license)

## Overview
This repository contains a minimal, reproducible prototype that demonstrates a full detection → verify → escalate loop:

- Edge simulator that replays wearable PPG/HRV streams and produces candidate anomaly events.
- Local detector that applies lightweight preprocessing and flags candidates.
- MCP client that calls a partner ECG verification endpoint (HTTP transport).
- Escalation flow that logs events, stores auditable metadata, and (optionally) notifies a clinician endpoint.

Goals: reduce false positives via verification, keep human‑in‑the‑loop for clinical decisions, and provide reproducible artifacts for judges.

## Quickstart (run locally)

### Prerequisites
- Node 18+ or Python 3.10+ (project contains both a small Python simulator and a Node microservice; pick one to run).
- git and a terminal (or use GitHub web UI to view files).
- Optional: Docker for containerized run.

### Clone (phone/web UI)
**Web UI:** open your repo page → Code → Download ZIP or use the GitHub mobile app to copy the repo URL.

**CLI (PC):**
```bash
git clone https://github.com/<your-username>/cardio-earlywarning-age.git
cd cardio-earlywarning-age
```

## Configuration (MCP + secrets)
*To be completed*

## Project structure
*To be completed*

## CI / Tests
*To be completed*

## Demo & Judging checklist
*To be completed*

## Contributing
*To be completed*

## License
*To be completed*
