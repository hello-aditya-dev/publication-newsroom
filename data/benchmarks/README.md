# Benchmark Registry

Purpose: keep benchmark results with enough experimental context to prevent misleading comparisons.

## Required context

```json
{
  "benchmark": "",
  "benchmark_version": "",
  "subject": "",
  "result": null,
  "unit": "",
  "hardware": "",
  "software": "",
  "precision": "",
  "batch_size": null,
  "concurrency": null,
  "input_length": null,
  "output_length": null,
  "run_by": "",
  "independent": false,
  "date": "",
  "source_url": "",
  "methodology_url": "",
  "notes": ""
}
```

A naked score without methodology is not a useful benchmark record.
