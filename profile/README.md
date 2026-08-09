<div align="center">

# 🗺️ Shadow Economy Map
### *See the Economy That No One Measures*

[![Status](https://img.shields.io/badge/Status-Active%20Development-orange)]()
[![Project](https://img.shields.io/badge/INSA-Summer%20Camp-blue)]()
[![License](https://img.shields.io/badge/License-MIT-green)]()
[![Version](https://img.shields.io/badge/Version-0.1.0-lightgrey)]()

---

An AI-powered geospatial platform that detects emerging economic activity in Ethiopia using free, publicly available satellite and mobility-derived data — surfacing growth signals before they show up in official statistics.

</div>

---

# 📖 Overview

Shadow Economy Map is built around a simple idea: **Ethiopia's real economic activity is happening faster than official statistics can track it.** New construction, population inflows, and rising commercial density are visible in satellite and mobility data long before they show up in a business registry or a census cycle.

The project combines free, high-frequency data sources — night-time lights, built-up area change, estimated relative wealth, and real-time news signals — into a single composite growth score, mapped across grid cells and viewable over time, with AI used to make that data explorable and easy to understand.

The long-term vision is a nationwide platform serving banks, investors, real estate firms, government agencies, and NGOs. We're building toward that vision one deliberate, provable version at a time — see **Where We're Headed** below.

---

# ❗️ Problem Statement

Ethiopia's economic growth is largely invisible to the tools that would normally track it.

Formal economic indicators — business registrations, tax records, census data — are slow, incomplete, or difficult to access at a granular level. Meanwhile, real economic activity is happening now, especially in fast-urbanizing areas around Addis Ababa. Banks, investors, developers, and government planners are working with outdated or incomplete pictures of where growth is actually happening — particularly outside a handful of well-documented central districts.

By the time official statistics confirm a neighborhood is growing, the opportunity to act on it early has already passed.

---

# 💡 Our Approach

We detect, we don't guess. The growth we surface has already happened on the ground — we just see the physical and economic evidence of it, in satellite and public data, faster than news coverage or official statistics catch up and confirm it publicly.

Four data sources feed a single composite growth score per area:

- **VIIRS Night-Time Lights** — activity intensity over time
- **GHSL (Global Human Settlement Layer)** — built-up area expansion, population growth
- **Meta Relative Wealth Index (RWI)** — estimated economic/wealth proxy
- **GDELT** — real-time news signals, used to independently validate our findings

Every score is explorable, not a black box — anyone can inspect the raw signals behind it, and we publish validated case studies showing the method actually works against real, independently confirmed growth.

---

# 🗺️ Where We're Headed

We're building this as a sequence of deliberate versions, each one proving something real before the next is attempted — not a single leap from idea to finished platform.

| Stage | Focus |
|---|---|
| **Detection Core** | Public, account-free growth detection for Addis Ababa — proving the core signal is real |
| **Identity & Requests** | Optional accounts, custom report requests |
| **Monetization** | Paid reports, alerts, payment integration |
| **API & Scale** | Paid API access, a second city, institutional dashboards |
| **Forecasting & National Platform** | True forecasting and nationwide coverage — dependent on ground-truth data partnerships that don't yet exist |

We're currently focused entirely on proving the first stage well before building toward the rest. Full detail lives in our roadmap documentation.

---

# ✨ What the Platform Does

- Public, account-free interactive growth-score map
- Time-slider to explore how growth signals change over time
- Click-to-inspect any area to see the underlying signal breakdown, an AI-generated plain-language summary, and recent trend
- Natural-language search — ask the map a question in plain English
- Independently validated case studies with supporting evidence and before/after imagery
- Full methodology transparency — how the score works, and its known limitations, documented in plain language

**Planned for later stages:** nationwide coverage, true predictive forecasting, custom paid analysis and reports, API access, and a full multi-segment commercial platform.

---

# 👥 Project Team

| Name | ID |
|------|------|
| Adonay Chilotu | CTC-1611-26 |
| Abrham Teramed | CTC-3158-26 |
| Amira Niguse | CTC-2988-26 |
| Aneni Kidanu | CTC-1451-26 |
| Abenezer Getamesay | CTC-2279-26 |
| Anteneh Wondwosen | CTC-286-26 |

---

# 🛠 Technology Stack

- **Data & Pipeline:** Python, Google Earth Engine (VIIRS, GHSL access), GDELT API, Meta RWI (static dataset)
- **Backend:** Node.js or Python (FastAPI), REST API
- **Database:** PostgreSQL (plain, no PostGIS extension for the current stage)
- **Frontend:** React-based interactive map (e.g., Mapbox GL / Leaflet)
- **AI:** LLM API integration for plain-language summaries and natural-language map search
- **Auth:** JWT-based admin authentication
- **Hosting/Infra:** Docker

---

# 📄 Documentation

- Problem & Solution Statement
- Functional & Non-Functional Requirements
- Use Cases
- Database & Data Model
- Version Roadmap
- API Specification *(in progress)*
- System Architecture *(planned)*
- UI/UX Design *(planned)*
- Testing & Evaluation *(planned)*

---

# 🌍 Vision

To build a live, trustworthy view of Ethiopia's real economy — one that surfaces where growth is happening as it happens, not months or years after the fact, and that makes overlooked areas as visible as the ones everyone already watches.

---

<div align="center">

### 🚀 Mapping Growth Before the Statistics Catch Up

**Shadow Economy Map**

*See the economy that no one measures.*

</div>
