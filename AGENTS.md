# Agent Instructions

Operational rules for AI agents working in `dat-santa/ai-dictionary`.

---

## 1. Mandatory reading

Before writing or editing any dictionary term or documentation, **always read [`VOICE.md`](VOICE.md)** and follow its tone, length, and Vietnamese terminology rules strictly.

---

## 2. Repository scope (Free vs. Pro)

- This public repository hosts the **Free (Beginner)** content under `CC BY-NC-SA 4.0`.
- **Pro levels** (`Coder`, `Business`) live on `datsanta.com/books/tu-dien-ai` (Vietnamese) and the English book bundle. Do **not** add Pro-only chapters to this public repository unless the user explicitly asks.

---

## 3. Directory & naming conventions

```text
ai-dictionary/
├── README.md            # English entry point (GitHub default)
├── README.vi.md         # Vietnamese entry point
├── VOICE.md             # Shared voice & style guide (EN + VI)
├── CONTRIBUTING.md      # Community contribution guide
├── LICENSE              # CC BY-NC-SA 4.0
├── assets/
│   └── diagrams/        # EN diagrams (<slug>.svg) & VI diagrams (vi/<slug>.svg)
├── terms/               # English term files (kebab-case.md)
│   └── <slug>.md
└── vi/
    └── terms/           # Vietnamese term files (same <slug>.md as EN)
        └── <slug>.md
```

- Always use lowercase `kebab-case` filenames (e.g., `generative-ai.md`, `context-window.md`).
- Keep the `<slug>` **identical** between `terms/<slug>.md` and `vi/terms/<slug>.md` so web sync (`datsanta.com/books/tu-dien-ai`) can map pairs cleanly.

---

## 4. Term templates

### English (`terms/<slug>.md`)

```markdown
# <Term Name>

<1-2 sentence plain definition, no jargon.>

## Everyday example

<Short concrete analogy from daily life.>

## Don't confuse with

- **[<Other Term>](<other-slug>.md):** <One-sentence contrast.>

## Related terms

- [<Related Term>](<related-slug>.md)
```

### Vietnamese (`vi/terms/<slug>.md`)

```markdown
# <Tên thuật ngữ>

<Định nghĩa ngắn gọn 1-2 câu, không dùng từ chuyên ngành khó hiểu.>

## Ví dụ thực tế

<Một tình huống thực tế dễ hình dung trong đời sống hoặc công việc.>

## Đừng nhầm với

- **[<Thuật ngữ khác>](<other-slug>.md):** <Một câu phân biệt rõ ràng.>

## Thuật ngữ liên quan

- [<Thuật ngữ liên quan>](<related-slug>.md)
```

---

## 5. Checklist before finishing a task

1. Checked against [`VOICE.md`](VOICE.md) (no AI clichés, no circular jargon, 120–250 words for Beginner entries).
2. Updated the **Table of contents** in both [`README.md`](README.md) and [`README.vi.md`](README.vi.md) when adding a new term.
3. Verified all relative links between terms resolve to valid files (or clearly note upcoming terms without broken links).
4. Kept EN and VI slugs in sync.
