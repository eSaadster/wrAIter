# wrAIter

A skill for removing AI tells from prose.

## What this is

AI writing has patterns. Predictable phrases, structures, rhythms. This skill teaches Claude or any LLM to catch and remove them while keeping natural sentence length and human rhythm.

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

**Structural clichés.** Foil constructions, binary contrasts, negative listings, dramatic fragmentation, rhetorical setups, false agency, narrator from a distance voice, passive voice, forced telegraphic shortness. See references/structures.md.

**Sentence level rules.** No Wh sentence starters, no dashes, no staccato fragmentation, no lazy extremes, active voice required. Length follows the thought. Crisp cuts filler. It does not chop every sentence short.

## Scoring

Rate 1 to 10 on each dimension.

| Dimension | Question |
|-----------|----------|
| Directness | Statements or announcements? |
| Rhythm | Syncopation or metronome, including forced shortness? |
| Trust | Respects reader intelligence? |
| Authenticity | A voice or a template? |
| Density | Any filler left, without chopping meaning for length? |
| Demonstration | Does output accidentally model banned patterns? |

Below 42 out of 60 means revise.

## License

MIT. Use freely, share widely.
