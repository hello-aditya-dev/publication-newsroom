# LLM Pricing Dataset

Purpose: maintain source-backed model API pricing for research and future public data products.

## Suggested fields

```json
{
  "provider": "",
  "model": "",
  "model_version": "",
  "pricing_unit": "USD per 1M tokens",
  "input": null,
  "cached_input": null,
  "output": null,
  "batch_input": null,
  "batch_output": null,
  "context_window": null,
  "effective_date": "",
  "source_url": "",
  "accessed_at": "",
  "notes": ""
}
```

## Rules

- Never infer missing prices.
- Keep effective date.
- Preserve old records when pricing changes.
- Distinguish provider price from reseller/aggregator price.
- Note region/tier/commitment conditions when material.
- Do not compare token prices without noting differences in model capability and billing rules.
