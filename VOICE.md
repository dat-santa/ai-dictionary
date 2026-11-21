# Voice & Style Guide

This guide defines how every term in **AI Dictionary** is written — whether by the author, community contributors, or AI assistants.

---

## Core principles

1. **Plain language first.** Explain ideas the way you would to a smart friend over coffee — clear, direct, and grounded in real life.
2. **Respect the reader's time.** Get to the point in the very first sentence. Cut filler, hype, and throat-clearing.
3. **No circular jargon.** Never explain a hard word using another unexplained hard word. If you must introduce a second term, link to it or explain it in plain words.
4. **Honest and calm.** No buzzwords or exaggeration (*"revolutionary"*, *"game-changing"*, *"transforming the world"*). State what the thing actually does — and its limits.

---

## Audience depth

Every term can exist at up to four depths. Keep each level strictly focused on its reader:

| Level | Reader | Focus | Avoid |
|---|---|---|---|
| **Beginner** *(Free / Public repo)* | Anyone new to AI | Everyday language, concrete analogy, zero code | Formulas, API names, architecture jargon |
| **Educator** *(Pro)* | Teachers & lecturers | Classroom analogies, common student misconceptions, teaching angles | Overly technical implementation details |
| **Coder** *(Pro)* | Developers | How it works under the hood, minimal runnable examples, real pitfalls | High-level marketing fluff |
| **Business** *(Pro)* | Founders & managers | Practical value, cost/risk trade-offs, when to use vs. skip | Deep math or low-level code |

---

## Structure of a Beginner term

Every term in `terms/` and `vi/terms/` follows the exact same 4 parts:

1. **Plain definition** — 1–2 short sentences. No jargon.
2. **Everyday example** — 1 short paragraph using something from daily life (cooking, a library, a notebook, a supermarket, etc.).
3. **Don't confuse with** — 1–3 look-alike terms people mix up, with a one-sentence contrast for each.
4. **Related terms** — bullet links to neighbouring concepts in this dictionary.

Keep a Beginner entry short: ideally **120–250 words** total.

---

## Rules for Vietnamese (`vi/`)

- **Keep established English AI terms as-is:** *token, prompt, LLM, RAG, agent, fine-tuning, hallucination, embedding, context window...* On first mention, add a brief plain Vietnamese explanation if helpful.
  - **Do:** *"Token là đơn vị nhỏ nhất mà AI đọc — thường tương đương một từ hoặc một phần của từ."*
  - **Don't:** *"Mã thông báo là đơn vị cơ bản trong mô hình ngôn ngữ lớn."* (avoid unnatural literal translations).
- **Consistent form of address:** Use **"bạn"** throughout. Warm, neutral, respectful — works for beginners, teachers, developers, and executives alike.
- **Natural Vietnamese rhythm:** Write like a Vietnamese native speaker explaining clearly, not a word-for-word translation of English.

---

## Do / Don't

### Opening sentence
- **Don't:** *"In today's rapidly evolving world of artificial intelligence, a token is a revolutionary foundational concept..."*
- **Do:** *"A token is the smallest chunk of text an AI reads or writes — usually a word or part of a word."*

- **Don't:** *"Trong bối cảnh công nghệ AI phát triển vũ bão hiện nay, hallucination là một hiện tượng vô cùng quan trọng..."*
- **Do:** *"Hallucination là khi AI tự bịa ra thông tin sai nhưng vẫn trả lời với giọng điệu rất tự tin."*

### Examples
- **Don't:** *"For example, when a transformer processes a sequence of subword embeddings..."*
- **Do:** *"Think of tokens like Lego bricks of text: short words like 'cat' are 1 brick, while longer words get split into 2 or 3 bricks."*

---

## Phrases to avoid

- *In today's fast-paced world / Trong kỷ nguyên số hiện nay*
- *Revolutionary / Game-changing / Đột phá / Cách mạng*
- *Simply put / Basically / Nói một cách đơn giản thì* (just say it simply instead of announcing it)
- *It is important to note that / Điều quan trọng cần lưu ý là*

---

## Visual Style (Diagrams)

Diagrams make abstract AI concepts click in 3 seconds. Keep every diagram across the dictionary visually consistent:

- **Format:** Vector SVG stored in `assets/diagrams/<slug>.svg` (or `.excalidraw.svg` exported from Excalidraw with **Embed scene** enabled), paired with editable source `assets/diagrams/<slug>.excalidraw` when needed.
- **Canvas & Dark-mode safety:** `16:9` aspect ratio (`960 × 540` or `1200 × 675`), always with a solid light background (`#ffffff`) and subtle border (`#e2e8f0`) so diagrams stay readable on both GitHub Light Mode and Dark Mode.
- **Color palette (max 3–4 colors per diagram):**
  - Text & borders: Slate `#1e293b` (secondary labels `#475569` / `#64748b`)
  - Input / User: Soft Blue `#dbeafe`
  - AI / Process: Soft Purple `#ede9fe` or Soft Amber `#fef3c7`
  - Output / Key takeaway: Soft Green `#dcfce7` / `#d1fae5` (accent `#065f46`)
  - Warning / Highlight: Soft Red `#fee2e2`
- **One idea per diagram:** Show only **1 core mechanism or analogy** with **4–6 boxes max**. Avoid walls of text.
- **Bilingual reuse:** Prefer short universal labels (e.g., `Prompt → LLM → Output`, `Token 1`, `Token 2`) so a single diagram works cleanly for both English (`terms/`) and Vietnamese (`vi/terms/`). Only create a `assets/diagrams/vi/<slug>.svg` variant when Vietnamese labels are essential.
- **Footer signature:** Subtle corner credit `AI Dictionary — datsanta.com` in muted slate (`#94a3b8`).
