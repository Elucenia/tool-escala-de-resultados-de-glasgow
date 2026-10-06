<!-- ELUCENIA technical documentation · escala-de-resultados-de-glasgow · en · no clinical/professional/rights approval -->

# Glasgow Outcome Scale (GOS)

[conditions, sources and permissions](https://elucenia.org/en/tools/escala-de-resultados-de-glasgow)

## How to use

Use the tool in the portal or open index.html through a local HTTP server. Select the language, complete the fields and calculate.

## Inputs and units

### Patient status

`gos`

- `1` — 1 – Death
- `2` — 2 – Persistent vegetative state: no meaningful response, sleep–wake cycles
- `3` — 3 – Severe disability: conscious but dependent on another person in daily life
- `4` — 4 – Moderate disability: independent but with residual deficits (can use transport, work in a sheltered setting)
- `5` — 5 – Good recovery: returns to normal life despite minor deficits

## Method edition

GOS/Jennett–Bond 1975: 5 categories; favorable 4–5; not the 8-category GOSE

## Documented formula

Select the category best describing the patient. Studies usually dichotomize outcomes as favorable (4 and 5) or unfavorable (1 to 3).

## Limits and population

Assesses functional outcome after brain injury, considering physical and mental disability. Record the follow-up time and the five-category edition. GOS must not be treated as equivalent to the eight-category GOSE or as a prediction from admission data.

## References

- [Jennett B, Bond M. Assessment of outcome after severe brain damage: a practical scale. Lancet, 1975.](https://doi.org/10.1016/S0140-6736(75)92830-5)

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

## Documented results

The information below preserves the method outputs for synthetic examples. It does not constitute independent clinical validation.

### 1

Severe disability (unfavorable outcome)


### 2

Moderate disability (favorable outcome)


### 3

Good recovery (favorable outcome)

