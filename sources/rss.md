# Feed / Monitoring Registry

Phase 0 uses manual or agent-assisted discovery. Do not build automation solely because this file
exists.

This file is the canonical registry for sources we may eventually monitor through RSS/Atom,
changelogs, release feeds, or polling.

## Registry schema

When a feed is confirmed, add:

```yaml
- name:
  category:
  webpage:
  feed_url:
  source_tier: A
  checked_at:
  status: active
  notes:
```

## Starter webpages to inspect for feed support

### AI
- https://openai.com/news/
- https://www.anthropic.com/news
- https://deepmind.google/discover/blog/
- https://ai.meta.com/blog/

### Compute
- https://nvidianews.nvidia.com/
- https://www.amd.com/en/newsroom.html

### Cloud
- https://aws.amazon.com/blogs/
- https://cloud.google.com/blog
- https://blog.cloudflare.com/

### Security
- https://www.cisa.gov/news-events/cybersecurity-advisories
- https://github.com/advisories

### Research
- https://arxiv.org/

## Rule

Do not invent an RSS URL from a site's hostname. Verify that the feed exists before recording it as
active.
