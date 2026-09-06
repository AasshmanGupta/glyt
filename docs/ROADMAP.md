# Roadmap

This roadmap describes the direction of the project. Dates are intentionally omitted because discovery may change the sequence.

## v0.1 — Foundation Rebuilt

**Status: complete**

Established:

- North Star
- Constitution
- philosophy
- learning philosophy
- creator experience
- safety direction
- control model
- domain model
- Glyt/Loom boundary
- contribution model
- research direction
- explicit decision to keep concrete syntax undecided until better evidence exists

## v0.2 — Language Discovery

Goals:

- research programming education and human-computer interaction
- research successful language design patterns
- collect community experiments
- test competing syntax and interaction hypotheses
- define the conceptual core
- identify which abstractions are fundamental
- identify which conveniences can be derived

## v0.3 — Core Language Design

Potential areas:

- grammar
- expressions
- blocks
- values
- variables
- functions
- types
- modules
- control flow
- errors
- resource ownership/lifetimes if required
- metaprogramming or extension mechanisms if justified

Nothing in this list is guaranteed to survive research unchanged.

## v0.4 — Execution Experiments

Build minimal experimental implementations to test whether the proposed language actually feels and behaves as intended.

Possible work:

- lexer/parser prototypes
- interpreters
- small frontends
- diagnostics experiments
- interactive tooling

## v0.5 — Real Software

Demonstrate increasingly serious software built using Glyt.

Focus on:

- packaging
- executable distribution
- libraries
- integration
- debugging
- testing
- performance
- reliability

## v0.6 — Deep Control

Prove the high-level-to-low-level path.

Users should be able to remain productive at a high level while gaining progressively more control when required.

## v0.7 — Domain Expansion

Develop domain vocabularies and experiment with multiple ways of making the same underlying language feel native to different kinds of creators.

## v0.8 — Ecosystem Foundations

Potential areas:

- package management
- formatter
- linter
- language server
- testing tools
- documentation generation
- build/distribution tooling

## v0.9 — Serious Validation

Attempt real projects with real users.

Look specifically for cases where people abandon work because of needless friction, and determine whether Glyt actually prevents that.

## v1.0 — Glyt becomes a language people can trust

The exact definition of 1.0 will be determined by evidence, not by reaching a decorative checklist.

The bar is roughly:

> A broad range of people can use Glyt to make serious software, understand increasingly more of what they are doing, and retain access to deep control without the language losing its identity.
