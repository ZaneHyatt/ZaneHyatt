# Zane Hyatt

Currently a Customer Support Developer at Airbyte.  
I spend most of my time working with APIs, debugging data pipelines, and building connectors — and outside of that, I like writing code that automates things or makes systems easier to reason about.

I’m generally interested in:
- automation
- infrastructure
- data movement
- making unreliable systems behave predictably

---

## What I Like Building

- Small tools that remove manual work
- Scripts that turn messy data into something usable
- API integrations (especially the annoying ones)
- Systems that can run without being babysat
- Things that log enough information to actually debug later

---

## A Recent Example

I wrote a crawler for unstable APIs that don’t behave nicely with pagination.

Instead of assuming the API is reliable, it:
- detects whether cursor-based pagination actually works
- falls back to offset pagination when needed
- does a second “healing pass” if records might have been missed
- prioritizes **at-least-once delivery over perfect efficiency**

The core idea is simple: don’t trust the API, design around its failure modes.

---

## Projects

### IT Analytics Platform
Internal system for collecting and organizing operational data across different services.

- API data collectors (Python)
- PostgreSQL for structured storage
- FastAPI for visibility
- Dockerized services
- Focus on observability and reliability

---

### IT Health Dashboard
A simple interface for understanding system state across multiple services.

- Aggregated metrics
- Daily + rolling reporting
- Built for quick debugging, not just visuals

---

### Employee Lifecycle Automation
Handles onboarding/offboarding across multiple systems.

- Google Workspace + API integrations
- Reduced repetitive admin work
- Designed to fail safely instead of silently

---

## Stack I Use Often

- Python
- PostgreSQL / SQL
- Docker
- Linux

And a lot of:
- REST APIs
- JSON
- logs

---

## Current Focus

- Better ways to debug data pipelines
- Connector development and API edge cases
- Making systems more observable
- Building tools I actually want to use

---

## Outside of Work

I still code for fun — usually small scripts, experiments, or trying to understand how something breaks.
