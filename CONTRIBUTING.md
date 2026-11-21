# Contributing to AI Dictionary

Thank you for helping make AI easier to understand for everyone.

---

## Ways to contribute

- **Fix a mistake:** Typo, unclear wording, broken link, or a misleading analogy.
- **Suggest a missing term:** Open an Issue with the term name and why beginners run into it.
- **Add a new term (or translation):** Submit a Pull Request following our template and style guide.

---

## Before you write

1. Read [`VOICE.md`](VOICE.md) — it explains our plain-language tone, word count, and Vietnamese terminology rules.
2. Check [`README.md`](README.md) (English) or [`README.vi.md`](README.vi.md) (Tiếng Việt) to make sure the term does not already exist.

---

## File structure & naming

- English terms go in `terms/<slug>.md`
- Vietnamese terms go in `vi/terms/<slug>.md`
- Use lowercase `kebab-case` for file names (for example: `generative-ai.md`, `prompt-engineering.md`). Keep the same `<slug>` for both English and Vietnamese versions.

---

## Term template

Every Beginner term follows the same 4 sections:

```markdown
# Term Name

One or two plain sentences explaining what it is, with no jargon.

## Everyday example

A short, concrete example from daily life.

## Don't confuse with

- **[Look-alike term](look-alike-term.md):** One sentence explaining the difference.

## Related terms

- [Neighbouring term](neighbouring-term.md)
```

*(For Vietnamese entries, use the headings: `## Ví dụ đời thường`, `## Đừng nhầm với`, `## Thuật ngữ liên quan`.)*

---

## Pull request checklist

- [ ] Follows [`VOICE.md`](VOICE.md) (plain language, short, no hype or circular jargon)
- [ ] Uses the 4-section template above
- [ ] Added to the Table of contents in [`README.md`](README.md) and/or [`README.vi.md`](README.vi.md)
- [ ] All internal links work

---

## License

By contributing to this repository, you agree that your contributions will be licensed under [CC BY-NC-SA 4.0](LICENSE).
