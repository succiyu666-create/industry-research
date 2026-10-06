# Industry Six Questions

An evidence-aware Agent Skill for building a causal model of an industry through six linked questions:

1. What is the industry boundary?
2. Where does money come from and go?
3. Where is value created and how does it flow?
4. Who captures profit and why?
5. What risks exist and who ultimately bears them?
6. What forces could change the current structure?

The skill is designed for industry primers, market maps, sector research, strategic exploration, investment context, and rapid industry learning. Its goal is an industry model—not a generic report, company list, or logo wall.

## What it produces

- Industry definition, exclusions, taxonomy, and substitutes
- Funding and cash-flow map
- Value-chain and dependency map
- Profit-pool and industry-power analysis
- Risk-allocation and transmission map
- Structural-change causal chains and leading indicators
- Claim-level evidence and uncertainty tracking

## Structure

```text
industry-six-questions/
├── SKILL.md
├── agents/
│   └── openai.yaml
└── references/
    ├── framework.md
    ├── evidence-and-quality.md
    └── output-templates.md
```

## Installation

Copy or clone this repository into the skill directory used by your agent.

For Codex:

```bash
git clone https://github.com/succiyu666-create/industry-research.git ~/.codex/skills/industry-six-questions
```

For Claude Code:

```bash
git clone https://github.com/succiyu666-create/industry-research.git ~/.claude/skills/industry-six-questions
```

For a project-scoped installation, clone it into the project's skills directory supported by your agent runtime.

## Usage

Invoke it explicitly when your runtime supports skill names:

```text
Use $industry-six-questions to analyze the commercial drone industry in China.
```

Or ask naturally:

```text
Build an industry map for AI coding agents. Focus on who pays, where value and profit accrue, who bears model and distribution risk, and what could reshape the market.
```

Before deep research, provide the decision the analysis should support, geography, time period, focal segment, and explicit exclusions when known.

## Design principles

- Cash flow, value flow, profit flow, and risk flow are distinct.
- Value creation does not guarantee value capture.
- The first risk bearer may not be the ultimate bearer.
- A trend is useful only when connected to a causal mechanism and observable indicator.
- Important conclusions remain traceable to evidence, definitions, and uncertainty.

## License

MIT
