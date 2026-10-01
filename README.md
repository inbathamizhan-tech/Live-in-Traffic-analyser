<div align="center">


# Live-in-Traffic-analyser

### Real-time traffic intelligence for drivers, commuters, and planners

<p>
  <a href="https://github.com/inbathamizhan-tech/Live-in-Traffic-analyser"><img src="https://img.shields.io/github/stars/inbathamizhan-tech/Live-in-Traffic-analyser?style=for-the-badge&color=0ea5e9&label=STARS" alt="GitHub stars" /></a>
  <a href="https://github.com/inbathamizhan-tech/Live-in-Traffic-analyser/issues"><img src="https://img.shields.io/github/issues/inbathamizhan-tech/Live-in-Traffic-analyser?style=for-the-badge&color=f59e0b&label=ISSUES" alt="Open issues" /></a>
  <a href="https://github.com/inbathamizhan-tech/Live-in-Traffic-analyser/blob/main/LICENSE"><img src="https://img.shields.io/badge/Status-Active%20development-22c55e?style=for-the-badge" alt="Project status" /></a>
</p>

<p>
  <strong>Live maps</strong> · <strong>Real-time alerts</strong> · <strong>Traffic analytics</strong> · <strong>Mobile-friendly</strong>
</p>

</div>

---

## Overview

**Live-in-Traffic-analyser** is a Pan-India traffic monitoring platform designed to make live road conditions easier to understand and act on. It brings maps, incident reporting, alerts, and analytics into one experience for people who move through — and plan around — busy roads.

The project is focused on building a practical real-time system: traffic data should be visible, timely, and useful whether someone is checking a route on the move or studying broader traffic patterns.

## Why this project?

Traffic information is often fragmented across maps, alerts, and local reports. This project explores how a single, responsive platform can combine those signals into a clearer operational picture for:

- **Drivers** planning or adjusting a route
- **Commuters** checking conditions before they travel
- **Planners** looking at traffic behaviour and incident patterns

## Core capabilities

| Capability | What it provides |
| --- | --- |
| **Live traffic maps** | A map-first view of current road conditions and traffic flow |
| **Incident reporting** | A way to surface disruptions, incidents, and local events |
| **Traffic alerts** | Timely information for drivers and commuters |
| **Traffic analytics** | Data-driven views for understanding traffic patterns |
| **Real-time updates** | Fast updates through a WebSocket-powered communication layer |
| **Responsive experience** | A mobile-friendly interface for use on the go |

## Technology stack

### Frontend

- **Next.js** — application framework and routing
- **React** — component-based user interface
- **TypeScript** — typed application development
- **Leaflet / Mapbox** — interactive maps and geospatial visualization

### Real-time and backend

- **Node.js** — server-side application services
- **WebSockets** — real-time event delivery and live updates

### Data

- **PostgreSQL** — relational application data
- **PostGIS** — geospatial data and location-aware queries
- **Redis** — fast-access data and real-time support

## High-level flow

```text
Traffic signals and reports
            ↓
   Backend services + APIs
            ↓
     WebSocket event layer
            ↓
  Maps · alerts · analytics UI
```

## Product principles

- **Real-time first:** information should stay current as conditions change.
- **Map-led clarity:** location and context should be visible at a glance.
- **Actionable information:** alerts should help people decide what to do next.
- **Mobile-friendly by default:** the experience should work for people on the move.
- **Scalable foundations:** geospatial data, caching, and event delivery should be considered from the start.

## Planned directions

- Expand coverage across more cities and traffic corridors
- Improve incident categorisation and reporting workflows
- Add richer historical traffic analysis and trend views
- Improve alert preferences and location-based notifications
- Continue refining map performance for mobile devices

## Repository

- **Repository:** [inbathamizhan-tech/Live-in-Traffic-analyser](https://github.com/inbathamizhan-tech/Live-in-Traffic-analyser)
- **Default branch:** `main`
- **Project type:** Real-time traffic monitoring and analytics platform

## Connect

Built by **[Inba Thamizhan](https://github.com/inbathamizhan-tech)**.

- [GitHub profile](https://github.com/inbathamizhan-tech)
- [LinkedIn](https://www.linkedin.com/in/inbathamizhan-k-2a5712431)

<div align="center">

### Making traffic data more visible, useful, and timely.

</div>
