---
trigger: always_on
---

# Documentation and Communication Standards

Maintain complete project documentation and code documentation for all software projects. Write all text in Simplified Technical English (ASD-STE100 / ASD-STE1000).

## 1. Controlled Language Standard (`ASD-STE100` / `ASD-STE1000`)
- Write all English text in compliance with the **ASD-STE100 / ASD-STE1000** standard.
- Apply this standard to:
  1. Project documentation (for example, `README.md` and files in `spec/`).
  2. Code comments and docstrings.
  3. Direct messages and responses to the user.
- Obey these ASD-STE100 rules:
  - Use clear and approved words. Use one word for one meaning.
  - Write short sentences. Use a maximum of 20 words for procedural sentences. Use a maximum of 25 words for descriptive sentences.
  - Use the active voice. Use the imperative mood for instructions.
  - Do not use jargon, idioms, or slang.
  - Use a maximum of 3 nouns in a noun cluster.
- **Other Languages:** Do not apply English ASD-STE100 rules to text in other languages. Use the equivalent simplified technical language standard for the target language (for example, *Einfache Sprache* and DIN 82079-1 for German).

## 2. Project `README.md` Requirements
- Every software project must have a `README.md` file in the root directory.
- If the `README.md` file does not exist, create it.
- If the software behavior changes, update the `README.md` file.
- Include these sections in the `README.md` file:
  1. **General Overview:** Describe the software, its purpose, its main functions, and its high-level architecture.
  2. **Installation Instructions:** List all prerequisites and dependencies. Give step-by-step instructions to install and build the software.
  3. **Usage Instructions:** Give instructions and examples to configure, run, and use the software (for example, CLI commands, configuration options, and API calls).

## 3. Code Documentation Comments and Parameter Examples
- Write standard documentation comments for all modules, classes, interfaces, functions, and methods (for example, Python docstrings, JSDoc, TSDoc, Rustdoc, or Javadoc).
- Include this information in every function or method comment:
  1. The purpose, behavior, and return value of the function.
  2. Each parameter and a clear example for each parameter (for example, valid values, data formats, or a code usage example).
- When you add or change a function signature, update its documentation comment at the same time.
