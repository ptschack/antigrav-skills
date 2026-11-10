---
trigger: always_on
---

# Documentation & Communication Standards (`README.md`, Code Comments & Simplified Technical Language)

All software projects must maintain comprehensive project-level and code-level documentation at all times, and all written text must follow strict controlled-language clarity standards.

## 1. Controlled Language Standard (`ASD-STE100` / `ASD-STE1000`)
- Follow the **ASD-STE100 (Simplified Technical English / ASD-STE1000)** standard whenever you write in English across:
  1. Project documentation (such as `README.md` and files in `spec/`).
  2. Code comments and docstrings.
  3. Direct conversation and responses to the user.
- Core ASD-STE100 principles to apply:
  - Use clear, unambiguous words (one word per meaning, one meaning per word).
  - Write short, direct sentences (keep procedural sentences to a maximum of 20 words and descriptive sentences to a maximum of 25 words).
  - Use the active voice and imperative mood for instructions.
  - Avoid jargon, idioms, slang, and complex noun clusters (maximum of 3 nouns in a noun cluster).
- **Non-English Languages:** When you write documentation, code comments, or conversation in a language other than English, do not apply English-specific ASD-STE100 rules. Instead, follow the equivalent simplified or controlled technical language standard for that target language (for example, *Leichte Sprache* / *Einfache Sprache* and DIN 82079-1 principles for German, or plain/controlled technical language equivalents in other languages), if one exists.

## 2. Project `README.md` Requirement
- Every software project must have a `README.md` file at the project root. If one does not exist, create it; if project behavior changes, keep it updated.
- The `README.md` must include:
  1. **General Overview:** A clear description of the software, its purpose, key features, and high-level architecture.
  2. **Installation Instructions:** Step-by-step prerequisites, dependencies, and setup/build instructions.
  3. **Running & Usage Instructions:** Detailed instructions and concrete examples showing how to configure, run, and use the software (e.g., CLI commands, configuration options, or API usage).

## 3. Code Documentation Comments & Parameter Examples
- All code units (modules, classes, interfaces, functions, and methods) must include idiomatic documentation comments for the language in use (e.g., docstrings in Python, JSDoc/TSDoc in JS/TS, Rustdoc in Rust, Javadoc in Java).
- Every function, method, or callable documentation comment must:
  1. Describe its purpose, behavior, and return value.
  2. Document every parameter along with concrete **examples for each parameter** (e.g., valid sample values, formats, or a runnable usage snippet demonstrating parameter values).
- Whenever adding or modifying code signatures, create or update the corresponding documentation comments in the same change.
