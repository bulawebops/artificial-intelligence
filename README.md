## Harness Engineering 
AI models are powerful on their own, but the systems that put them to work in production — the loops, the tools, the context strategies, the configuration — are what turn a model into a reliable product. We call that work harness engineering, and it's what this course is about.
In this course, you'll move from choosing the right Claude model for a job to standing up complete, tested systems. You'll write real code, run it against real test suites, and finish with a capstone where you operate and defend four working systems end to end.

### What You'll Build
* A stop-reason-driven agentic loop — a claims-intake agent whose control flow is driven entirely by the model's stop_reason, with a disciplined tool kit and an anti-pattern audit.
* A long-conversation context strategy — a retail support copilot that stays affordable by pruning tool output, pinning case facts, and compressing resolved segments under a coherent token budget.
* A configured Claude Code harness — a multi-surface monorepo team setup with a layered CLAUDE.md hierarchy, path-scoped rules, a custom slash command, and a forked-context skill.
* A multi-shift orchestration system — a Layer 3 quality-monitoring system that runs fresh each shift, keeps state tiny through tiered storage, recovers from crashes, and forks state for hypothesis exploration.

Along the way you'll select Claude models by weighing intelligence, speed, and cost; design agent architectures around the perceive–reason–act loop; build production agents with the Claude Agent SDK; and author reusable Claude Skills. The final project ties all four systems together.


### Two Languages, One Set of Skills
You write TypeScript in some lessons and Python in others. This is on purpose. Harness engineering is about patterns, not syntax. A stop-reason loop, a tool schema, a context budget, or a configuration hierarchy are the same idea in any language. Claude's building blocks work the same way in both. The Claude API, the Claude Agent SDK, and Claude Code all ship in TypeScript and in Python. The method names barely change. Write the same loop in each language and the pattern stands out, because the syntax around it is all that moved.

Two languages also matches industry. AI teams rarely use one language.
* App and front-end tooling often uses TypeScript.
* Data, ML, and backend agent services often use Python. If you only know one language, you can only work on half of the stack.

Here is the split across the course:
* TypeScript: the foundational lessons. You select models, build with the Claude Agent SDK, configure Claude Code, and author Claude Skills.
* Python: the project modules and the capstone. You build the agentic loop, the context strategy, the multi-surface configuration, and the orchestration system.

You do not need to be fluent in both. The prerequisites list the level assumed. When a language is unfamiliar, ask Claude Code in your workspace to explain it.
