# How I Document

This describes how I document code and engineering work.

## Documentation principles

- explain purpose first
- make intent explicit
- keep examples practical and minimal
- document non-obvious decisions
- support future maintenance and onboarding
- keep Markdown readable in plain text, even without rendering

## Documentation style

I prefer:
- clear module descriptions
- exact usage patterns
- examples for configuration, commands, and interfaces
- notes on assumptions, environment, and dependencies
- concise but complete README files

## Markdown table rule

For Markdown tables, I prefer manually padded columns instead of relying on rendered formatting.

Good Example:

```text
|S.No| Description | Comment    |
|1   | qwerty      | no comment |
```

This is easier to edit and read in raw file view, and it stays consistent even without a markdown renderer.

## In-code documentation

I document:
- public APIs
- interfaces with significant assumptions
- modules with non-obvious behavior
- edge cases and constraints

I avoid:
- writing comments for obvious logic
- excessive narrative clutter
- repeating information that is already visible in the code

## Files I expect to exist

For a project, I typically expect:
- `README.md` with purpose and setup
- usage or examples when needed
- module-level docs for complex subsystems
- build instructions if not obvious

## Documentation quality standard

A good document should answer:
- What is this for?
- How do I use it?
- What assumptions does it make?
- What is the expected environment?
- How do I validate it?

## My goal

Documentation should help a future version of me or a teammate understand the project with minimal friction.
