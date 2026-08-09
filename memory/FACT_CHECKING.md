# Fact-Checking Policy

## Purpose

Verification is an adversarial stage.

The verifier should assume the draft may contain mistakes, stale data, hidden assumptions, unit
errors, or claims that grew stronger during writing.

## Claim classes

Tag consequential claims mentally or in a fact-check record as:

- **F — Confirmed fact**
- **V — Vendor/party claim**
- **E — Estimate/calculation**
- **A — Analysis/inference**
- **U — Unverified/uncertain**

Publishable prose should make the distinction clear even when these literal labels are not shown.

## What must be checked

### Identity
- company/product/model names;
- version numbers;
- people/titles when relevant;
- dates;
- release status.

### Numbers
- units;
- currency;
- percentages;
- ratios;
- memory capacity;
- bandwidth;
- power;
- throughput;
- latency;
- pricing;
- benchmark scores;
- time windows.

### Calculations
Recalculate independently.

Record:
- formula;
- input values;
- units;
- assumptions;
- rounding.

### Comparisons
Ensure:
- same metric;
- same units;
- comparable test conditions;
- comparable product/version;
- no cherry-picked denominator.

### Quotes
Check exact wording against the source.

### Causality
Do not turn correlation or timing into causation.

### Superlatives
"fastest", "first", "largest", "only", "most efficient" require unusually strong evidence and
careful scope.

## Benchmark verification checklist

For every benchmark claim, identify:
- benchmark name/version;
- hardware;
- software stack;
- model/workload;
- precision;
- batch size if relevant;
- input/output length if relevant;
- concurrency if relevant;
- latency/throughput definition;
- who ran the test;
- whether results are independently reproducible.

If conditions differ, do not present a simple ratio as apples-to-apples.

## Security claims

For vulnerabilities:
- verify identifier;
- affected versions;
- exploitation status;
- vendor advisory;
- severity source;
- patch/mitigation status;
- disclosure date.

Do not overstate exploitability from a severity score alone.

## Fact-check outcome

Each material claim is one of:

- PASS
- PASS — vendor claim clearly labeled
- PASS — estimate with assumptions
- NEEDS REVISION
- UNSUPPORTED
- CONFLICTING EVIDENCE

A draft cannot be "verified" while central claims remain UNSUPPORTED.

## Corrections after publication

When new evidence appears, distinguish:
- normal update;
- clarification;
- factual correction;
- changed conclusion.

Material corrections should be visible to readers.
