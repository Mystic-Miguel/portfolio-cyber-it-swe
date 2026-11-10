# Miguel Rowe — Software Engineering & Cybersecurity Portfolio

A responsive portfolio focused on real software engineering, backend development, practical web applications, and defensive cybersecurity learning.

## Live preview

After deployment, open the homepage at the portfolio site's root URL and use **Try the SOC triage lab** to explore the interactive security demonstration.

## Run locally

Open `index.html` in a browser, or from this folder run:

```bash
python3 -m http.server 8000
```

Then visit http://localhost:8000 and http://localhost:8000/soc-lab.html.

## Selected work

- **Security Signal Lab** — original local-only browser demonstration that supports synthetic event review, filtering, notes, triage status updates, safe CSV/JSON import, and CSV export.
- **FORGE Performance Tracker** — deployed browser-based fitness tracking prototype, with a separate live Vercel project.
- **FastAPI Task API** — Python FastAPI/Pydantic CRUD endpoints, UUID identifiers, health check; currently uses in-memory persistence.
- **Omon Braids** — responsive salon website and sample booking flow, not connected to a production booking/payment backend.
- **Night-time Emergencies** — HTML/CSS multi-page site, with additional frontend framework experiments.
- **Resume Matcher** — TF-IDF cosine similarity command-line tool (not a production ATS scorer).
- **URL Uptime Monitor** — requests-based CLI for logging URL response times and status codes to CSV.
- **Barracks Car Hunter** — car shopping and shortlist prototype; external provider integrations may be incomplete.
- **CSV → Parquet ETL** — Pandas CSV ingestion, deduplication, string trimming and Parquet export.

This site deliberately excludes aspirational claims about unbuilt functions. Status descriptions reflect inspected source or existing deployments.

## Security lab data policy

The SOC-style lab contains **synthetic sample alerts** only. CSV/JSON import is processed in the visitor's browser. No analytics or network collection is included in the site. It is not a production security information and event management (SIEM) platform or intrusion detection system. Investigations and notes last for the current browser session; users can export the filtered dataset to CSV.

Limit imports to 1MB/500 records. Avoid uploading private company logs or operational data to unreviewed tools. Conduct cybersecurity testing only in environments you own or are authorized to test.

## Deployment

This is a static site: `index.html`, `soc-lab.html` and `favicon.svg`. No build command or environment credentials are required.

## Source

GitHub: https://github.com/Mystic-Miguel/portfolio-cyber-it-swe
