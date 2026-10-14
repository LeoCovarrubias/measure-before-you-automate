# Measure Before You Automate

A reading of Paystand's *AI Playbook for Finance 2027* (*Playbook de IA para finanzas 2027*) from the Mexican context, documented as a short research paper.

This is not original primary research. It is a critical reading of a commercial document, checked against public sources (KPMG, Centro México Digital and UNAM, the SAT, PwC, specialized press). It is independent and has no relationship with Paystand, KPMG, or any institution cited.

## The paper

[PDF](paper.pdf) · [LaTeX source](paper.tex)

**Abstract.** Of thirteen playbook claims checked against public sources, seven are confirmed outright, two with reservations, one arithmetic example is correct, and three could not be fully confirmed or need qualification. The central finding: 71% of finance leaders perceive that AI meets their return expectations, yet only 7% of organizations, in Mexico as in the world, have consolidated that return. The distance between the two figures is the distance between perceiving and measuring.

## Three tensions

1. **Perceiving is not consolidating.** 71% (perception, finance leaders at companies with revenue of at least about MXN 5,000 million) versus 7% (consolidated return, 2,000+ leaders across all functions, revenue above about MXN 1,000 million).
2. **The denominator of adoption.** 75%, 26%, 8.4%, 31.5%, and 6.2% describe different universes. Large Mexican financial institutions adopt AI about five times more than small ones.
3. **Model and rule.** Each category is judged by its own yardstick: calibration for the model, automatic application rate and exception handling for the rule.

## Practical principles

1. Instrument before you buy.
2. Distinguish the model from the rule.
3. Design the audit trail before automating.
4. Read each figure against its denominator.
5. Verify the rule with whoever answers for it.

## Methodological note

No original data and no client or employer data are used. Several figures were checked against specialized press rather than the primary document, and the paper details which. Two regulatory points (the SAT's bank-data cross-check and automatic invitation letters) could not be fully confirmed, and the 2027 Tax Mailbox date appears to mark the start of the penalty rather than the obligation. Nothing here is tax or financial advice.

## Build

```bash
latexmk -pdf paper.tex
```

## License

MIT, see [LICENSE](LICENSE).
