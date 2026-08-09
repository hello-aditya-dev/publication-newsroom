# Durable Decisions

This file records decisions that future sessions must treat as project constraints until explicitly
changed.

---

## 2026-08-09 — Separate newsroom and website repositories

**Decision:** Editorial operations live in a private `publication-newsroom` repository. Public
website/product code lives in a separate repository.

**Rationale:** Editorial IP, unpublished research, internal decisions, and operational memory should
not be coupled to production code.

**Consequence:** Do not put public-site implementation work here unless explicitly requested.

---

## 2026-08-09 — Repository is the agent's persistent memory

**Decision:** Z.ai's lack of native long-term project memory is handled through explicit repository
files.

**Rationale:** Version-controlled memory is inspectable, reversible, portable, and independent of
the agent vendor.

**Consequence:** Every substantive session must read the relevant memory before work and update
`CURRENT_STATE.md` when finished.

---

## 2026-08-09 — Initial editorial focus

**Decision:** Focus first on AI infrastructure, compute, semiconductors, cloud/developer
infrastructure, and cybersecurity.

**Rationale:** These beats can support technically differentiated reporting and commercially
valuable professional audiences.

**Consequence:** Avoid broad general technology coverage unless the scope is deliberately changed.

---

## 2026-08-09 — Human approval is mandatory

**Decision:** No story may be published autonomously.

**Rationale:** Editorial accountability, accuracy, security, and reputation require a human gate.

**Consequence:** `queue/approved.md` may only reflect explicit human approval.

---

## 2026-08-09 — Primary sources first

**Decision:** Material claims should be grounded in primary evidence whenever available.

**Rationale:** The publication must add analysis rather than become a rewrite layer over other news.

**Consequence:** Secondary reporting may aid discovery/context, but important technical claims
should be traced to authoritative originals.

---

## 2026-08-09 — Quality over volume

**Decision:** Do not optimize for maximum article count or scaled SEO pages.

**Rationale:** The publication is intended to win trust through information gain and expert-level
usefulness.

**Consequence:** Kill weak stories. A rejected story is preferable to a generic article.
