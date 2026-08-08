<div align="center">

# 🗺️ Shadow Economy Map
### *See the Economy That No One Measures*

[![Status](https://img.shields.io/badge/Status-Draft-orange)]()
[![Project](https://img.shields.io/badge/INSA-Summer%20Camp-blue)]()
[![License](https://img.shields.io/badge/License-MIT-green)]()
[![Version](https://img.shields.io/badge/Version-0.1.0-lightgrey)]()

---

An AI-powered geospatial platform that detects emerging economic activity in Ethiopia using free, publicly available satellite and mobility-derived data — surfacing growth signals before they show up in official statistics.

</div>

---

# 📖 Overview

Shadow Economy Map is a geospatial growth-signal platform built around a simple idea: **Ethiopia's real economic activity is happening faster than official statistics can track it.** New construction, population inflows, and rising commercial density are visible in satellite and mobility data long before they show up in a business registry or a census cycle.

This project combines free, high-frequency data sources — night-time lights, built-up area change, estimated relative wealth, and real-time news signals — into a single composite growth score, mapped across grid cells and viewable over time. The long-term vision is a nationwide platform serving banks, investors, real estate firms, government agencies, and NGOs. The current MVP proves the concept for a single city: Addis Ababa.

---

# ❗️ Problem Statement

Ethiopia's economic growth is largely invisible to the tools that would normally track it.

Formal economic indicators — business registrations, tax records, census data — are slow, incomplete, or difficult to access at a granular level. Digitization efforts exist but are recent and not yet reliable enough to serve as clean, bulk data sources. Meanwhile, real economic activity — new construction, population inflows, rising commercial density — is happening now, especially in fast-urbanizing areas around Addis Ababa.

Banks, investors, real estate developers, and government planners making decisions about where to invest, lend, or build infrastructure are working with outdated or incomplete pictures of where growth is actually happening, particularly outside a handful of well-documented central districts.

The core gap: by the time official statistics confirm a neighborhood is growing, the opportunity to act on it early has already passed — and areas outside the best-mapped, wealthiest zones are systematically under-visible in the data that does exist.

---

# 💡 Proposed Solution

### 🌍 Grand Vision
A nationwide geospatial platform that detects **and eventually predicts** emerging economic activity across Ethiopia, using an evolving mix of satellite, mobility, and public data. At full scale, it serves multiple paying customer segments — banks, investors, real estate companies, government agencies, and NGOs — through a live platform with subscriptions, premium reports, and API access.

### 🎯 MVP (Current Focus)
A growth-**detection** tool for **Addis Ababa only**, built entirely on four free, high-frequency, publicly accessible data sources:

- **VIIRS Night-Time Lights** — activity intensity over time
- **GHSL (Global Human Settlement Layer)** — built-up area expansion, population growth
- **Meta Relative Wealth Index (RWI)** — estimated economic/wealth proxy
- **GDELT** — real-time news signals for validation

These combine into a single composite growth score per grid cell, explorable on an interactive map with a time-slider, and validated against a small set of independently verifiable, known-growth locations in Addis Ababa.

**What the MVP does *not* do:** it does not forecast future prices or hotspots, does not use business-registration data as ground truth, and does not cover areas outside Addis Ababa. See `1. Problem & Solution Statement` for the full scope discussion.

---

# ✨ Features

### MVP Features (this release)
- Public, account-free interactive growth-score map of Addis Ababa
- Time-slider to explore how growth signals change over time
- Click-to-inspect grid cells showing the underlying signal breakdown
- Raw vs. composite layer toggle for transparency
- Independently validated case studies with supporting evidence
- Admin area for data pipeline management and case-study curation
- Mobile-responsive public map

### 🔭 Grand Vision Features (future work)
- Nationwide coverage
- True predictive forecasting of future hotspots
- Additional data sources (traffic, business registrations, social trends) as they become reliably accessible
- Multi-segment commercial platform: subscriptions, premium reports, API access
- Live, continuously updated data pipeline

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

# 🚧 Project Status

> **Current Phase:** Foundational Documentation (Draft)

The project has completed its core planning documentation and is preparing to move into system design.

**Completed:**
- [x] Problem & Solution Statement
- [x] Functional & Non-Functional Requirements
- [x] Use Cases
- [x] Database & Data Model

**Upcoming milestones:**
- API Specification
- System Architecture
- UI/UX Design
- Data Pipeline Development
- Frontend Dashboard Development
- Testing & Validation
- Deployment

---

# 🛠 Technology Stack

> To be finalized — reviewed at design time.

Expected/likely technologies include:

- **Data & Pipeline:** Python, Google Earth Engine (VIIRS, GHSL access), GDELT API, Meta RWI (static dataset)
- **Backend:** Node.js or Python (FastAPI), REST API
- **Database:** PostgreSQL with PostGIS (geospatial support)
- **Frontend:** React-based interactive map (e.g., Mapbox GL / Leaflet)
- **Auth:** JWT-based admin authentication (no public user auth required)
- **Hosting/Infra:** Docker

---

# 🏗 System Architecture

> Coming Soon — to be documented following the Database & Data Model doc.

---

# 📱 Screenshots

> Dashboard mockups and application screenshots will be added during development.

---

# 📄 Documentation

- [x] 1. Problem & Solution Statement
- [x] 2. Functional & Non-Functional Requirements
- [x] 3. Use Cases
- [x] 4. Database & Data Model
- [ ] 5. API Specification
- [ ] System Architecture
- [ ] UI/UX Design
- [ ] Testing & Evaluation
- [ ] User/Admin Manual

---

# 🌍 Vision

To build a live, trustworthy view of Ethiopia's real economy — one that surfaces where growth is happening as it happens, not months or years after the fact, and that makes overlooked areas as visible as the ones everyone already watches.

---

<div align="center">

### 🚀 Mapping Growth Before the Statistics Catch Up

**Shadow Economy Map**

*See the economy that no one measures.*

</div>
