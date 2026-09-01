# Leveraging AI Tools for Academic Research: A One-Week Boot Camp
*2026-08-31 00:00 PDT*

A short workshop for faculty researchers who want AI tools to
make their whole workload faster (bibliographies, project
scaffolding, drafting) without making it riskier. Five days,
one chapter each, plus an appendix on faculty-specific
considerations (grant writing, teaching policy, trainee
authorship, IRB/data confidentiality).

## Structure

- **Day 1** Foundations: How LLMs Work and Where They Fit in
  Research
- **Day 2** Literature Review and Synthesis with AI Tools
  (leads with efficient bibliography compilation)
- **Day 3** AI-Assisted Coding and Data Analysis (leads with
  scaffolding a reproducible project)
- **Day 4** Writing, Editing, and Citation Management with AI
  (leads with outlining via chatbot dialog)
- **Day 5** Reproducibility, Provenance, and Responsible Use
  in Publication
- **Appendix** Considerations for Faculty and Principal
  Investigators

Each day is approximately 1 hour of lecture content + 2 hours
of homework with worked solutions. No examinations.

## Build

```bash
quarto render
```

The cover is generated procedurally:

```bash
Rscript images/build-cover.R
```

## Position in the series

This workshop is the AI-tools volume in the rgtlab curriculum
sequence. It draws on the preparatory boot camps and the
reproducibility infrastructure volume:

- *R for Biostatistics*: preparatory R
- *Git and GitHub for Biostatistics*: preparatory version
  control, used here for AI-use provenance
- *Biostatistics Practicum*: workflow infrastructure (Git in
  depth, Docker, renv, Quarto, CDISC)
- *Reproducible Research for the Health Sciences*: the
  reproducibility core, extended here to cover AI provenance
  and disclosure

## License

Prose: CC BY-NC-ND 4.0. Code: CC0 1.0.
