# Glyt Runtime Exception, Draft

**Status: DRAFT. Not yet adopted as a final license.**

This document records the licensing design intended for the future Glyt
runtime and closely related standard-library components. It is deliberately
kept separate from `LICENSE`, which contains the unmodified GNU General
Public License version 3.

## Intended purpose

The Glyt runtime is intended to remain free software while allowing software
created with Glyt to remain under licenses chosen by its creators. The goal is
similar in spirit to established compiler runtime exceptions such as the one
used by GCC, but this document is **not** the GCC Runtime Library Exception
and must not be treated as a finished legal instrument.

## Intended policy

1. Runtime source code itself remains covered by GPLv3.
2. A designated runtime component may additionally grant permission for
   compiled or otherwise generated application code to be conveyed under
   terms chosen by the application author, subject to the final exception's
   conditions.
3. This permission does not grant permission to make modified copies of the
   Glyt runtime itself proprietary. Modified runtime source that remains a
   copyrighted derivative of Glyt remains subject to the applicable copyleft
   terms.
4. The final exception must define precisely which files are covered and how
   generated output is treated.
5. The final text must be reviewed before the runtime is distributed as a
   real software component.

## Why this is separate

A runtime exception is a legal boundary between the open Glyt implementation
and software created with Glyt. It should not be improvised by individual
contributors or inferred from the README.

Until a final exception is adopted, runtime components should not be assumed
to have this exception merely because they are part of the Glyt project.
