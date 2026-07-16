# Premises, Hypotheses, and Coding Protocol
## Reproducibility and reuse companion to *Contested Liberalisms in Mexico*

**Author:** Luis Bourguet · ORCID [0000-0002-4673-4486](https://orcid.org/0000-0002-4673-4486)
**Companion to:** *Contested Liberalisms in Mexico: Popular Liberalism, the Fourth Transformation, and the Struggle over Constitutional Identity* (INGURUAK, forthcoming; AAM at [10.5281/zenodo.21386477](https://doi.org/10.5281/zenodo.21386477))
**Data license:** CC0 1.0 (public domain dedication) — see `../LICENSE-data`
**Purpose:** To make the article's premises, hypotheses, coding rules, and analytical instruments explicit enough that another researcher can (a) evaluate the inference, (b) reapply the instrument to a different case, and (c) check the forecasts against future events.

> **Note on "data" for interpretive research.** This is a work of interpretive constitutional and political-sociological analysis, not a statistical study. Its "reproducibility" is *analytic transparency* in the APSA/DA-RT sense: the premises are stated, the coding rules that map primary sources to analytical categories are explicit, and every substantive claim is traceable to a primary source (a dated *Diario Oficial de la Federación* decree, a constitutional article, or a documented ruling). Two researchers applying the same rules to the same sources should reach compatible — not necessarily identical — judgments.

---

## 1. Premises

**P1 — Anti-reductionism.** A national constitutional order is not reducible to its legal text alone. It is a multi-level formation in which institutional rules, documentary inscriptions, collective intentionality, legitimacy structures, and constructions of alterity interact. No single-factor (purely legal, purely cultural, purely economic) explanation is admitted.

**P2 — Liberalism is internally plural.** "Liberalism" is not a single stable object against which a project defines itself. At least two rival liberal lineages operate in the Mexican case: a **popular/Juarista** liberalism and a **procedural/proprietary** liberalism the 4T codes as *neoporfirista*.

**P3 — Civil-law condition of possibility (after Glenn 2014).** Mexico belongs unambiguously to the civil-law tradition: codified, without *stare decisis*, without entrenched unamendable clauses. This determines which instruments of constitutional change exist (Art. 135 supermajority amendment) and which do not (entrenchment, precedent-based protection). This premise is what makes the reforms legible as *rule-following* rather than *rule-breaking*.

**P4 — Legitimacy is never automatic (after Pegoraro & Rinella 2016).** Constitutional obedience must always be explained, not assumed. It is produced by identifiable sources of legitimation (tradition, agreement/consent, divine authority, reason, political authority), operationalised here as the **Constitutional Legitimacy Vector (CLV)**.

**P5 — Every "we" constructs an "other" (after Todorov 1982).** Every definition of a national people simultaneously constructs alterity, distributed across three independent planes (axiological / praxeological / epistemic) that need not move together.

**P6 — Community is layered (after Anderson 1983).** A constitutional order addresses multiple, separable layers of community (belonging, imagined, moral, juridical, epistemic, constitutional, destiny, ontological). Resilience depends on whether these layers *couple* onto a shared frame.

---

## 2. Central thesis and hypotheses

### T0 — Core thesis (the intra-liberal thesis)

> The Mexican constitutional conflict driven by the *Cuarta Transformación* (4T) is **internal to the liberal-republican tradition** — a dispute of *degree and dialect within* liberalism — **not** a liberal-vs-illiberal rupture. The 4T advances by **appropriating** a popular, Juarista liberalism against a proprietary one it codes as *neoporfirista*, rather than by negating liberalism.

This thesis must be held firm as a claim of *kind*: the conflict is one of degree along a shared continuum, not a categorical rupture that would place the 4T outside the liberal-republican tradition.

### H1 — Appropriation, not negation

The 4T's erosion of counter-majoritarian institutions is conducted **in the name of another liberal source** (consent, reactivated as popular sovereignty under Art. 39), and proceeds **through** the constitutional form (Art. 135 is used, not suspended), **not** from an avowedly anti-liberal position.

- **Observable implication:** reform decrees will *cite* the constitutional amendment power and popular-sovereignty articles, rather than suspend or bypass them.
- **Verification:** confirmed in the DOF record — the organic-simplification decree (20 Dec 2024) *expressly invokes Art. 135*. See `../data/table4_reform_chronology.csv`.

### H2 — The decoupling hypothesis (central empirical finding)

Constitutional resilience requires the alignment (coupling) of multiple community layers onto a shared frame. In Mexico the two projects align on **non-overlapping** layers: popular liberalism holds belonging, imagined, moral, destiny, and ontological; procedural liberalism holds juridical, epistemic, and constitutional. The juridical and constitutional layers are *in dispute*; the rest are *decoupled*.

- **Observable implication:** the conflict is resistant to procedural resolution, because no shared layer exists on which a procedural settlement could rest.
- **Coding:** see `../data/table3_community_layers_coupling.csv`, column `coupling_code` (`decoupled` / `in_dispute` / `synthesis`).

### H3 — Legitimacy-shift hypothesis

The 4T's legitimacy profile is dominated by **Tradition + Consent + Authority**, with the **Reason** component actively suppressed. Procedural liberalism's profile is dominated by **Reason + Consent**, with Authority formally rejected. Because both cite the *same* text (notably Art. 39), the conflict is **constitutionally undecidable on textual grounds alone**.

- **Coding:** see `../data/table1b_clv_applied.csv`, columns `popular_liberalism_4T` / `procedural_liberalism` / `tension_what_is_at_stake`.

### H4 — Threshold clarification (relation to illiberalism)

The threshold between liberal appropriation and illiberal effect is one of **degree along a shared continuum**, not a change of kind. Whether the order tips into what comparative scholarship would, *on its effects*, class as illiberal is treated as an **empirical** matter — measured by the distance between the resilient and fragmented trajectories (see H5) — not a definitional verdict issued in advance.

---

## 3. Falsifiability conditions

The thesis is not merely interpretive dressing; it carries explicit conditions under which it would fail.

**F1 — Most-likely-case logic (stated in § 4).** The reform episodes selected are those where the two liberalisms collide *most directly* (judicial reform, militarisation, autonomous-body extinction). If the intra-liberal interpretation **fails to illuminate precisely these episodes**, the thesis is in serious doubt. That it does illuminate them is correspondingly informative.

**F2 — Negation test.** If reforms were enacted by **suspending** the constitutional form (bypassing Art. 135, ignoring supermajority ratification, or openly repudiating the liberal lineage) rather than **through** it, H1 (appropriation-not-negation) would be falsified. *Current status: not falsified* — the decrees proceed through Art. 135.

**F3 — Coupling test.** If a procedural settlement were reached that both projects accepted *on a shared community layer*, H2 (structural decoupling) would be falsified. *Current status: not falsified.*

---

## 4. Coding rules (how primary sources map to categories)

To reapply or audit the analysis, use these rules.

### 4.1 CLV source coding (Tables 1a / 1b)

Assign a legitimacy claim to a source by the **maxim it appeals to**:

| Source | Assign when the claim appeals to… |
|---|---|
| Tradition | historical/revolutionary lineage as self-validating ("continuity with Juárez/the Reforma") |
| Consent/Agreement | prior agreement, electoral or plebiscitary mandate, the constitutional pact |
| Divine | transcendent/sacred sanction (rare in Mexican constitutional doctrine; note tone only) |
| Reason | technical, codified, law-bound, expert, or counter-majoritarian authority (courts, *jurisprudencia*, autonomous bodies) |
| Authority | the personal/charismatic standing of the office-holder as the group's authentic voice |
| Common law | **N/A** by principle — Mexico is a civil-law order (P3); functional analogue folded into Reason |

A source is marked **suppressed / ↓** when a reform reduces the institutional capacity that carries it; **↑** when a reform amplifies it.

### 4.2 Alterity coding (Table 2, after Todorov)

Code each project independently on three planes that **do not move together**:
- **Axiological** — is the other judged *bad* or merely *different / deficient*?
- **Praxeological** — *assimilation* (impose own image), *identification*, or *indifference/containment*?
- **Epistemic** — does the project *know* or *refuse to know* the other on its own terms?

### 4.3 Coupling coding (Table 3, after Anderson)

For each community layer, mark:
- `decoupled` — the layer is held by **only one** project (color: red)
- `in_dispute` — **both** projects claim the layer (color: orange)
- `synthesis` — the summary/resilience-profile row (color: blue)

### 4.4 Mechanism coding (used throughout § 5–6)

Every substantive claim is referred to a mechanism type:
- **constitutive** — creates a status or category
- **reproductive** — maintains it
- **transformative** — changes it
- **disruptive** — breaks it down

### 4.5 Temporal status of evidence (the fact/projection boundary)

- **§ 6 — enacted, dated institutional practice.** Reforms documented with their DOF promulgation dates and, where relevant, Supreme Court rulings. Treated as *fact*.
- **§ 7 — textual evidence + prospective trajectories.** What is legible in the *current* constitutional text, plus five conditional forecasts. Treated as *projection*, stated in the conditional.

This boundary must be preserved in any reuse: do not promote a § 7 trajectory to a § 6 fact.

---

## 5. Forecasts (checkable against future DOF publications)

Five prospective trajectories (§ 7), each a different resolution of the H2 decoupling. These are **foresight hypotheses**, checkable as the constitutional record develops:

| Trajectory | Condition | Checkable signal |
|---|---|---|
| **Resilient** | Counter-majoritarian institutions absorb the challenge; the decoupling is *reversed* (each project builds the layers it lacks) | New institutions combining popular legitimacy **and** technical competence; Reason component rebalanced |
| **Polarised** | Decoupling entrenched permanently; two publics each cite Art. 39 for its own reading | Sustained non-overlap; no shared layer emerges |
| **Fragmented** | Epistemic/juridical layers dissolve without replacement | Autonomous architecture dismantled faster than any new settlement stabilises |
| **Transformative** | Popular-liberal reading consolidated into a durable new settlement via sustained Art. 135 use — **only if** it generates its own epistemic/juridical layers | New 4T-aligned institutions with genuine technical competence (else collapses to Fragmented) |
| **Post-national** | Transnational layers (USMCA governance, inter-American rights system) partly substitute for decoupled national layers | The 2026 anti-intervention provisions of Art. 40 read as a *defence against* precisely this trajectory |

---

## 6. Reproducibility chain

Every substantive claim in the article is designed to be located on the following chain (the project's "Ruling Book" canon). This protocol makes the mapping explicit:

```
THEORY        → Premises P1–P6, thesis T0
   ↓
ONTOLOGY      → Plural social ontology; community layers (Table 3)
   ↓
LEGITIMACY    → CLV; Pegoraro & Rinella sources (Tables 1a / 1b)
   ↓
ALTERITY      → Todorov's three planes (Table 2)
   ↓
MECHANISM     → constitutive / reproductive / transformative / disruptive (§ 4.4)
   ↓
INDICATOR     → CLV component ↑/↓; coupling status (Table 3)
   ↓
VERIFICATION  → DOF decrees, CPEUM articles, SCJN rulings (Table 4; primary sources § 7)
   ↓
FORESIGHT     → five trajectories (§ 5 above)
```

A claim that cannot be located somewhere on this chain is treated as incomplete.

---

## 7. Primary sources (canonical, not mirrored)

To keep the record current, primary legal sources are **linked**, not copied, so readers always reach the canonical version:

- **CPEUM (current consolidated text):** Cámara de Diputados — <https://www.diputados.gob.mx/LeyesBiblio/index.htm> (reference version used: *Últimas Reformas DOF 02-06-2026*)
- **Reform decrees:** *Diario Oficial de la Federación* — <https://www.dof.gob.mx> (dates in `../data/table4_reform_chronology.csv`)
- **Reform chronology:** Cámara de Diputados reform history — <https://www.diputados.gob.mx/LeyesBiblio/ref/cpeum_crono.htm>

---

*This protocol is released into the public domain (CC0 1.0) to maximise reuse. The article text (AAM) remains under CC BY-NC 4.0.*
