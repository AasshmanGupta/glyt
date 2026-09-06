# Control Model

Glyt should support a continuous range of abstraction.

## The intended descent

**High-level Glyt**

→ **Deeper Glyt constructs**

→ **Lower-level system interfaces**

→ **Raw machine-facing control**

The user should not be forced into a completely different language merely because they want more control.

## Two directions

Creation can move upward and downward.

### Upward

Low-level mechanisms can become easier-to-use abstractions, libraries, domain vocabulary, or derived commands.

### Downward

High-level intent can be unpacked until the user reaches the actual mechanisms underneath.

## Abstraction is optional

Convenience is not a prison.

A user may stay at a high level or descend further depending on their goals.

## The editor participates

The language itself describes computation.
The development environment can expose configuration for permissions, target systems, debug depth, safety environments, toolchain options, and other implementation controls.

This keeps language design and development-environment design related without pretending they are the same thing.

## Escape routes

If Glyt cannot directly solve a problem, the project should have several possible exits:

- user-defined abstractions
- extension mechanisms
- lower-level access
- interoperability with another language
- contributing changes to Glyt itself
- building or integrating additional tools

No single convenience layer should become a dead end.
