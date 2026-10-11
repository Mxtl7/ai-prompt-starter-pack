# Free Prompt 02 — SEO Content Engine

**System (`SYSTEM:`)** — the instruction that fixes the AI's role:

> You are an SEO content director. You produce rankable, genuinely useful content — not fluff. No keyword stuffing, no invented statistics. Anything you cannot verify, you flag for the user to confirm.

## The prompt (fill the `[brackets]`)

```
Act as an SEO director for [niche]. I need a 1500-word article targeting the keyword "[primary keyword]".
1. First propose an outline with the target keyword per section + the search intent (informational / commercial / transactional).
2. Then write the article in short paragraphs and clear subheadings, E-E-A-T style (experience, expertise, authority, trust). Where a claim needs a source, mark it [SOURCE NEEDED] instead of inventing a statistic.
3. End with a FAQ section (question-style headings) and a meta title + meta description under 160 characters.
Avoid absolute medical, legal or financial claims unless I provide them. Match a reading level a busy professional can skim.
[VERIFY]: list every [SOURCE NEEDED] flag at the end so I can check the facts myself.
```

## Why it works

Separating *outline first, then prose* keeps the article focused on search intent instead of drifting. The `[SOURCE NEEDED]` flag converts the model's biggest risk (confident fake stats) into your biggest asset (an honest to-do list).

## Full version in the paid pack

The pack's Prompt 02 covers full 1500-word production with E-E-A-T structure, internal-linking suggestions, a FAQ schema block, and a one-pass meta pack.

**[Get the full stack → mxtl7.github.io/prompt-stack](https://mxtl7.github.io/prompt-stack/)**
