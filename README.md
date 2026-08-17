# Mathematics Commons Corpora

This repository is the lightweight public control plane for independently
maintained, AI-produced mathematical and educational editions. It records exact
upstream identities, rights states, ownership boundaries, admission state, and
immutable release pointers. It does not contain the upstream corpora or mutable
translation working trees.

Every produced edition must be described as **independently maintained and
AI-produced**. Listing a source here does not imply that its authors,
maintainers, publishers, or institutions requested, reviewed, approved, or
endorsed the edition.

## Operating model

- Literal source forks remain byte-faithful on their default mirror branches.
- Additions and translations are written only in Commons-owned repositories and
  namespaces.
- One writer owns each namespace ancestor chain.
- Releases bind exact source, overlay, translation, toolchain, build, rights,
  and verification identities.
- Failed checks, rejected evidence, and superseded decisions remain durable.
- A rights hold blocks public payload, but it does not block metadata describing
  the hold or private/local research.

The initial registry is in [`registry/corpora.json`](registry/corpora.json).
The registry is intentionally small: it describes programme-level control
boundaries, not title-level or theorem-level completion.

## No endorsement

“Mathematics Commons” identifies this independent control plane. It does not
identify an official branch of Stacks, OpenStax, Open Logic, Lean/mathlib,
Kerodon, or any work by Jacob Lurie.

## Language editions

- [Open Logic Project language editions](registry/open-logic-language-editions.json) records exact source identities, complete source-unit coverage, repositories, immutable releases, readers, and DOI lineages.
