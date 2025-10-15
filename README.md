# ai-agent-eval-blueprint
An example to use an eval feature of AI agent evaluation - LLM-as-judge exampel

## Quickstart

### 1) Prerequisites
- Python 3.10+
- An API key for your LLM provider(s) (e.g., `ANTHROPIC_API_KEY`, `OPENAI_API_KEY`)
- Optional: Docker (for isolated runs)

### 2) Setup
```bash
git clone https://github.com/<your-org>/agentic-commerce-evals.git
cd agentic-commerce-evals

# choose one dependency style
pip install -r requirements.txt
# or:
# pipx install uv && uv sync

cp .env.example .env            # add your API keys
