# Partner Portal — Lead-Management & Telecalling CRM

I built this for **Rent A Roof**'s partner/agent team — a lean, focused portal to work a lead list end to end: upload contacts, call through them, qualify, book site visits, and keep the follow-ups honest. It was a fast turnaround as a one-man team, design through deploy, driven end to end through agentic AI workflows — deliberately light, the kind of tool a small team actually keeps open all day.

The screenshots are from a demo build — a placeholder brand, dummy data and placeholder staff accounts stand in for the real branding and credentials, which I keep out of the public repo.

*The source is in a private repo; happy to share it with a serious reviewer on request.*

---

## What it does

- **Contacts → leads** — upload a contact list (from the main CRM or a spreadsheet) and work it as a live pipeline.
- **Telecalling** — log call attempts and outcomes (interested / callback / not-picked / wrong-number), notes and attempt counts, with a "stale after N days" nudge.
- **Qualification & stages** — move leads New → Contacted → Qualified → Visit Scheduled → Visited → Closed / Lost, with disqualify and revive paths.
- **Site visits & meetings** — schedule visits and meetings, track status, keep a field calendar.
- **Follow-ups** — everything due, in one queue.
- **WhatsApp templates** — ready-to-send messages for common replies.
- **Monitor & activity** — an admin board over the team's calling activity, plus per-agent activity and role-based access.

---

## Screenshots

**Leads** — the pipeline: filters, stages, call outcomes, budgets
![Leads](screenshots/d-leads.png)

**Dashboard** — contacts to call, active leads, visits, source breakdown
![Dashboard](screenshots/d-dashboard.png)

**Contacts** ![Contacts](screenshots/d-contacts.png)
**Follow-ups** ![Follow-ups](screenshots/d-follow-ups.png)
**Meetings** ![Meetings](screenshots/d-meetings.png)
**Monitor** — admin view over calling activity ![Monitor](screenshots/d-monitor.png)

### Mobile
| Dashboard | Leads | Contacts |
|---|---|---|
| ![](screenshots/m-dashboard.png) | ![](screenshots/m-leads.png) | ![](screenshots/m-contacts.png) |

| Follow-ups | Meetings | Monitor |
|---|---|---|
| ![](screenshots/m-follow-ups.png) | ![](screenshots/m-meetings.png) | ![](screenshots/m-monitor.png) |

---

## Tech
Laravel 13 · Blade · Alpine.js · Tailwind CSS · MySQL · PHP 8.4 · custom auth · role-based access

---
Developed by **[@abBytes-sudo](https://github.com/abBytes-sudo)** for Rent A Roof · abhimasih0505@gmail.com · +91 73039 37702
