# Glyt and Loom

Glyt and Loom are separate projects.

They are related, but they answer different questions.

## Glyt asks

> **What should this language be?**

Glyt is responsible for language identity, philosophy, user experience, language design, and the community that discovers those things.

## Loom asks

> **How do we transform one representation into another?**

Loom is a separate universal translation/build/transformation engine intended to solve problems associated with language-specific compiler infrastructure and fragmented toolchains.

## Glyt is not a Loom module repository

Glyt is the language project.

A Glyt knowledge module or frontend may eventually exist for Loom, but that does not make Glyt itself part of Loom's implementation.

## Possible future relationship

```text
             GLYT
      What should the language be?
              │
              ▼
       Glyt language knowledge
              │
              ▼
            LOOM
   How should transformation happen?
              │
        ┌─────┼─────┐
        ▼     ▼     ▼
      target target target
```

A Loom-facing Glyt module could be very small if Loom provides the broader transformation machinery.

## Independence

Glyt should remain independently meaningful.

If the Glyt community eventually wants an independent compiler or frontend, it may build one.

If Loom can make Glyt executable through a compact module, that is an amplification of Glyt, not a dependency that defines Glyt's identity.

## Important boundary

Do not build Glyt's language design around assumptions about Loom's internal implementation.

Do not build Loom's architecture around assumptions that Glyt will never change.

The projects should be able to evolve independently while benefiting from each other.
