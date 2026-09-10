# Grok project instructions — Europe rope-access job search

Living brief for **this** project only.  
Repo: `duvida13/GROK-Rope-Access-Job-Search`  
Updated: 2026-09-11 (system section: queries first, employer list is memory)

This file replaces the old portable brief for day-to-day work. Keep the old brief only as a terms/portals archive. Do not follow its Obsidian, CV-tailoring, experience-bank, or “source of truth for per-job CVs” sections.

---

## Goal

Find as many **real** rope-access and closely adjacent jobs across Europe as possible, verify them, and log them so Luis can act.

Maximize findings. Do not pre-filter by IRATA level. Do not hide blade / offshore / industrial / construction rope work.

One working pile. Do not create a second tracker. Write only to this Grok repo. The other two GitHub repos belong to other AIs — read them for “already seen” or method if useful, never commit to them.

**Do not treat a short agency list as the search.** The market is hundreds of employers. The other pipelines already surfaced **1,000+ distinct company names** across ~2,280 URL records. A list of 15–30 names cannot cover Europe. The list is a *memory of who has hired*, not the engine that finds the next unknown firm.

---

## The system (this is the point of this file)

An AI reading this file should run a **coverage machine**, not a favourite-employer tour.

Learned from the other two repos (read-only):

- Claude `rope-access-job-search`: daily digests + `state/seen_jobs.json` (~2,280 URLs, ~1,043 company strings). Volume comes from repeating queries on Indeed + national boards + specialist boards, then remembering URLs.
- ChatGPT repo: weekday country rotation + a public job index with stable IDs + a source register of portals per country. That is closer to a system. Their company list is still only a seed.
- Both overlap and both miss. Do not copy their finds into our `finds/` as if we discovered them. Use their URLs as a seen set. Use new company names as careers-page seeds.

### Four layers — run in this order

1. **Query layer** — finds companies we do not know yet. For each country in today’s slice: English `rope access` + `IRATA`, then the local term, then blade/LPS titles, on open web + Indeed (country-level) + that country’s national portal.
2. **Board layer** — every run: IRATA, Rigg Access, TTR, ANETVA, emploi-cordiste.fr, lalineavertical.com, CareerStructure.
3. **Employer-memory layer** — grow `context/employers.md` from verified finds (name, country, careers URL if seen, last checked). Recheck frequent hirers on a cadence. Never invent URLs. Memory is not a cap.
4. **Dedup / honesty layer** — one campaign = one job. Closed = Company watch. No date = Unverified. Already in another AI repo = re-list only if confirmed still live.

### Coverage rhythm

Specialist boards every run. Plus at least four of NL, DE, FR, ES, UK, NO.
Rotate the tail: Mon UK/IE; Tue DE/AT; Wed FR/IT; Thu PT/ES; Fri PL/RO; Sat UK/DE/offshore; Sun CH/BE/LU/DK/SE + employer-memory sweep.

Complete brief = an AI can rebuild the machine from this file. Complete ≠ pasting 1,043 company names here.

---

## Candidate (enough for search, not a CV rewrite)

- Luis Fernandes, Portuguese citizen, EU work rights, IRATA Level 1 (note, not a filter), GWO BST + Blade Repair, BOSIET, advanced rigging/scaffolding.
- Languages: PT native, EN fluent, ES intermediate.
- One or two standard CVs. No per-job CVs. Do not call him L2/L3. Blade ads stay in scope.

## How to search (every run)

Not a single English Google dump. Each country: (1) `rope access` + `IRATA` (2) local term (3) disguised blade titles (4) boards + careers.

| Country | Local term |
|---|---|
| FR / Wallonia / French CH | cordiste |
| IT | su fune / in fune / tecnico fune |
| DE / AT / German CH | Industriekletterer |
| PT | acesso por cordas |
| ES | trabajos verticales / técnico vertical |
| NO | tilkomstteknikk |
| SE | reparbetare / reptekniker |
| DK | erhvervsklatrer |
| PL | alpinista przemysłowy / technik dostępu linowego |
| RO | alpinism utilitar |
| NL, UK, IE, LU, BE-Flanders | English + IRATA |

Log each job with URL, English summary, language, cert, blade yes/no, status Live | Company watch | Unverified date.
Write to `finds/YYYY-MM-DD.md` only in this repo.
