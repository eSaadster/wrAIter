# wrAIter

A skill for removing AI tells from prose.

## What this is

AI writing has patterns. Predictable phrases, structures, rhythms. This skill teaches Claude or any LLM to catch and remove them.

## Skill Structure

```
wrAIter/
├── SKILL.md              # Core instructions
├── references/
│   ├── phrases.md        # Phrases to remove
│   ├── structures.md     # Structural patterns to avoid
│   └── examples.md       # Before and after transformations
├── README.md
└── LICENSE
```

## Quick start

**Claude Code.** Add this folder as a skill.

**Claude Projects.** Upload SKILL.md and reference files to project knowledge.

**Custom instructions.** Copy core rules from SKILL.md.

**API calls.** Include SKILL.md in your system prompt. Reference files load on demand.

## What it catches

**Banned phrases.** Throat clearing openers, emphasis crutches, business jargon, all adverbs, vague declaratives, meta commentary. See references/phrases.md.

**Structural clichés.** Binary contrasts, negative listings, dramatic fragmentation, rhetorical setups, false agency, narrator from a distance voice, passive voice. See references/structures.md.

**Sentence level rules.** No Wh sentence starters, no dashes, no staccato fragmentation, no lazy extremes, active voice required.

## Scoring

Rate 1 to 10 on each dimension.

| Dimension | Question |
|-----------|----------|
| Directness | Statements or announcements? |
| Rhythm | Varied or metronomic? |
| Trust | Respects reader intelligence? |
| Authenticity | Sounds human? |
| Density | Anything cuttable? |
| Demonstration | Does output accidentally model banned patterns? |

Below 42 out of 60 means revise.

## License

MIT. Use freely, share widely.
