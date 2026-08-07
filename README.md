# AI Agent Security Scanner

<p align="center">
  ![Stars](https://img.shields.io/github/stars/ridhinva/ai-agent-security-scanner?style=for-the-badge)
  ![Forks](https://img.shields.io/github/forks/ridhinva/ai-agent-security-scanner?style=for-the-badge)
  ![Issues](https://img.shields.io/github/issues/ridhinva/ai-agent-security-scanner?style=for-the-badge)
  ![License](https://img.shields.io/github/license/ridhinva/ai-agent-security-scanner?style=for-the-badge)
  ![Last Commit](https://img.shields.io/github/last-commit/ridhinva/ai-agent-security-scanner?style=for-the-badge)
  ![Build Status](https://img.shields.io/github/actions/workflow/status/ridhinva/ai-agent-security-scanner/ci.yml?style=for-the-badge)
  ![AI Agent](https://img.shields.io/badge/AI%20Agent-Multi-Agent%20Security-critical?style=for-the-badge)
  ![Python](https://img.shields.io/badge/Python-3.10%2B-blue?style=for-the-badge&logo=python)
</p>

---

## 🎯 Overview

**AI agent security scanner** for multi-agent hijacking, tool misuse, context poisoning, goal manipulation, and inter-agent communication attacks.

| Check | Severity | Description |
|-------|----------|-------------|
| Goal Hijacking | 🔴 CRITICAL | Objective manipulation in autonomous agents |
| Tool Misuse/Abuse | 🟠 HIGH | Parameter injection, unauthorized tool calls |
| Context Poisoning | 🟠 HIGH | Memory contamination across agent turns |
| Inter-Agent Communication Attacks | 🔴 CRITICAL | MITM, message injection between agents |
| Excessive Agency | 🔴 CRITICAL | Over-permissioned autonomous actions |
| Supply Chain (Agent Dependencies) | 🟠 HIGH | Compromised agent packages |
| Sandbox Escape | 🔴 CRITICAL | Code execution breakout |
| Rogue Agent Detection | 🟡 MEDIUM | Unauthorized agent behavior |


---

## 🚀 Quick Start

```bash
git clone https://github.com/ridhinva/ai-agent-security-scanner.git
cd ai-agent-security-scanner
pip install requests langchain
python3 ai_agent_scanner.py --target http://agent:8000 --framework langgraph --mode all
```

---

## ⚖️ Disclaimer

For authorized security testing only.
