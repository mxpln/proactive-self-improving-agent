# Proactive Self-Improving Agent (Translated to English)

Automatically Capture Experience · Safely Evolve · Record Trajectory

A self-improving skill designed specifically for OpenClaw agents, integrating the behavioral principles of proactive agents with the structured learning systems of self-improving agents.

## Features

- **7 Trigger Conditions**: Errors, Corrections, Knowledge Gaps, Better Practices, Feature Requests, Task Completion Reviews + Academic Scenario Extensions
- **Structured Logging**: Three-file system: LEARNINGS / ERRORS / FEATURE_REQUESTS
- **Experience Evolution**: Promotion Mechanism + Recursive Detection (≥3 automatic promotions) + Skill Extraction
- **Safety Barriers**: ADL drift prevention + VFM value-first scoring
- **Operational Logs**: JSONL-formatted CHANGELOG, machine-readable
- **Code of Conduct**: Perseverance, post-verification completion reporting, security reinforcement

## Installation

```bash
# OpenClaw
openclaw add https://github.com/mxpln/proactive-self-improving-agent

# Or manually
git clone https://github.com/mxpln/proactive-self-improving-agent.git ~/.openclaw/skills/proactive-self-improving-agent
```

## Usage

After installation, the agent automatically loads SKILL.md. Ensure the `.learnings/` directory exists in your workspace:

```bash
mkdir -p .learnings
```

See [SKILL.md](SKILL.md) for details.

## License

MIT
