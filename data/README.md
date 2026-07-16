# Data — structured analytical tables

Machine-readable versions of the five analytical tables from *Contested Liberalisms in Mexico*.
**License:** CC0 1.0 (public domain) — see `../LICENSE-data`. The article text (AAM) is CC BY-NC 4.0.

## Files

| File | Content | Rows |
|------|---------|------|
| `table1a_clv_general_instrument.csv` | The Constitutional Legitimacy Vector as a **general, reusable instrument** — the five Pegoraro & Rinella sources, the basis of obedience in each, and the CPEUM article that anchors it. *This is the scalable part: the blank instrument before it is applied to any case.* | 5 |
| `table1b_clv_applied.csv` | The CLV **applied** to the two Mexican liberalisms — dominant source, and the tension when both projects claim the same source | 7 |
| `table2_alterity_todorov.csv` | Todorov's three planes (axiological / praxeological / epistemic) × the two liberalisms | 5 |
| `table3_community_layers_coupling.csv` | The **decoupling diagnosis** — nine community layers, what each project holds, and the coupling status (`decoupled` / `in_dispute` / `synthesis`). *The article's central empirical finding.* | 9 |
| `table4_reform_chronology.csv` | The four "Plan C" constitutional reforms (2024–2025): DOF date (with ISO date), articles amended, legitimacy effect, enactment route | 4 |
| `tables_all.json` | All five tables bundled with metadata and schema notes — the interoperable single-file version | — |
| `bibliography.bib` | Core theoretical sources (Glenn, Pegoraro & Rinella, Todorov, Anderson, CPEUM) in BibTeX | 5 |

## Coding scheme (table3 `coupling_code`)

- `decoupled` — layer held by **one** project only (article color legend: red)
- `in_dispute` — **both** projects claim the layer (orange)
- `synthesis` — the resilience-profile summary row (blue)

## Reuse notes

- **To reapply the CLV to another country:** start from `table1a`, replace the CPEUM anchors with that country's constitutional articles, then build a new `1b`-style application table using the coding rules in `../protocol/premises_and_hypotheses.md` § 4.
- **Primary legal sources are linked, not mirrored** (see the protocol § 7), so the reform dates in `table4` always resolve against the canonical DOF / Cámara de Diputados record.
- Dates are given both in human form (`dof_date`) and ISO 8601 (`dof_date_iso`) for sorting and joins.
