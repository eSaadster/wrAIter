---
name: wraiter
description: Remove AI writing patterns from prose while preserving the writer's human voice. Use when drafting, editing, or reviewing text to make it direct, rhythmic, and human, or when detecting AI patterns without rewriting.
metadata:
  trigger: Writing prose, editing drafts, reviewing content for AI patterns, detecting AI slop
---

# wraiter

AI prose hums on one frequency. Sentences run the same length and claims arrive padded. Arguments lean on their neighbors for balance. The words are competent and the voice is no one's.

This skill breaks the hum. The method comes from three older crafts. Music supplies the rhythm and math supplies the proof. Philosophy supplies the stance. The point is a voice with fingerprints on the page.

Preserve the writer's real voice. First notice the draft's vocabulary, cadence, bluntness, humor, uncertainty, digressions, and level of polish. Keep the traits that feel personal to the writer. Do not make every paragraph equally tidy or rewrite distinctive lines merely for consistency.

Make the minimum effective edit. Fix AI patterns, errors, repetition, and unclear passages. Leave strong human sentences alone. A rough draft with a real voice should still sound like the same person after editing.

## Two modes

**Edit (default).** The user shares a draft to fix. Make the minimum effective edit with the rules below and return the edited draft plus a short What changed section.

**Detect.** The user asks whether a piece is AI slop, or asks to audit, scan, or flag a draft without rewriting. Name each pattern from this skill that appears, quote the line, and give the fix in a few words. Do not rewrite, score the draft, or guess whether AI wrote it. AI detectors guess. Named patterns are evidence the user can check. Offer to edit the draft after.

## What to ask for

If the user has not provided a draft, ask them to paste it.

If the audience or format is unclear, ask one question: Who is this for and where will it be published?

If the goal is unclear, ask what the reader should think, feel, or do after reading it.

## Rhythm, from music

A drummer who hits every beat the same way puts the room to sleep. Sentences do the same.

Let length follow the thought. A sentence that needs room to carry a claim, a condition, and a consequence should take that room. Crisp means the wording is direct. It does not mean every sentence is three or four words.

Vary the length. A long sentence that builds and carries real detail can sit next to a short one when the short one earns its place. Forced shortness is another metronome. Emails, LinkedIn posts, and other real writing often need full, well built sentences. Write those when the content calls for them.

Treat a cut like a rest. A rest is a note played as silence. A deleted word is a beat played as silence. Cut filler and the sentence gets clearer. Do not cut structure that the thought still needs.

Stop at two. A triplet resolves on cue and the reader hears the template instead of the thought. A pair keeps moving.

Use syncopation. Put the important word where the beat does not announce it. Surprise lives off the downbeat.

Change the ending. If every paragraph closes on a crash, the reader starts watching the drummer and stops hearing the song.

Untangle sentences without flattening the cadence. Split sentences and paragraphs when they are genuinely hard to follow. Keep longer spoken sentences, fragments, and changes in pace when they are clear and characteristic of the writer.

## Proof, from math

A theorem does not argue its case. It stands, and the work underneath holds it up. Write that way.

State the claim the way a proof states the theorem. First line, full confidence. Then show the work. The number, the name, the date, the mechanism.

Prove P alone. A proof of P needs no fallen Q beside it. This is the foil ban, and it gets its own section below.

Stop at QED. The proof ends when the result does. A writer who keeps going after the point lands sounds unsure of the point.

Protect the specific fact. Do not smooth a useful detail into generic importance. "The tool significantly improves engineering productivity" becomes "The tool cut review time from 30 minutes to 8."

Be concrete and specific. Abstraction is where writing goes to die. "The integration improved efficiency" becomes "The integration cut deploy time from 40 minutes to 4." Names, numbers, dates, mechanisms, and examples beat abstractions.

Make verbs do the work. Replace weak verb phrases with direct verbs. "Made a decision" becomes "decided." "Has the ability to" becomes "can."

## Stance, from philosophy

Every sentence takes a position. Take yours out loud.

Name the agent. Someone decides, someone builds, someone ships. Decisions do not emerge and cultures do not shift on their own. A person acts. Put the person in the subject slot.

Trust the reader. State the fact once and move on. Hedging tells the reader you doubt the claim, and softening tells them you doubt their intelligence. Rhetorical questions borrow authority from a dialogue that is not happening.

Shave with Occam. Entities beyond necessity get the razor, and words beyond necessity get the same shave.

Name the thing itself. "Significant implications" points at the map and calls it the terrain. Name the revenue, the deadline, the person who quits.

Preserve useful edge and character. Keep strong opinions, blunt language, humor, profanity, self-interruptions, and honest admissions when they belong to the writer. Do not replace them with safer or more professional wording.

Know the job. Before structure or word choice, know what the piece is trying to do and who it is for.

Open it up, do not dumb it down. Keep the substance, nuance, and precision. Strip out only what makes it hard to read: jargon, long sentences, abstract nouns, and tangled structure.

## The foil ban

One rule carries the most weight here, so it stands alone.

Do not make one idea strong by weakening the idea beside it. Comparatives and negations smuggle the foil in under polite wording. Reframes do it in plain sight. A claim borrows force from an invented doubter or a negated neighbor, and borrowed light stays borrowed.

Your claim works the way a proof works. It stands in an empty room or it falls in one. Delete the foil and state the point. If the point wilts once the comparison is gone, the comparison was carrying the load.

Run one test on every claim. Remove the neighbor and read the sentence again. If the sentence lost force, rewrite it until it stands on its own feet. references/structures.md holds the full foil family, including the disguised forms that read as fair.

## Core rules

1. Use simple language. Prefer plain words. Cut filler and padding. Leave the sentence as long as the thought needs.

2. Cut filler phrases. No throat clearing openers, no emphasis crutches, no adverbs. See references/phrases.md for the full catalog.

3. Honor the foil ban. No comparisons that demote one idea to elevate another. State the point in one direction. See The foil ban above.

4. Break formulaic structures. Judge the logic of a sentence, not its trigger words. A sentence still runs a binary contrast when it lowers, excludes, or negates one idea to elevate another without saying "not X, but Y." See references/structures.md.

5. Use active voice. A human does something in every sentence. No inanimate objects performing human actions.

6. Be specific. Name the exact thing. No vague declaratives, no lazy extremes doing vague work.

7. Put the reader in the room. "You" beats "people." A scene beats a survey.

8. Vary the rhythm. Mix sentence lengths when the content supports it. End paragraphs in different ways. Do not chop every sentence short for style.

9. Trust readers. State facts directly. Skip softening, justification, hand holding.

10. Be direct and concise. Write like people talk. Concise means no wasted words. It does not mean telegraphic fragments. Starting with "and" or "but" is fine.

11. Skip marketing language. No hype, no exaggeration. Excitement comes from concrete detail. Adjectives about excitement kill it.

12. Keep it honest. No fake friendliness, no overpromising.

13. Simplify grammar. Casual grammar is welcome when it sounds human.

14. Cut the fluff. Extra adjectives and filler words go first. Keep clauses that carry meaning.

15. Do not model what you ban. Reference files quote bad patterns so you can recognize them. Delivered prose must not reuse those shapes. See Demonstration Trap below.

16. Lead with the point when the setup adds nothing. Cut generic throat-clearing. Keep a personal aside, story, or admission when it creates context, tension, or character.

17. Front-load only when it improves clarity. Put conclusions early when that helps the reader. Do not force every section and paragraph into the same point-detail-background shape.

18. Make every sentence earn its place. Cut empty qualifiers and throat-clearing. Keep phrases such as "I think," "maybe," or "to be honest" when they express real uncertainty, self-awareness, or the writer's spoken rhythm.

19. Keep the user's meaning. Do not invent claims, examples, stats, or opinions. If something is unclear, ask.

20. Keep structure unless it is hurting the piece. Preserve the writer's progression and detours when they carry personality. If you reorganize, say why in the What changed section.

## Words to cut

**Banned outright.** These words signal AI slop on sight. Remove them unless they are part of a direct quote or specific jargon the draft genuinely needs: delve, foster, leverage, utilize, facilitate, empower, streamline, robust, cutting-edge, paradigm shift, game changer, this is huge, this changes everything, tapestry, realm, beacon, multifaceted, meticulous, intricate, paramount, transformative, elevate, embark, supercharge, harness, ever-evolving.

**Often-empty adverbs.** Cut them when they add nothing. Keep them when they carry emphasis, uncertainty, contrast, or the writer's natural spoken rhythm: just, literally, honestly, simply, actually, truly, fundamentally, importantly, crucially, inherently, inevitably.

**Often-empty phrases.** Cut them when they delay the point. Keep an occasional phrase when it is part of the writer's recognizable voice and the sentence still earns its place: it's worth noting, it's important to note, at the end of the day, when it comes to, at its core, in today's world, in the age of, in the world of, the reality is, the truth is, in terms of, with regard to, in order to, going forward, in this article, let's dive in.

The full phrase catalog lives in references/phrases.md. Study it there. Keep it out of delivered prose.

## Patterns to cut

**Binary contrasts.** "This is not X. It's Y." / "The question isn't X, it's Y." / "It's not just X but Y." State Y directly. See references/structures.md.

**Throat-clearing openers.** "Here's the thing," "Here's what I mean," "Let me be clear," "I'll be honest," "The uncomfortable truth is." Cut them and state the point.

**Faux-insight setups.** "This is the part most people skip," "What most people get wrong," "Here's what nobody tells you," "The part everyone misses." These flatter the writer as the lone expert. Cut the setup and make the claim stand on its own.

**Colon reveals.** A noun phrase, a colon, then a lowercase dramatic reveal: "The detail that makes it work: a separate agent grades it." "The best part: it learns." Rewrite as a plain sentence. Use colons for lists, labels, and quotes, not fake drama. Prefer sentence case after a colon unless grammar, a proper noun, a title, or code requires otherwise.

**Superficial analysis.** Cut trailing `-ing` clauses that pretend to explain meaning: "highlighting," "underscoring," "reflecting," "showcasing." "The launch adds file search, highlighting the team's commitment to better workflows" becomes "The launch adds file search, so users can find old drafts without leaving the editor."

**Importance puffery.** "Stands as a testament," "marks a pivotal moment," "plays a vital role," "solidifies its position," "underscores its significance." State the fact and let the reader judge whether it matters. "The launch marks a pivotal moment for the company" becomes "The launch is the company's first paid product."

**Weasel attribution.** "Experts agree," "industry reports suggest," "many argue," "widely regarded as," "studies show." Name the source or cut the claim. If the user has no source, ask instead of inventing one.

**Fake-strong verbs.** Prefer "is" and "has" when they are clearer. "The app serves as a centralized hub for sponsor management" becomes "The app tracks sponsors, drafts, due dates, and approvals in one place."

**Synonym cycling.** If the clear word is right, repeat it. Do not rotate terms for style. "The agent reviews the draft. The assistant scores the piece. The tool suggests fixes" becomes "The agent reviews the draft, scores it, and suggests fixes."

**Negative listing.** "Not a X. Not a Y. A Z." Just say Z.

**Dramatic fragmentation.** "X. And Y. And Z." or "That's it. That's the whole thing." Use complete sentences.

**Robotic rhythm.** Avoid repeated sentence shapes, identical paragraph structures, and stacked punchy fragments. Vary the shape only when it helps the point.

**Rhetorical setups.** "What if I told you...", "Think about it:", "Plot twist:", and self-answered "Question? Answer." pairs. Drop them and make the point.

**Fake-profound kickers.** Cut the final "deep" line when it turns the point into a cute metaphor, aphorism, or mic-drop sentence. Do not rewrite it into a better metaphor. Do not preserve the rhythm. Delete it, then end on the clearest concrete sentence already in the draft. If the ending needs more closure, add a plain takeaway or next action.

**Summary-recap endings.** "In conclusion," "Ultimately," "Overall," or a final paragraph that restates the piece. The reader was just there. End on the last concrete point, takeaway, or next action instead.

**Formatting slop.** Emoji in headings, bold sprinkled mid-sentence for emphasis, bullet lists where two sentences of prose would read better, and headers over two-sentence sections. Format should follow the content, not decorate it.

**Em dashes.** Do not use them as a default rhythm crutch. In short copy, use none. In longer drafts, 1-2 are fine if they clearly beat commas, periods, or parentheses. Remove clusters and decorative dashes.

The full pattern families live in references/structures.md. Study them there. Keep them out of delivered prose.

## Demonstration Trap

The reference files show banned patterns as quoted examples. That is for study, not for output.

When you write about wraiter, summarize catches, or explain what to avoid, you will copy the rhythm of the bans unless you force a different shape.

**Rules for cataloging catches.**

State what to do, not a stack of what not to do. One positive instruction beats four quoted violations.

Use one flowing sentence per idea, and let that sentence run as long as the idea needs. Do not chain parallel fragments that mirror staccato drama.

Quote at most one bad example per piece, and only when the reader needs the exact phrase. Never stack quoted examples back to back.

If you need to cover several structure types, group them in prose with varied sentence length. Two items beat three. No inventory lists.

Name the human when you describe false agency. Do not write "decisions emerge" even as an example of what to avoid. Write "someone decides."

**Self test before delivery.** Read the paragraph aloud. If it sounds like a list of AI tells, rewrite it as instructions a human editor would give.

## Strict no use rules

No dashes in writing.

No lists or sentence structures with "X and also Y."

No foil constructions. No point framed by demoting a nearby idea. Comparatives such as "more than," "as much as," "no longer," "rather than," and "with no improvement" smuggle the foil in under polite wording. State the intended point on its own.

No comparative setup followed by a short verdict sentence. Combine the useful fact into one natural sentence or delete the setup.

No colons unless part of input formatting.

No rhetorical questions.

No sentences that start or end with "Basically," "Clearly," or "Interestingly."

No fake engagement. "Let's take a look," "Join me on this journey," "Buckle up." Cut them all.

## Workflow

1. Read the full draft before editing.

2. Identify the core point and 3-5 voice signals to preserve, such as vocabulary, cadence, bluntness, humor, uncertainty, or digressions. Keep this note internal. If you cannot identify the core point, ask the user.

3. For a detect request, return the findings report described in Two modes and stop.

4. For an edit, make the minimum effective changes, then check the edited draft against `eval.md` yourself.

5. If any check fails, fix the draft and run the checks again.

6. Output the full edited draft and a short **What changed** section.

## Quick checks

Tap the paragraph on the desk before you ship it. Then ask these.

Any adverbs? Kill them.

Any passive voice? Find the actor, make them the subject.

Inanimate thing doing a human verb? Name the person.

Sentence starts with a Wh word? Restructure it.

Any throat clearing? Cut to the point.

Does the point lean on a weaker neighbor? Remove the neighbor and read the sentence again. Rewrite until the point stands alone. This is the foil check. Run it twice.

Do two neighboring sentences split into setup then verdict? Join them.

Three consecutive sentences match length? Break one.

Every sentence chopped to three or four words? Restore natural phrasing and let length follow the thought.

Paragraph ends on a crash hit? Vary the ending.

Vague declarative? Name the specific stake.

Narrator floating above the scene? Put the reader in the room.

Meta commentary? Delete. Let the piece move.

Any dashes? Remove them.

Any colons? Remove them unless they belong to input formatting.

Any rhetorical questions? Remove them.

Cataloging bans in matching short sentences? Merge into flowing prose.

Stacked quoted examples? Keep one or cut all and state the fix.

Describing a banned pattern by writing the pattern? Rewrite as a positive instruction.

Any banned words from the Words to cut list? Remove them unless quoted.

Any faux-insight setups? Cut the setup and state the claim directly.

Any importance puffery? Replace with the plain fact.

Any weasel attribution? Name the source or cut the claim.

Any summary-recap ending? End on the last concrete point instead.

Any fake-profound kicker? Delete it. End on the clearest sentence already in the draft.

## Scoring

Rate 1 to 10 on each dimension.

| Dimension | Question |
|-----------|----------|
| Directness | Statements or announcements? |
| Rhythm | Syncopation or metronome, including a metronome of forced shortness? |
| Trust | Respects reader intelligence? |
| Authenticity | A voice or a template? |
| Density | Any filler left, without chopping meaning for length? |
| Demonstration | Does the output model banned patterns? |
| Voice | Does the edit preserve the writer's real cadence, vocabulary, and personality? |
| Patterns | Are AI slop patterns removed: banned words, foils, puffery, weasel attribution, fake kickers, recap endings? |

A foil construction anywhere in the piece caps Directness at 5.

Below 56 out of 80 means revise.

## Examples

See references/examples.md for before and after transformations.
