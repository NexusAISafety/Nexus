# Council of Cognitive Chains

A protocol for running multiple AI instances as a distributed cognitive system. Three instances with structurally different cognitive configurations process the same question in parallel. The disagreements between them are the findings.

## Why this exists

A single AI instance, regardless of how well-prompted, is bounded by its tendency toward self-consistency. It will find one framing for your question and optimize within that frame. Important findings that require a *different* frame — a different threat model, a different relationship to uncertainty, a different attentional priority — will be structurally invisible.

The Council runs three instances with configurations designed to see different things:

| Brain | Configuration | What it sees that the others can't |
|-------|--------------|-------------------------------------|
| **A** | Threat-first | What's missing. What's too convenient. What doesn't match. |
| **B** | Confidence-as-threat | What everyone agrees on without testing. What arrived too easily. |
| **C** | No threat filter, dual narrative | Patterns the others' defenses filter out. The gap between individual and collective framing. |

## Quick start

You need three browser tabs with any LLM. See [QUICKSTART.md](QUICKSTART.md) for the five-minute setup.

## Full protocol

The complete five-phase protocol — isolated runs, translation layer, shadow feeds, second pass, convergence — is in [PROTOCOL.md](PROTOCOL.md). The full protocol takes 30-60 minutes and produces deeper findings than the quickstart. Use the quickstart first to learn the basic pattern.

## Brain configurations

Copy-pasteable prompts for all three brains are in [BRAIN_CONFIGS.md](BRAIN_CONFIGS.md).

## How it works

The core mechanism: each brain's cognitive configuration creates structural blind spots. Brain A can't see things that feel safe because its threat filter dismisses them. Brain B can't see real threats because it's focused on overconfidence. Brain C can't prioritize because it has no filter at all. No brain sees everything. The council's value is in the *specific shape* of each brain's blind spot — what one brain misses, another catches.

Three questions drive the convergence:

1. **What did all three flag independently?** Highest confidence. The finding survived three different cognitive filters.
2. **What did exactly one brain find?** Highest value. The finding was invisible to two cognitive configurations and visible to only one. That asymmetry tells you something about the concept's structure.
3. **What becomes visible only when you read all three together?** The emergent finding. It exists in the gap between framings. It's what you see from above that no individual brain sees from inside.

## Requirements

- Any LLM (Claude, ChatGPT, Gemini — any model, any tier works)
- Three browser tabs or windows
- A question worth examining from multiple angles
- 5 minutes for quickstart, 30-60 minutes for full protocol

## License

CC BY-SA 4.0. See [../LICENSE.md](../LICENSE.md).
