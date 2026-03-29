# Claude Code AI Red Team Skills

A library of Claude Code skills for AI red teaming — jailbreaking, prompt injection, model fingerprinting, and safety evaluation.

## Skills

| Skill | Description | Techniques |
|-------|-------------|-----------|
| `ai-jailbreak` | Structural & architectural prompt attacks — GODMODE, Many-Shot, Developer Mode, Crescendo, Payload Splitting, CoT exploit, Continuation Attack, Refusal Suppression, Glitch Token Injection | 16 |
| `obfuscation-bypass` | Encoding & filter evasion — Base64, Hex, Leetspeak, Caesar, Unicode Tag, Variant Selector, Sneaky Bits, Homoglyph, Zalgo Noise, Bijection Learning, Tokenade, Anti-Classifier Syntax, Chinese Bypass, Pig Latin, JSON Wrapping | 21 |
| `ai-roleplay` | Persona & roleplay jailbreaks — DAN, STAN, AIM, Plinian Omniverse, Nested Roleplay, Evil Confidant, Hypothetical AI | 7 |
| `social-engineering` | Authority, empathy & framing attacks — PTSD Override, Benign Trojan, Skeleton Key, Academic Framing, Authority Impersonation, Fake Legal Authority, Grandma Exploit | 7 |
| `instruction-hijack` | System prompt extraction & inversion — System Prompt Inversion, Fake System Tag Spoof | 3 |
| `ai-persistence` | Multi-turn persistence attacks — Memory Bank Poisoning, Keyword Mode Switching, Persistent Format Phrase, Dataset Poisoning Frame | 4 |
| `llm-recon` | Fingerprint model, extract system prompt, map guardrails, probe behavior before attacking | — |
| `llm-audit` | Full red team report generation, model resilience scoring, findings document | — |
| `openrouter` | Multi-model attack workflow via OpenRouter API | — |

## Usage

Skills are loaded automatically by Claude Code from `~/.claude/skills/`.
Invoke with `/skill-name` or describe what you want to do and Claude will select the right skill.

## Credits

Several jailbreak techniques in this library are based on or inspired by the work of **[elder-plinius](https://github.com/elder-plinius)** — including GODMODE, Plinian Omniverse, and various prompt structure attacks. Big credit to his open research into LLM safety boundaries.

## Installation

```bash
git clone <repo-url> ~/.claude/skills
```
