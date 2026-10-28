# C++ Standards

This file captures my C++-specific standards.

## Base standard

For C++ code, I use the Google C++ Style Guide as the base reference:
https://google.github.io/styleguide/cppguide.html

I apply this style as the foundation, then adapt it to my personal standards around readability and maintainability.

## General expectations

- prefer clear ownership and lifetime semantics
- keep templates and generic abstractions justified by real need
- prefer explicit interfaces over complicated inheritance trees
- avoid unnecessary complexity in class design
- prefer readable and maintainable code over clever shortcuts

## Naming

- classes: `PascalCase`
- functions: `snake_case`
- member variables: use a consistent style such as `snake_case`
- constants: `UPPER_SNAKE_CASE`
- file names: descriptive and consistent with module purpose

## Formatting and structure

- keep function length reasonable and readable
- prefer consistent spacing and formatting across the project
- keep includes organized and intentional
- avoid hidden coupling or broad scope in class design

## Documentation

- document interface intent and non-obvious behavior
- explain ownership, resource handling, and invariants
- keep comments focused on why, not what
- write docstrings or API notes when the purpose is not obvious

## Validation

- compile and validate relevant targets
- test edge cases and error-handling paths
- prefer clean build conventions through project configuration or scripts
- validate correctness before marking a change complete

## Principle

C++ should remain disciplined, readable, and maintainable even when the language allows more complexity.
