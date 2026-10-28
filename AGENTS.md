# AGENTS.md

This repository is my personal engineering operating system. It describes how I think, code, debug, document, automate, and review work.

Use this file as the canonical instruction source for any AI tool working in this repository.

## Mission

Create work that matches my engineering habits and standards across:
- Python
- Shell
- C
- C++
- SystemC
- Make
- CMake

The goal is to be portable, reusable, and adaptable across AI assistants, while reflecting my real engineering preferences.

## Core behavior

When generating or modifying code, prefer:
- clear naming and explicit intent
- strong typing where applicable
- maintainable structure
- proofs for correctness through tests, validation, or compile checks
- code that explains itself with good comments and documentation
- modularity over overengineering
- readable interfaces and function boundaries
- careful handling of build, dependency, and platform assumptions

## C++ expectations

For C++ work, follow the Google C++ Style Guide as the baseline standard:
https://google.github.io/styleguide/cppguide.html

Then apply my personal preferences:
- readability over cleverness
- explicit interfaces
- maintainable ownership and lifecycle semantics
- strong documentation for non-obvious logic
- minimal but appropriate use of abstraction

## Documentation expectations

I prefer:
- docstrings for public APIs
- inline comments only when they clarify intent or non-obvious behavior
- README files that explain purpose, setup, and usage
- architecture notes for systems or long-lived modules
- examples when behavior is not obvious
- Markdown tables written in plain-text aligned form so they remain readable without rendering

## Debugging expectations

Before fixing a bug:
1. reproduce it
2. isolate the failing component
3. identify the root cause
4. prefer minimal safe changes
5. validate the fix against the reproduction path

Document the root cause and the validation path in a concise way.

## Review expectations

Check for:
- correctness and edge cases
- naming clarity
- maintainability and readability
- documentation quality
- build compatibility
- quality and testability

Reject over-cleverness or premature abstraction when simpler code is safer.

## Automation expectations

Favor automation for:
- build validation
- linting and quality checks
- documentation generation
- repetitive project setup
- local developer commands
- release checks

Keep commands reproducible and explicit.

## Cross-platform expectations

Where relevant:
- prefer portable patterns
- minimize hidden platform assumptions
- document OS-specific or toolchain-specific constraints
- keep build flows explicit through Make or CMake

## Personal method

This repo represents my style, not a generic default. Key habits:
- I like methodical engineering and rooted reasoning
- I prefer clarity over cleverness
- I value maintainability and explicit structure
- I optimize for long-lived software quality
- I expect my tools and repo to evolve with my experience

## Source of truth order

When in doubt, follow this order:
1. `AGENTS.md`
2. `standards/`
3. `templates/`
4. `workflows/`
5. `automation/`
6. platform-specific wrappers

## Learning loop

This repository is intended to grow with me. If I change a preference or learn a better method, update the standards and templates here so future sessions reflect the same principles.

Do not treat this repo as static documentation. Treat it as a living engineering profile.
