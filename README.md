# 🎓 Grok Bot: Campus Opportunities Database Builder
### Automated Event Scraping, Sorting, and Structured CSV Telemetry

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![MLH Challenge](https://img.shields.io/badge/MLH%20GHW-Challenge%205-blue.svg)](https://www.mlh.com/events/global-hack-week-open-source-90/challenges)

> Built for **MLH Global Hack Week Hacktoberfest: CHALLENGE 5: Build a Campus Opportunities Database**. Demonstrates autonomous event calendar harvesting, chronological sorting, and audit logging into structured formats (`campus-opportunities.csv`).

---

## 📌 Mission & Workflow Overview

Grok Bot inspects public event schedules and compiles a verified opportunities table:
- **Source Portal**: `https://events.mlh.com/events/14553-global-hack-week-open-source`
- **Output Destination**: `campus-opportunities.csv`
- **Required Columns**: `Event`, `Date and time`, `Location`, `Audience`, `Registration URL`, `Source URL`, `Checked at`
- **Sorting Rule**: Chronological by date/time ascending.

---

## 📂 Deliverables in this Repository

- **Database Export**: `campus-opportunities.csv` (5 verified events, all 7 required columns)
- **Chat Completion Evidence**: `screenshots/grok_bot_database_completion_chat.png`
- **Sorted Table Evidence**: `screenshots/sorted_campus_opportunities_table.png`

---

## 📄 License
MIT License. Created by [Li-Qifeng](https://github.com/Li-Qifeng) for MLH Global Hack Week 2026.
