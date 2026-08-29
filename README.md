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

## Related editions

Each link goes directly to a peer edition repository; there is no central hub. Coverage describes public releases and may trail local production.

| Edition | Language | Public scope |
|---|---|---|
| [EGA — French](https://github.com/KokunoYumeto/ega-fr) | French | Complete declared EGA I–IV scope |
| [EGA — English](https://github.com/KokunoYumeto/ega-en) | English | Complete declared EGA 0–IV scope |
| [EGA/FGA — Spanish](https://github.com/KokunoYumeto/ega-fga-es) | Spanish | Validated partial EGA; FGA tranches A and B |
| [SGA — Spanish](https://github.com/KokunoYumeto/sga-es) | Spanish | Complete 13-book linked edition |
| [SGA — English](https://github.com/KokunoYumeto/sga-en) | English | Complete published scope; SGA 6 has mixed source alignment |
| [EGA/FGA/SGA — Brazilian Portuguese](https://github.com/KokunoYumeto/ega-fga-sga-pt-br) | Brazilian Portuguese | Validated partial release, including complete EGA III-1 and SGA 5 readers |
| [EGA/FGA/SGA — Vietnamese](https://github.com/KokunoYumeto/ega-fga-sga-vi) | Vietnamese | Validated partial release; current public readers are EGA |
| [FGA — English (external)](https://github.com/thosgood/fga) | English | Independently maintained external edition |
