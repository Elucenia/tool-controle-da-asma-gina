<!-- ELUCENIA technical documentation · controle-da-asma-gina · en · no clinical/professional/rights approval -->

# Asthma symptom control (GINA)

[conditions, sources and permissions](https://elucenia.org/en/tools/controle-da-asma-gina)

## How to use

Use the tool in the portal or open index.html through a local HTTP server. Select the language, complete the fields and calculate.

## Inputs and units

### Daytime symptoms more than twice a week

`diurno`

### Any night waking due to asthma

`noturno`

### Reliever medication (SABA) use more than twice per week

`alivio`

### Any activity limitation due to asthma

`limit`

## Method edition

GINA strategy 2021: symptom control over 4 weeks, 4 questions; SABA reliever; 0/1–2/3–4

## Documented formula

Over the past 4 weeks, count present items: daytime symptoms \> 2×/week; night waking from asthma; SABA reliever \> 2×/week (excluding pre-exercise use); activity limitation.

0 = well controlled · 1–2 = partly controlled · 3–4 = uncontrolled.

## Limits and population

The GINA 2021 assessment calculated here covers symptom control over the past four weeks in adults and children older than 5 years, with the reliever question referring to SABA. This count does not assess the full future risk of exacerbation, lung function, comorbidities, inhaler technique or adherence. Symptom control and asthma severity are not equivalent. Adaptation of the material remains subject to the rights holder’s conditions.

## References

- [Reddel HK et al. Global Initiative for Asthma Strategy 2021: executive summary and rationale for key changes. Eur Respir J, 2022.](https://doi.org/10.1183/13993003.02730-2021)

- [Global Initiative for Asthma (GINA). Global Strategy for Asthma Management and Prevention (relatório anual).](https://ginasthma.org/reports/)

## Reproduce the technical tests

Run node test.cjs in the root directory of this repository to repeat the recorded synthetic cases. Original inputs, expectations and tolerances are preserved. Technical tests do not constitute clinical validation.

```sh
node test.cjs
```

tool.json contains sources, edition and review scope. examples.json retains synthetic inputs and expectations; results.json records the obtained results.

[Record and references](../tool.json) · [JavaScript code](../calculator.js) · [Reference cases](../examples.json) · [results.json](../results.json)

## Review and conditions of use

Independent clinical review has not been performed.

This interface is an authorial translation, not an official or certified edition. Independent clinical review, professional language review and instrument rights clearance have not been performed.

Formula or classification result. Interpretation, care and applicability depend on professional assessment and the selected source.

## License and attribution

Apache-2.0 applies only to ELUCENIA code. Rights to instruments, publications, translations and data remain with their respective holders. Preserve LICENSE and NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026
