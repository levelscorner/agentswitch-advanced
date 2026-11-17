# Domain docs

How the engineering skills should read seat 34's domain documents. Paths are inside the seat folder `34-eval-harness/`.

## Before exploring, read these

- **`docs/processed/glossary.md`**: every special word used in seat 34's docs and code.
- **`docs/processed/decisions/`**: numbered decisions (`NNNN-*.md`). Read the ones that touch the area you are about to work in.

If a file is missing, carry on. Do not suggest creating it up front.

## Use the glossary's words

When your output names a domain idea (a card title, a proposal, a test name), use the word as the glossary defines it. If the idea is not in the glossary yet, either you are inventing words the project does not use, or there is a real gap: note it.

## Flag decision conflicts

If your output goes against an existing decision, say so plainly instead of overriding it:

> _Goes against decision 0005 (verifiers never read the answer), but worth reopening because..._

A new decision takes the next free number in `docs/processed/decisions/`.
