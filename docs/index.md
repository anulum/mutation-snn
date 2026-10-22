<!--
SPDX-License-Identifier: AGPL-3.0-or-later
Commercial license available
© Concepts 1996–2026 Miroslav Šotek. All rights reserved.
© Code 2020–2026 Miroslav Šotek. All rights reserved.
ORCID: 0009-0009-3560-0851
Contact: www.anulum.li | protoscience@anulum.li
MUTATION-SNN — repository foundation
-->

# Mutation SNN

This repository is preparing source-bound mutation testing for neuromorphic suites. Its current executable surface is repository validation tooling. It has no installed mutation-testing package, public mutation runner or qualified mutation report.

The intended workflow fixes complete source and population identity before execution. Every generated unique mutant and every actual attempt remains visible. Kills require a valid baseline and an attributable failure. Equivalence needs an independent scoped justification; unresolved cases cannot disappear from the report.

Read [Architecture](ARCHITECTURE.md), [validation tooling](validation-tooling.md), [data boundaries](THREAT_MODEL.md) and the [repository boundary decision](adr/0001-repository-boundary.md).
