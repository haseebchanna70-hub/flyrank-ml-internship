# Weekly Review Assistant (AI Agent Capstone)

An automated decision-support agent designed to ingest unstructured daily developer notes, extract completed tasks, identify operational blockers, and output structured weekly reports with priority recommendations.

## Target User & Core Job
* **For:** Developers, ML interns, and productivity-focused professionals.
* **Job to be Done:** Converts messy daily brain-dumps into executive-ready weekly review summaries without manual copy-pasting.

## Architecture
[Unstructured Daily Notes (.txt/.md)]
│
▼
[File Analysis / System Prompt Engine]
│
├── Rule Enforcer (Read-Only Guardrails)
├── Data Extractor (Done / Blockers / Next Priorities)
│
▼
[Structured Executive Review Report]
## Quickstart Setup
1. Clone this repository:
   ```bash
   git clone [https://github.com/haseebchanna70-hub/flyrank-capstone.git](https://github.com/haseebchanna70-hub/flyrank-capstone.git)
   cd flyrank-capstone
   
