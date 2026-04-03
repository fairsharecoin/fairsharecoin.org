# FairShareCoin.org Messaging Audit (2026-04-03)

## Context / scope
- Live fetch check of `https://fairsharecoin.org` returned **500 Internal Server Error** at audit time.
- Current repo (`fairsharecoin.org`) contains only a minimal `README.md` and no page source files.
- This audit therefore provides a **content alignment plan and ready-to-paste copy** for website updates.

---

## 1) Contradictions / risk list (current public positioning)

### A. "Final" language vs active evolution
- Risk: phrases like "Fair. Final. Yours." imply immutable/finalized protocol state.
- Conflict: current reality is alpha implementation with ongoing hardening and decentralization work.

### B. Value claims ambiguity
- Risk: readers may assume FSC claims intrinsic value like commodity money.
- Preferred truth: FSC is a fairness-first medium of exchange model; value is socially/economically emergent, not intrinsic claim-marketing.

### C. Implementation authority ambiguity
- Risk: people may not know which repo is authoritative for current behavior.
- Required clarity:
  - `fairsharecoin/foundation` = active implementation baseline
  - `fairsharecoin/fairsharecoin` = concept/spec and philosophy archive

### D. Infrastructure assumptions
- Risk: messaging can sound like high-compute / mining-heavy ecosystems.
- Preferred truth: no mining race model, normal compute footprint, staged decentralization path.

---

## 2) Rewrite map by page/section

## Homepage (hero)
- Replace absolute/final wording with clear alpha-aware value statement.
- Add one sentence: FSC does not claim intrinsic value.

## Homepage ("How it works" short section)
- Add 5-step minimal flow:
  Register → identity uniqueness check path → activation → transfer/use → recovery continuity.

## Homepage (status panel)
- Add explicit status box:
  - Alpha (local-first)
  - Not production-ready
  - No real ICAO/NFC verification live yet
  - No decentralized consensus runtime live yet

## FAQ / Principles page (new or expanded)
- Add direct Q/A:
  - "Does FSC claim intrinsic value?" → "No"
  - "Why no mining?" → accessibility/fairness rationale
  - "What hardware is required?" → normal commodity hardware for current phase

## Repo map / transparency section
- Add permanent links:
  - Active implementation: `https://github.com/fairsharecoin/foundation`
  - Concept/spec archive: `https://github.com/fairsharecoin/fairsharecoin`

---

## 3) Ready-to-paste copy blocks

## A) Hero subtitle (homepage)
"FairShareCoin is a fairness-first monetary system centered on identity uniqueness, recoverability, and long-term balance."

## B) Value honesty block
"FairShareCoin does not claim intrinsic value. It is designed as a clean, fairness-oriented medium of exchange where value emerges from real human use and trust over time."

## C) Compute/decentralization block
"No mining arms race. No specialized hardware requirement as a design goal. The system is intended for accessible, normal compute environments while decentralization is phased in progressively."

## D) Minimal flow block
"Register → identity uniqueness check path (future ICAO integration) → wallet/account activation → send/receive value → recover account continuity if access is lost."

## E) Status block
"Status: Alpha (local-first)
- Not production-ready
- No real ICAO/NFC identity verification live yet
- No decentralized consensus runtime live yet"

## F) Transparency/repo map block
"Project map:
- Active implementation baseline: https://github.com/fairsharecoin/foundation
- Concept/spec archive: https://github.com/fairsharecoin/fairsharecoin
If wording conflicts, the foundation repository reflects current implemented behavior."

---

## Suggested execution order
1. Update homepage hero + value honesty + status block
2. Add repo map/transparency block
3. Add FAQ entries for intrinsic value + mining/hardware posture
4. Add minimal flow section
5. Re-audit wording for absolutes ("final", "always", "never")
