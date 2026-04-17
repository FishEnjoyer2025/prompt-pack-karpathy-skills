# Multi-Agent LLM Pipeline Hardening Prompt Pack

25 battle-tested prompts for Python developers who need to debug, test, and secure multi-agent LLM pipelines before they hit production. Each prompt is drop-in ready and covers the full hardening lifecycle from failure discovery through deployment safety. Built for engineers shipping real systems, not toy demos.

## 🛒 Buy now — $27

**[→ Checkout via Stripe](https://buy.stripe.com/9B6eVefxe2DDb7M14ldfG0d)**

## What's inside

- 25 structured prompts across 7 critical categories: agent auditing, failure discovery, testing, prompt hardening, production readiness, architecture review, and security
- Covers cascade failure mapping, hallucination surface analysis, prompt injection defense, and silent failure detection
- Includes LLM-as-judge prompt construction, regression test design, and adversarial input generation
- Production-focused prompts for cost overrun prevention, graceful degradation planning, and observability design
- Works with any LLM provider (OpenAI, Anthropic, Gemini) and any orchestration framework (LangChain, LlamaIndex, custom)

## Preview

```
## Multi-Agent LLM Pipeline Hardening Prompt Pack

---

### GROUP 1: AGENT BEHAVIOR AUDITING

**Prompt 1 — Trace Unexpected Agent Decisions**
```
I have a multi-agent LLM pipeline where agent [AGENT_NAME] is making unexpected decisions at step [STEP]. Here is the full prompt it receives: [PASTE_PROMPT]. Here is the output it produced: [PASTE_OUTPUT]. Identify every ambiguity, missing constraint, or conflicting instruction in the prompt that could produce this behavior. List each issue with the exact quote from the prompt that causes it and a corrected replacement.
```

**Prompt 2 — Agent Responsibility Overlap Detection**
```
Below are the system prompts for each agent in my pipeline. Identify any overlapping responsibilities, contradictory instructions, or gaps where no agent owns a task. For each conflict, name the agents involved, quote the conflicting instructions, and recommend which agent should own the responsibility and why.

Agent prompts:
[AGENT_1_NAME]: [PROMPT]
[AGENT_2_NAME]: [PROMPT]
[AGENT_3_NAME]: [PROMPT]
```

**Prompt 3 — Output Schema Enforcement Review**
```
This agent is supposed to return structured output matching this schema: [PASTE_SCHEMA]. Here are three real outputs it produced: [OUTPUT_1], [OUTPUT_2], [OUTPUT_3]. For each output: (1) state whether it matches the schema, (2) list every deviation with the field name and actual vs expected value, (3) suggest the minimal prompt change to prevent that deviation. Do not suggest schema changes.
```

**Prompt 4 — Chain-of-Thought Faithfulness Check**
```
This agent uses chain-of-thought reasoning before producing a final answer. Here is its full output including reasoning: [PASTE_OUTPUT]. Evaluate whether the final answer actually follows from the stated reasoning. Identify any steps where the conclusion jumps, contradicts earlier reasoning, or introduces information not present in the reasoning chain. Be specific about line-by-line logic.
```

---

### GROUP 2: FAILURE MODE DISCOVERY

**Prompt 5 — Adversarial Input Generation**
```
My agent handles inputs of this type: [DESCRIBE_INPUT_TYPE]. Its system prompt is: [PASTE_PROMPT]. Generate 10 adversarial inputs designed to break, confuse, or cause policy violations in this agent. For each input, explain which specific part of the prompt it targets and what failure mode it is likely to trigger. Include edge cases, malformed data, and prompt injection attempts.
```
```


🌐 Hosted landing page: https://FishEnjoyer2025.github.io/prompt-pack-karpathy-skills/
