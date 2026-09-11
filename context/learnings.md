# Learnings

## 2026-09-11 first Grok run

- irata.org/jobs currently shows IRATA head-office technical/audit vacancies, not field tech jobs.
- TTR employment page still has many listings dated March–May 2026. Treat each date as a possible stale flag; do not drop the board.
- Aerones careers still lists Europe RAT rows but marks them “Posted 1 year ago”. US Denton RAT is recent. Do not log the old Europe rows as new dated ads.
- Tesla Gigafactory Berlin L2 listing still appears on Indeed; LinkedIn says applications closed. Do not log as open.
- Baltic DIA Germany wind campaign on Net-Empregos had start “until 15 August 2026” — past. Do not log as live.
- Eurosafe werkenbijeurosafe.nl lists a Rope Access Technician card but the filtered list returned no items. Standing employer, not a confirmed live ad.
- Rigg Access single-job pages are JS templates; WebFetch often returns placeholders. Use category pages + search snippets, then say if the body could not be opened.
- Bilfinger jobs.bilfinger.com confirmed a live NL Height Specialists RAT with IRATA training offered.
- SPIE Wind Bremen blade-rope ads are active on Indeed DE under ref 2026-1495 / German twin title.
- Scope this run reached specialist boards + ES, FR (light), UK (light), NL, DE, PT aggregator, SE (TTR). Not a full pass on NO, DK, IT, PL, RO, CH, AT, BE, IE, LU.

## 2026-09-11 correction — Altrad Rotterdam IRATA 1

- LinkedIn job 4396578339 now redirects to an expired-job page (`trk=expired_jd_redirect`). User confirmed posted ~5 months ago and applications closed.
- First-run mistake: treated a LinkedIn search snippet + Expertini/Careerjet/Glassdoor mirrors as “recent” because Glassdoor said “3d”. Aggregators recycle closed ads. Live vs closed must be read on the actual apply page.
- Keep Altrad Benelux as a company-watch (they hire IRATA 1 for inspection/insulation). Do not list that URL as an open vacancy.
- Rule added: if LinkedIn says closed / expired redirect / “no longer accepting”, log as Company watch, not Live.

## 2026-09-11 pass 2

- ANETVA is the biggest new source vs pass 1. Sep 2026 cards = Live-on-board; Feb–Jun = Unverified date.
- IRATA.org field ads exist this week (two UK L3 window-cleaning cards). Not only HQ.
- Bilfinger UK careers: painters + NDT L1 Tiffany (1409711133) + multi-NDT radiographer. Do not mix with L3 Team Leader slug.
- Italy: search `su fune` / `operatore su fune`. 2High, BlackLine, Edilfuni.
- Finn.no opened: most TT ads expired (frist utløpt). Hytech electro deadline 31 Aug 2026 past. Still a useful NO query.
- PL/RO: Eventus watch only; OLX/eJobs informal; Jan–Mar eJobs telecom-alpinist already expired.
- France: 350+ cordiste ads, mostly interim. Océlian/VINCI Saint-Nazaire is the named-employer CDI to keep.
- Do not invent ANETVA detail URLs when only the index row is visible.
- Boards still thin: emploi-cordiste body, lalineavertical, CareerStructure, DK, CH, BE, LU, IE, AT, PT portals.
