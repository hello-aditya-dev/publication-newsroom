# Research Sources

## Primary research discovery

- arXiv — https://arxiv.org/
- OpenReview — https://openreview.net/
- Papers with Code / Hugging Face papers may aid discovery, but trace important claims to the
  original paper/repository.
- Conference proceedings and official project pages when available.
- Originating laboratory/university repositories.
- GitHub repository linked by the paper authors.

## Paper-reading protocol

Never report a paper from its title or abstract alone when the claim depends on methodology.

Capture:

1. research question;
2. authors/institutions;
3. version/date;
4. dataset;
5. experimental setup;
6. baseline selection;
7. metric definitions;
8. main result;
9. ablations;
10. limitations;
11. code/data availability;
12. whether claims exceed the evidence.

## Preprints

State when work is a preprint and not peer reviewed if that distinction is material.

## Benchmarks

Ask:
- Is the benchmark saturated?
- Is contamination possible?
- Is the comparison zero-shot/few-shot/fine-tuned?
- Are model versions identical to public versions?
- Are prompt/tool settings comparable?
- Are confidence intervals or variance reported?
- Is the evaluator model-based?
- Are costs/latency excluded from the headline result?

## Replication

Independent reproduction is stronger evidence than a self-reported score.
