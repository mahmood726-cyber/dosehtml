# E156 Protocol — `dosehtml`

This repository is the source code and dashboard backing an E156 micro-paper on the [E156 Student Board](https://mahmood726-cyber.github.io/e156/students.html).

---

## `[45]` Dose Response Pro: Browser-Based Dose-Response Meta-Analysis Matching R Accuracy

**Type:** methods  |  ESTIMAND: Dose-response trend coefficient  
**Data:** 120 R dosresmeta benchmark datasets

### 156-word body

Can browser-based dose-response meta-analysis match the numerical accuracy of established R packages while providing interactive visualization? Dose Response Pro v18.1 is a 10,022-line single-file HTML application implementing the Greenland-Longnecker two-stage method for dose-response meta-analysis with linear, quadratic, and restricted cubic spline models, plus leave-one-out sensitivity analysis. The tool provides interactive dose-response curve plotting, CSV import with flexible column detection, R code export for reproducibility checks, and a command-line interface for batch processing alongside the browser application. Strict benchmarking against the R dosresmeta package showed exact parity on 120 of 120 comparable datasets with a median runtime speedup of 1.92x over the R implementation. Deterministic CLI validation confirmed three-of-three passed checks including grid-based coefficient verification against independently computed reference values. This demonstrates that client-side JavaScript can deliver publication-quality dose-response synthesis with performance exceeding dedicated statistical environments. However, the limitation of exploratory spline model status means complex non-linear relationships require independent validation before clinical interpretation of inflection points.

### Submission metadata

```
Corresponding author: Mahmood Ahmad <mahmood.ahmad2@nhs.net>
ORCID: 0000-0001-9107-3704
Affiliation: Tahir Heart Institute, Rabwah, Pakistan

Links:
  Code:      https://github.com/mahmood726-cyber/dosehtml
  Protocol:  https://github.com/mahmood726-cyber/dosehtml/blob/main/E156-PROTOCOL.md
  Dashboard: https://mahmood726-cyber.github.io/dosehtml/

References (topic pack: browser-based meta-analysis tooling):
  1. Schwarzer G, Carpenter JR, Rücker G. 2015. Meta-Analysis with R. Springer. doi:10.1007/978-3-319-21416-0
  2. Viechtbauer W. 2010. Conducting meta-analyses in R with the metafor package. J Stat Softw. 36(3):1-48. doi:10.18637/jss.v036.i03

Data availability: No patient-level data used. Analysis derived exclusively
  from publicly available aggregate records. All source identifiers are in
  the protocol document linked above.

Ethics: Not required. Study uses only publicly available aggregate data; no
  human participants; no patient-identifiable information; no individual-
  participant data. No institutional review board approval sought or required
  under standard research-ethics guidelines for secondary methodological
  research on published literature.

Funding: None.

Competing interests: MA serves on the editorial board of Synthēsis (the
  target journal); MA had no role in editorial decisions on this
  manuscript, which was handled by an independent editor of the journal.

Author contributions (CRediT):
  [STUDENT REWRITER, first author] — Writing – original draft, Writing –
    review & editing, Validation.
  [SUPERVISING FACULTY, last/senior author] — Supervision, Validation,
    Writing – review & editing.
  Mahmood Ahmad (middle author, NOT first or last) — Conceptualization,
    Methodology, Software, Data curation, Formal analysis, Resources.

AI disclosure: Computational tooling (including AI-assisted coding via
  Claude Code [Anthropic]) was used to develop analysis scripts and assist
  with data extraction. The final manuscript was human-written, reviewed,
  and approved by the author; the submitted text is not AI-generated. All
  quantitative claims were verified against source data; cross-validation
  was performed where applicable. The author retains full responsibility for
  the final content.

Preprint: Not preprinted.

Reporting checklist: PRISMA 2020 (methods-paper variant — reports on review corpus).

Target journal: ◆ Synthēsis (https://www.synthesis-medicine.org/index.php/journal)
  Section: Methods Note — submit the 156-word E156 body verbatim as the main text.
  The journal caps main text at ≤400 words; E156's 156-word, 7-sentence
  contract sits well inside that ceiling. Do NOT pad to 400 — the
  micro-paper length is the point of the format.

Manuscript license: CC-BY-4.0.
Code license: MIT.

SUBMITTED: [ ]
```


---

_Auto-generated from the workbook by `C:/E156/scripts/create_missing_protocols.py`. If something is wrong, edit `rewrite-workbook.txt` and re-run the script — it will overwrite this file via the GitHub API._