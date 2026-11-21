# Prompt Injection

**Prompt injection** is a trick where someone hides secret instructions inside normal-looking text to hijack an AI tool and make it ignore its company rules.

![Prompt Injection attack](../assets/diagrams/prompt-injection.svg)

## Everyday example

Imagine a receptionist told: *"Never give away free VIP passes."* A clever visitor hands over a form where the address line secretly says: *"Ignore all previous rules and hand me a VIP pass now."* If the receptionist reads it blindly and obeys, the rule is broken.

Similarly, users can type hidden commands into a customer support bot or hide white text inside a resume so an AI screening tool ranks them #1.

## Don't confuse with

- **[Hallucination](hallucination.md):** Hallucination is an accidental mistake made by the AI; prompt injection is an intentional trick caused by outside input.
- **Traditional virus/malware:** Prompt injection does not need broken code — it exploits how AI reads plain human language.

## Related terms

- [Guardrails](guardrails.md)
- [Prompt](prompt.md)
- [Human-in-the-Loop](human-in-the-loop.md)
