# Dhananjoy Mahato

**Final-Year BTech CSE, GD Goenka University, Gurugram (Class of 2027)**
**Aspiring Data Engineer** — I build ETL pipelines and data-backed applications with Python and SQL.

Open to remote Data Engineering internships (India / worldwide).

---

## About

Final-year Computer Science student focused on data engineering. I design end-to-end pipelines — extraction from APIs and live feeds, transformation and data-quality checks in pandas, idempotent loads into SQLite and PostgreSQL, and SQL analysis — and I ship them as live dashboards and web applications. My final-year major project, PlacePrep AI, is deployed and in use.

## Technical Skills

| Area | Skills |
| --- | --- |
| Languages | Python, SQL, Java, JavaScript, TypeScript |
| Data Engineering | ETL pipeline design, pandas, data-quality checks, data modelling, idempotent loads |
| Databases | PostgreSQL, SQLite |
| Web Development | FastAPI, Next.js, React, Tailwind CSS |
| Tools | Git, GitHub, Vercel |

## Featured Projects

### [PlacePrep AI](https://github.com/dxhanjay/PlacePrep-AI) — Real-Time AI Mock Interview & Resume Analyzer
Final-year major project, deployed and live: [placeprep-ai-cyan.vercel.app](https://placeprep-ai-cyan.vercel.app)

- JWT authentication, resume PDF upload, and an ATS score against any pasted job description, with matched and missing skills shown per resume
- Mock interviews in four tracks (Data Engineering, Python + SQL, DSA, HR) with per-answer scoring, plus a voice mode built on the Web Speech API
- A readiness score blending resume and interview performance, an analytics view (score trend, recurring gaps), and a role-guarded TPO cohort view
- Stack: Next.js, FastAPI, PostgreSQL (Supabase), Vercel — Sprints 1–5 complete, data persisted in Supabase

### [Open-Data ETL Pipeline](https://github.com/dxhanjay/open-data-etl-pipeline)
A complete, reproducible ETL pipeline for Delhi weather data.

- **Extract:** Open-Meteo API into an untouched raw layer (168 hourly records per run)
- **Transform:** pandas cleaning under explicit rules, with data-quality checks for duplicates, gaps and ranges that fail loudly
- **Load:** idempotent upserts into SQLite and PostgreSQL — re-runs add zero duplicates (verified)
- **Analyse:** 10 SQL queries using GROUP BY, CTEs, LAG, rolling averages and RANK window functions, with findings documented in the repository

### [Earthquake ETL Pipeline](https://github.com/dxhanjay/earthquake-etl-pipeline)
An end-to-end ETL pipeline on live USGS earthquake data (M2.5+), with a live dashboard: [earthquake-etl.vercel.app](https://earthquake-etl.vercel.app)

- **Extract:** USGS GeoJSON feed into a raw layer; **Transform:** pandas with explicit data-quality checks (a non-earthquake "explosion" event was caught and removed)
- **Load:** SQLite with idempotent upserts on the USGS event id — re-runs add zero duplicates (verified)
- **Analyse and present:** 8 SQL queries (strongest, deepest, most-felt, regional patterns) rendered into a self-contained HTML dashboard generated from the database
- **Historical mode:** USGS FDSN archive backfill in ≤31-day chunks, deduplicated by event id — October 2026 backfilled to 2,127 events (strongest: M7.7, Panama)

### [Live AQI Dashboard](https://github.com/dxhanjay/live-aqi-dashboard)
A real-time air-quality ETL pipeline for 12 Indian cities, live at [live-aqi-dashboard-dun.vercel.app](https://live-aqi-dashboard-dun.vercel.app)

- **Extract:** Open-Meteo (CAMS) hourly PM2.5/PM10; **Transform:** pandas with data-quality checks, and Indian AQI computed from the official CPCB breakpoint formula rather than a black-box API number
- **Load:** SQLite with idempotent upserts on (city, timestamp) — re-runs add zero duplicates (verified)
- **Present:** live dashboard with a featured-city panel, CPCB scale bar, worst-to-cleanest ranking, and a location-aware view that finds the nearest tracked city or fetches live AQI for exact coordinates

## Additional Projects

- **[InvoiceFlow](https://github.com/dxhanjay/invoiceflow)** — professional invoice generator with live A4 preview, vector PDF export and local persistence (Next.js, TypeScript, Tailwind). Live: [invoiceflow-smoky.vercel.app](https://invoiceflow-smoky.vercel.app)
- **[Image Colorization](https://github.com/dxhanjay/Image-colorization-)** — deep-learning model that colourises grayscale images (Python, OpenCV, TensorFlow)
- **[Netflix UI Clone](https://github.com/dxhanjay/Netflix-project)** — streaming interface built with HTML, CSS and JavaScript using TMDB API data

## Experience

**Project Trainee — Steel Authority of India Limited (SAIL), Bokaro Steel Plant** · May – Jul 2026
Completed 8 weeks of practical training (11 May – 3 Jul 2026). Built a static web page using HTML and CSS as the training project. Overall performance assessed as "GOOD".

## Currently

- Deepening SQL (window functions, data modelling) and ETL design patterns; Spark and Airflow are next on the learning path
- Daily DSA practice in Python on LeetCode (1 SQL + 1 DSA problem a day)
- Preparing for GATE 2028 (Computer Science)

## Contact

- LinkedIn: [linkedin.com/in/dhananjoy-mahato-303462272](https://www.linkedin.com/in/dhananjoy-mahato-303462272)
- LeetCode: [leetcode.com/u/dhananjay81](https://leetcode.com/u/dhananjay81)
- Email: dhananjoy377@gmail.com
