# Glyt Licensing Model

Glyt is intended to make the open language implementation free while keeping
the things people create with Glyt free to belong to their creators.

> **Glyt itself stays free. Things people build with Glyt belong to the people
> who build them.**

This document describes the intended architecture. The applicable license
text for a particular file always controls.

## 1. Glyt implementation

The main Glyt software implementation is intended to be licensed under the
GNU General Public License version 3 (GPLv3), found in the repository root as
`LICENSE`.

The goal is that distributed modified versions of GPL-covered Glyt code keep
the corresponding freedoms and source-availability obligations of GPLv3.

## 2. Things built with Glyt

An application, game, tool, website, library, or other independent work made
using Glyt is not intended to become GPL merely because Glyt was used to make
it.

Its creator may choose its own licensing model, subject to the licenses of
any Glyt components actually incorporated into that work.

## 3. Runtime and standard-library boundary

Some future Glyt runtime or standard-library components may need an explicit
exception so that generated applications can use them without inheriting the
copyleft obligations of the runtime implementation itself.

The repository currently contains `LICENSE-RUNTIME-DRAFT.md` to record this
design. It is not a final legal license and should not be treated as one.

No future runtime component should be assumed to have an exception unless the
component itself says so clearly.

## 4. Independent implementations

A separately written compiler or other implementation of the Glyt language
can be independently licensed by its author, provided it does not incorporate
copyrighted Glyt implementation code in a way that makes the Glyt license
applicable.

The language specification is separately licensed as documentation.

## 5. Documentation, specification, and research

Unless stated otherwise, non-software written materials are licensed under
CC BY 4.0. See `LICENSE-DOCS`.

The purpose is simple: people should be able to read, reuse, translate,
remix, and build on Glyt's written knowledge while giving appropriate credit.

## 6. Contributions

Contributors retain ownership of their own work unless a separate agreement
says otherwise. By contributing material that is accepted into Glyt, the
contributor must grant the project the rights necessary to use, modify,
redistribute, and maintain that contribution under the project's applicable
licenses.

The exact contributor terms are documented in `CONTRIBUTING.md` and may be
formalized further before substantial third-party code is merged.

## 7. Branding

Copyright licensing does not automatically grant rights in the Glyt name or
logo. See `TRADEMARKS.md` for the project's current naming policy.

## 8. Security

Security handling is governed separately by `SECURITY.md`. Security policy is
not a replacement for, or modification of, the software licenses.

## 9. License design status

This repository is still pre-implementation. The licensing architecture may
be refined when the compiler, runtime, package system, and distribution model
exist and can be reviewed as real software.

No custom exception should be treated as final merely because it appears in a
draft document.
