# Contested Liberalisms in Mexico
## Popular Liberalism, the Fourth Transformation, and the Struggle over Constitutional Identity

[![License: CC BY-NC 4.0](https://img.shields.io/badge/Manuscript-CC%20BY--NC%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc/4.0/)
[![Data: CC0](https://img.shields.io/badge/Data-CC0%201.0-brightgreen.svg)](https://creativecommons.org/publicdomain/zero/1.0/)
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.21386477.svg)](https://doi.org/10.5281/zenodo.21386477)
[![ORCID](https://img.shields.io/badge/ORCID-0000--0002--4673--4486-a6ce39.svg)](https://orcid.org/0000-0002-4673-4486)

**Author:** Luis Bourguet — [luisbour@ucm.es](mailto:luisbour@ucm.es)
**Affiliations:** Universidad Complutense de Madrid (UCM) · Università di Torino, LabOnt — Center for Ontology · Hiroshima University, Laboratory of Complex Systems
**Accepted (minor revisions):** INGURUAK — Revista Vasca de Sociología y Ciencia Política (ISSN: 0214-791X) · <http://inguruak.eus>

---

## What this repository is

This is an **open-science deposit** for the article above. It goes beyond depositing the PDF: it provides a **FAIR data companion** so the article's instruments and findings can be reused, re-applied to other cases, and checked against future events.

| | Findable | Accessible | Interoperable | Reusable |
|---|:---:|:---:|:---:|:---:|
| **How** | DOI + ORCID + Zenodo/OpenAIRE | Open, no paywall | CSV + JSON + BibTeX, explicit schema | CC0 data + explicit coding rules |

## Abstract

Mexico's *Cuarta Transformación* (4T) is usually read as one instance of a global illiberal turn. This article argues instead that the Mexican constitutional conflict is **internal to the liberal-republican tradition**: rival projects each claim the mantle of liberalism to define who counts as 'the people'. The 4T advances by appropriating a popular, Juarista liberalism against a proprietary one it codes as *neoporfirista*. Four frameworks — comparative law (Glenn), legitimation theory (Pegoraro & Rinella), alterity (Todorov) and imagined communities (Anderson) — are synthesised through a **Constitutional Legitimacy Vector (CLV)**, producing a structural decoupling resistant to procedural resolution. The case refines the theory of illiberalism: Latin American populism can operate through **appropriation of the liberal lineage**, not its negation.

## Repository contents

```
├── README.md                     ← this file
├── CITATION.cff                  ← how to cite
├── .zenodo.json                  ← Zenodo deposit metadata
├── LICENSE                       ← CC BY-NC 4.0 (manuscript)
├── LICENSE-data                  ← CC0 1.0 (data + protocol)
│
├── manuscript/
│   └── Bourguet_2026_Contested_Liberalisms_Mexico_AAM.pdf   ← add this yourself
│
├── data/                         ← CC0 · structured, machine-readable
│   ├── README.md
│   ├── table1a_clv_general_instrument.csv    ← reusable blank CLV instrument
│   ├── table1b_clv_applied.csv               ← CLV applied to the two liberalisms
│   ├── table2_alterity_todorov.csv           ← three planes of alterity
│   ├── table3_community_layers_coupling.csv  ← the decoupling diagnosis (key finding)
│   ├── table4_reform_chronology.csv          ← the four Plan-C reforms, DOF-dated
│   ├── tables_all.json                       ← all tables + schema, one file
│   └── bibliography.bib
│
├── protocol/                     ← CC0
│   └── premises_and_hypotheses.md            ← premises, hypotheses, coding rules, forecasts
│
└── figures/
    └── figure3_analytical_architecture.png
```

## Two licenses, on purpose

- **Manuscript** (`/manuscript/`) → **CC BY-NC 4.0** (`LICENSE`)
- **Data and protocol** (`/data/`, `/protocol/`) → **CC0 1.0** (`LICENSE-data`)

The permissive CC0 on the data layer is deliberate: it lets other researchers reapply the Constitutional Legitimacy Vector to new constitutional conflicts, and integrate the reform chronology into comparative datasets, without licensing friction — the standard FAIR recommendation for structured research data.

> The license of the final **typeset** article (Version of Record) is governed by INGURUAK's editorial policy; consult <http://inguruak.eus>.

## How to reuse the instrument

The Constitutional Legitimacy Vector is designed to travel. To apply it to another country:
1. Start from `data/table1a_clv_general_instrument.csv` (the blank instrument).
2. Replace the CPEUM article anchors with the target constitution's articles.
3. Build a `1b`-style application table using the coding rules in `protocol/premises_and_hypotheses.md` § 4.

## Citation

> Bourguet, Luis (2026). *Contested Liberalisms in Mexico: Popular Liberalism, the Fourth Transformation, and the Struggle over Constitutional Identity* [Accepted Author Manuscript, with FAIR data companion]. Zenodo. https://doi.org/10.5281/zenodo.21386477

Once published, cite the journal Version of Record (INGURUAK, ISSN 0214-791X) and reference this deposit for the data.

## Notes and provenance

- Previously circulated as a working paper titled **"Contested Sovereignty"** at *Emergent Sovereignties* — the Fifth International Conference on Nationalism (<https://emergentsovereignties.net/en/abstract/>).
- Primary legal sources (CPEUM, DOF decrees) are **linked, not mirrored**, so they always resolve to the canonical, current version.
- Figures 1–2 (Alarcón political cartoons) are **not** included here: they require reproduction permission and are omitted from the open deposit.

---

*Repository maintained by the author. Data and protocol dedicated to the public domain (CC0 1.0); manuscript under CC BY-NC 4.0.*
