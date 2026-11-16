# Research notes (checked 2026-11-16, from a non-Indian IP, via curl)

## (a) Moved or died

- **Dead/hijacked:** openbudgetsindia.org now redirects to a casino page. Dropped. CivicDataLab and CBGA pages still link to it.
- **No longer resolve (dropped):** geosadak-pmgsy.nic.in, hydro.imd.gov.in (replaced with IMD rainfall page).
- **nic.in to gov.in moves:** India Code (indiacode.gov.in), FCRA (fcraonline.gov.in), PFMS (pfms.gov.in), CPCB (cpcb.gov.in), MoRTH (morth.gov.in), NCRB (ncrb.mha.gov.in), Supremo (supremo.dopt.gov.in), MGNREGA (nrega.dord.gov.in), OMMAS (pmgsy.dord.gov.in).
- **Other moves:** NSE to nseindia.in; SAT to satweb.sat.gov.in; AAI AIM to aim-india.aai.aero.in; seismo.gov.in to riseq.seismo.gov.in; MP Bhulekh to webgis2 subdomain; PM-JAY dashboard to dashboard.nha.gov.in; Global Forest Watch to globalnaturewatch.org.
- rchiips.org/nfhs returns 404; NFHS entry uses nfhsiips.in.

## (b) Unsure

- **ECI pages** (electoral bonds, statistical reports): site is a JavaScript shell that returns 200 for any path, so the paths are not machine-verified. Dropped the party contribution reports entry for this reason. Check in a browser.
- **Meta transparency URLs (2), archive.today, IDSP:** blocked or timed out, and not confirmed by search. URLs are from prior knowledge.
- **Lok Dhaba:** appears to be down, not just blocked.
- **New gov.in addresses** for Supremo, OMMAS, PFMS, FCRA and PM-JAY were found by trying likely hosts; they load with the right titles but were not confirmed by an official notice.
- Dropped DILRMP (timed out, unconfirmed).
- "access" values are from prior knowledge plus page loads, not from running each search form.
- Total is 183, above the 120-160 target; trim weaker state entries if needed.

## (c) Prior art on GitHub

| Repo | Last push | Size |
|---|---|---|
| [paulpogoda/OSINT-Tools-India](https://github.com/paulpogoda/OSINT-Tools-India) | 2026-10-19 | 64 stars, ~50 links |
| [OSINT-for-countries/OSINT_in_India](https://github.com/OSINT-for-countries/OSINT_in_India) | 2026-05-28 | 4 stars, ~100 links |
| [mrsmartpants/india-public-datasets](https://github.com/mrsmartpants/india-public-datasets) | 2015-01-14 | 1 star, stale; link count not measured |

Off GitHub: a Start.me "OSINT India" page (start.me/p/aLe0vp/osint-india), which paulpogoda's README says has broken links. Most other GitHub hits for "India OSINT" are phone-number lookup tools, which our rules exclude.
