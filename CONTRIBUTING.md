# Contributing

Thanks for wanting to improve the **AI Prompt Starter Pack**.

## The format every prompt must follow

1. **System instruction** — a paragraph that fixes the AI's role, quality bar and honesty rules.
2. **Prompt block** — a copy-paste code block with `[bracket]` slots for the user's own niche and details.
3. **Why it works** — one short paragraph explaining the mechanism (why this beats a generic prompt).
4. **`[VERIFY]` / `[CONFIRM]` flags** where the model could otherwise invent facts.

## How to contribute

- **Improve a prompt:** open a PR editing the relevant file in `prompts/`.
- **Report a weak result:** open an issue with the input you used and the output you got.
- **Add a niche example:** append a short "example fill" section — do not remove the generic version.

## Rules

- No invented statistics, no fake testimonials, no claims we cannot stand behind.
- Keep prompts tool-agnostic (they must work in ChatGPT, Claude, Gemini and local models).
- Plain language. No marketing-speak.

By contributing you agree your work is released under the [MIT License](LICENSE).
