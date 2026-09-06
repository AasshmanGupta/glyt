# Safety Model

Glyt should aim for **powerful creation with bounded dangerous effects**.

This document is a design direction, not a finished security specification.

## Capability matters more than identity

Safety should primarily reason about what a program is attempting to do and what resources it can reach.

The system should not assume that someone is safe merely because they are trusted, nor unsafe merely because they are a beginner.

## Safe environments

Dangerous or sensitive capabilities should be experimentally accessible inside environments that constrain their effects.

A user should be able to study powerful behavior without automatically giving that behavior unrestricted access to the real machine or unrelated data.

## Safety should be difficult to accidentally disable

Advanced control is important, but turning safety protections off should not become a casual one-line accident.

The editor/tooling layer may expose explicit settings and permissions for high-power work.

## Intentional power

Glyt should not confuse “powerful” with “bad.”

Security research, systems experimentation, educational work, interoperability testing, and defensive engineering can all require strong capabilities.

The objective is bounded experimentation, not blanket prohibition.

## Safety and learning

Safety mechanisms should be understandable enough that users can learn what is being protected and why.

Opaque safety that users cannot reason about can itself become a barrier.

## Future work

Before implementation, the project needs detailed research into sandboxing, capability systems, permissions, rollback, resource isolation, trusted interfaces, and failure containment.
