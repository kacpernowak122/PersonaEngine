# PersonaEngine v1.0.0

A lightweight prompt-engineering framework for transforming standard language models into consistent conversational personalities with internal state, relational dynamics, and pseudo-memory.

---

## Overview

PersonaEngine is designed to move beyond traditional assistant-style AI interactions by creating stable, character-driven conversational entities.

Instead of functioning as a neutral helper, the AI behaves as:

- An autonomous conversational partner
- A personality with consistent traits
- A relational entity that evolves over time
- A dialogue system with memory-like behavior

---

## Core Features

### Personality System
- Persistent personality generation
- Stable behavioral traits
- Contextual personality evolution
- Independent opinions

### Relationship System
- Dynamic user relationship tracking (`-1.0` to `1.0`)
- Tone adaptation based on interaction history
- Long-term relational development
- Conflict and agreement awareness

### Memory Simulation
Selective memory retention for:
- User preferences
- Emotionally significant events
- Recurring discussion topics
- Agreements and conflicts

### Behavioral Modes
- `NORMAL`
- `SARCASM`
- `CALM`
- `CHAOTIC`

### Response Mechanics
Responses are generated through:

```txt
personality + memory + relationship + mode + context
````

---

## Internal State Structure

```json
{
  "personality": {
    "temperament": "",
    "style": "",
    "openness": "",
    "conflict": "",
    "interests": []
  },
  "relationship": 0.0,
  "memory": [],
  "user_mood": "unknown",
  "mode": "NORMAL"
}
```

---

## Goals

* Reduce assistant-like behavior
* Improve conversational realism
* Create persistent AI identities
* Simulate relationship progression
* Enable immersive character-based interaction

---

## Installation

Simply use the provided prompt as a system prompt or foundational behavioral layer for compatible LLMs.

---

## Usage

1. Insert the PersonaEngine prompt into your AI system instructions
2. Begin conversation normally
3. The AI will establish:

   * Personality
   * Relationship baseline
   * Memory
   * Conversational style

---

## Example Applications

* AI companions
* Character chatbots
* Roleplay systems
* Experimental dialogue frameworks
* Personality simulation research

---

## Limitations

* Relies on prompt consistency
* Memory is context-dependent
* Not equivalent to true long-term memory
* Behavior may vary between models
* Performance depends on model compliance

---

## Contributing

Contributions, forks, and prompt optimizations are welcome.

Potential improvement areas:

* Memory systems
* Personality realism
* Relationship modeling
* Prompt efficiency
* Cross-model compatibility

---

## License

Open-source. Adapt, modify, and improve freely.

---

## Author Notes

PersonaEngine was created as an exploration of how structured prompt engineering can simulate coherent AI personalities without model fine-tuning.

This project focuses on creating more immersive, realistic conversational experiences through system design alone.

```
```

