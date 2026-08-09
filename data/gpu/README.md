# GPU / Accelerator Dataset

Purpose: maintain source-backed specifications and availability for compute analysis.

## Suggested fields

```json
{
  "vendor": "",
  "product": "",
  "architecture": "",
  "form_factor": "",
  "memory_type": "",
  "memory_capacity_gb": null,
  "memory_bandwidth_tb_s": null,
  "interconnect": "",
  "tdp_w": null,
  "supported_precisions": [],
  "availability_status": "",
  "announced_at": "",
  "source_url": "",
  "accessed_at": "",
  "notes": ""
}
```

## Rules

- Use vendor documentation for published specs.
- Keep SKU distinctions.
- Do not merge board-level and rack/system-level power.
- Do not calculate theoretical performance unless formula and inputs are preserved.
- Treat roadmap specs as roadmap specs, not shipped-product facts.
