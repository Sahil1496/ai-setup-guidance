# Personal Engineering Operating Manual

This repository is my personal AI-agnostic engineering system: a living map of how I code, debug, document, automate, and evolve my work across tools such as GitHub Copilot, Claude, GPT, and other assistants.

It is designed to be:
- portable across AI tools
- specific to my working style
- structured for real-world engineering work
- maintainable as my methods evolve

## Core idea

The repo is not built around a single vendor or workflow. Instead, it stores the rules, methods, and templates that define how I work.

AI tools read this repo and align with it, rather than forcing me to re-learn or re-explain my preferences every time.

## Repository structure

- `AGENTS.md` — canonical operating instructions for assistant behavior
- `instructions.md` — portable human-readable summary of my working method
- `standards/` — coding and engineering standards by subject and language
- `templates/` — project scaffolds for common stacks
- `workflows/` — how I perform common engineering tasks
- `automation/` — CI/CD, quality, docs, and script patterns
- `prompts/` — reusable prompts for coding, review, and debugging
- `platform-wrappers/` — thin tool-specific translations of the same method
- `docs/personal-methods/` — how I think about coding and engineering
- `memory/` — evolving notes on what I change over time

## Primary engineering profile

I work across:
- Python
- Shell scripting
- SystemC
- C++
- C
- Makefiles
- CMake

My working style emphasizes:
- explicit typing
- readable function naming
- object-oriented structure where it helps
- documentation within code
- maintainability over cleverness
- disciplined debugging and root-cause analysis
- automation and repeatability
- cross-platform awareness

## Observed repository pattern

I also align this system with the patterns visible in my existing project work, especially the simple, direct C/C++ project structure using CMake and compact documentation patterns.

This repo is intentionally designed to preserve that practical engineering mindset while making it portable across AI tools.

## Markdown formatting standard

I prefer Markdown that remains readable and editable without rendering.

For tables, align columns manually so the file stays clean in plain text:

```text
|S.No| Description | Comment    |
|1   | qwerty      | no comment |
```

I do not rely on rendered table formatting to preserve readability.

## C++ standard reference

For C++ work, the base standard is the Google C++ Style Guide:
https://google.github.io/styleguide/cppguide.html

This repository extends that with my personal preferences for readability, maintainability, and documentation clarity.

## Philosophy

This repo should evolve with me.

Whenever I improve a workflow, add a new standard, or change a preference, I update the repo so the system learns from my habits instead of freezing them in time.

## Use it as a source of truth

Tools and AI assistants should follow this order:
1. `AGENTS.md`
2. `standards/`
3. `templates/`
4. `workflows/`
5. `automation/`
6. tool-specific wrappers

This keeps my personal method consistent across all environments.

## How to update it

When my workflow changes, update:
- relevant standard file
- workflow doc
- prompts
- template examples
- personal method notes

The repo is meant to be a living profile of my engineering identity.
