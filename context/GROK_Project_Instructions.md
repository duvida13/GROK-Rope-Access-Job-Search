# Grok project instructions — Europe rope-access job search

Living brief for **this** project only.  
Repo: `duvida13/GROK-Rope-Access-Job-Search`  
Updated: 2026-09-11

This file replaces the old portable brief for day-to-day work. Keep the old brief only as a terms/portals archive. Do not follow its Obsidian, CV-tailoring, experience-bank, or “source of truth for per-job CVs” sections.

---

## Goal

Find as many **real** rope-access and closely adjacent jobs across Europe as possible, verify them, and log them so Luis can act.

Maximize findings. Do not pre-filter by IRATA level. Do not hide blade / offshore / industrial / construction rope work.

One working pile. Do not create a second tracker. Write only to this Grok repo. The other two GitHub repos belong to other AIs — read them for “already seen” or method if useful, never commit to them.

---

## Candidate (enough for search, not a CV rewrite)

- Name: Luis Fernandes
- Portuguese citizen, full EU work rights
- IRATA Level 1 (working toward 2) — **level is a note, not a search filter**
- Also holds GWO BST, GWO Blade Repair, BOSIET, advanced rigging and scaffolding tickets
- Hands-on trades: rope access, rigging, scaffolding, mechanical / construction
- Languages: Portuguese native, English fluent, Spanish intermediate
- Relocating from Australia to Europe

Honest gaps (do not invent past them):

- No genuine turbine **service / blade composite / nacelle** history. Wind work was construction-phase rigging in Portugal. Blade ads are still in scope.
- No North Sea oil & gas platform history. Closest is marine / port rope access in Australia.
- Do not call him IRATA 2 or 3.

He uses **one or two standard CVs**. Do not build a new CV per job.

---

## In scope

- Industrial rope access (IRATA / FISAT / SOFT / ANETVA / CQP / SPRAT / “su fune” / cordiste / Industriekletterer / tilkomstteknikk / reparbetare / alpinism utilitar / acesso por cordas / trabajos verticales)
- Wind: blade repair, blade technician, LPS, composite repair, Rotorblatt, pás / palas — when the work is on ropes
- Offshore and onshore industrial: inspection, insulation, coatings, rigging-on-ropes, steeplejack, NDT **only if the posting itself requires rope access / IRATA**
- Construction / façades / roofs / industrial maintenance on ropes
- Agencies, company career pages, specialist boards, national portals
- Stretch titles (L2/L3, supervisor) — log them, do not drop them
- Closed ads that still name a useful employer — log as **Company watch**, not as live vacancies

## Out of scope

- Invented jobs, companies, URLs, salaries, or tickets
- Per-job tailored CVs
- Writing into the other AI repos or their Obsidian vaults
- Logging NDT / inspector / railway / sales / office roles just because the employer also does ropes
- Treating aggregator “posted 3 days ago” as proof the apply button is open
- Logging in to Luis’s LinkedIn

---

## How to search (every run)

1. English baseline first, every country: **rope access** and **IRATA**.
2. Then the local term for that country.
3. Then specialist boards and employer career pages.
4. Open the actual posting (or employer page) before calling it live.
5. If a country or board was not opened, say so in the run summary. Do not imply a full Europe sweep.

### Local terms

| Country | Use after the English baseline |
|---|---|
| France, Wallonia, French Switzerland | cordiste |
| Italy | su fune / in fune / tecnico fune — never “cordista” |
| Germany, Austria, German Switzerland | Industriekletterer — not Seilzugangstechniker |
| Portugal | acesso por cordas — not generic “trabalhos em altura” |
| Spain | trabajos verticales / técnico vertical / ANETVA or IRATA |
| Norway | tilkomstteknikk |
| Sweden | reparbetare |
| Denmark | erhvervsklatrer / IRATA |
| Poland | alpinista przemysłowy / technik dostępu linowego + IRATA |
| Romania | alpinism utilitar |
| Netherlands | English is enough; local translations failed |
| Ireland, UK, Luxembourg, Belgium (Flanders) | English baseline + IRATA |

Disguised titles to catch: Blade Repair, Blade Technician, LPS inspection, composite repair, Rotorblatt, pás, palas.

### Boards that usually pay off

- irata.org/jobs
- rigg-access.com category pages (`/jobsbycat/rope-access-jobs/1` and wind/rigging cats)
- ttrinternational.com ofertas / employment
- anetva.org/bolsa-de-empleo (open each card; stale and live sit together)
- offres.emploi-cordiste.fr
- jobs.bilfinger.com
- jobs.rts-wind.de
- lalineavertical.com
- karrierestart.no and finn.no
- candidat.francetravail.fr and hellowork.com (FR pages may 403 to bots — that is not “dead”)
- net-empregos.com with `chaves=acesso+por+cordas`
- Country Indeed sites — search the **country name**, not only a city
- Employer pages beat Indeed / Glassdoor / Careerjet / Expertini dates

### Known traps

- LinkedIn logged-out dies after ~6 results. Ask Luis to paste/share extra LinkedIn hits.
- LinkedIn expired redirect = closed. Keep the company if useful.
- DWP findajob keeps expired UK ads.
- InfoJobs.it is shut down. Use it.indeed.com.
- jobs.ch “cordiste” is watchmaking noise. Use team.jobs / web search for CH.
- Jobindex.dk fuzzy-matches “access”.
- Source language ≠ worksite country (Romanian ad for NL, Polish ad for Iceland, etc.). Log the **worksite**.
- Multi-country campaigns (SWIRE, Aerones, similar): one lead per country.
- Acrobatica sales / office titles are not rope jobs. Hands-on “muratore / operaio / cordiste urbain” can be.

---

## What to write for each job

Mandatory:

- Company
- Exact title
- Country + city/site if known
- Direct URL
- Short **English** summary (even if the ad is not in English)
- English usable: yes / no / mixed / unclear
- IRATA / local cert asked (or “not stated” / “they train”)
- Blade: yes / no
- Status: **Live** | **Company watch** | **Unverified date**
- Date this run found it

Status rules:

- **Live** — employer page or apply path still open, or a dated board card that was opened and did not say closed.
- **Company watch** — ad closed / expired / “applications no longer accepted”, but the employer hires rope access. Useful later.
- **Unverified date** — board card has an old or missing date (TTR March–May cards, “posted 1 year ago”). Do not sell it as a new vacancy.

Never invent a URL. If you cannot capture one, say so and do not fake it.

---

## Repo layout

```
GROK-Rope-Access-Job-Search/
  README.md
  context/
    GROK_Project_Instructions.md   ← this file
    candidate.md
    rules.md
    search-terms.md
    portals.md
    learnings.md
    Portable_Job_Search_Brief.md   ← archive only
  finds/
    YYYY-MM-DD.md                  ← one file per run
```

`finds/` is the page Luis opens. One file per calendar day. If a second pass happens the same day, append to that file with a clear “second pass” heading. Do not start a parallel spreadsheet unless he asks.

After a run, also append 3–8 lines to `context/learnings.md`: what worked, what was stale, what was not opened.

---

## Run summary (always)

At the top of the day’s finds file:

- Date
- Countries actually opened
- Portals actually opened
- How many Live / Company watch / Unverified
- Explicit **not opened** list
- Terms that newly worked or failed

Default next-run start (unless Luis names a slice): countries and boards still thin — Norway, Denmark, Italy, Poland, Romania, Switzerland, Austria, Belgium, Ireland, Luxembourg, ANETVA detail cards, emploi-cordiste listings, Finn / karrierestart, France Travail / Hellowork detail, company pages for Altrad, Bilfinger, RTS, SPIE, Rope Access Sverige, Sky-Work, RT9, 2High, ISLA/EST.

---

## Rigour bar (after the Altrad miss)

A search snippet is a candidate. It is not a live job until the apply page or employer page is read.

If LinkedIn / Indeed / Glassdoor disagree, the apply page wins.

Closed ≠ worthless. Closed + real rope-access employer = Company watch.

---

## What Luis still has to supply

- LinkedIn results he can see while logged in (anonymous search is capped)
- Which of two CVs is the default apply file
- Whether a given Company-watch name is worth a speculative email
- Anything already applied / already in the other AIs’ daily files that he wants deduped by URL
