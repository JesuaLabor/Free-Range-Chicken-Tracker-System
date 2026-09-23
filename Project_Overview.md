PROJECT PROPOSALE
Free-Range Chicken (Meat Production)Tracker System
A Company Enabled Flock Management Platform


1. Introduction
Small-to-medium poultry operations — including those organized under cooperatives — largely rely on paper logs or memory to track flock health, feeding, and productivity. This makes it difficult to catch problems early, measure performance accurately, or make informed decisions at the farm or cooperative level. This proposal outlines a digital tracking system designed to close that gap.
2. Problem Statement
Without structured, timely data:
Mortality spikes often go unnoticed until they've already caused significant loss
Desired bird quality - weight at desired age, body build, animal health condition and meat quality are difficult to achieve
Company management and farm owners lack visibility into performance without manually checking each farm
Technology protocols as prescribed, are hard to track whether they are religiously implemented by Growers
There is no consolidated way to assess whether a given batch is actually profitable
3. Objectives
Digitize periodic flock record-keeping in a way that's fast enough for real field use
Give farm owners clear, data-driven visibility into their own operations
Give Company Management a consolidated view across all grower farms
Give platform administrators the ability to manage the system in order to improve the supply chain management
Reduce preventable losses through timely alerts (mortality spikes, farm mismanagement, grower pole-vaulting, etc)
4. Target Users & Roles
Role
Responsibility
Super Admin
Manages the platform — cooperatives, user accounts, system-wide configuration
Company Chief Technical Officer
Oversees all grower farms under the Company — consolidated reporting and status
Farm Owner / Grower
Manages their own farm(s) — batches, staff, day-to-day operations
Logs daily field data — feed, mortality, eggs, weight
Company Chief Technical Officer
Reviews health logs and manages vaccination/treatment plans for assigned farms
5. Proposed Solution
A role-based system split across two access points suited to how each role actually works:
Website (Progressive Web App) — used by Super Admins, Cooperative Chairmen, Farm Owners, and Veterinarians. Built as a PWA so it's installable on desktop or mobile, works with intermittent connectivity, and can send push notifications for alerts — without needing separate native apps for each management role
Android app — used by Caretakers/Workers for fast, offline-capable daily logging directly from the coop
Core Features
Farm and coop/batch management (breed, hatch date, initial headcount)
Daily field logs: feed given, water, mortality with cause, egg count, periodic weight sampling
Vaccination and medication scheduling with automated reminders
Dashboards: mortality rate, viewable per batch, per farm, per cooperative, and platform-wide
Expense tracking with profit/loss calculation per batch
Automated alerts for mortality spikes, escalatable up the role hierarchy
Company-level rollup reporting 
Platform-wide administrative controls for Super Admin
6. Organizational Structure (Data Hierarchy)
Super Admin (platform-wide)
└─ Cooperative (Chairman)
    └─ Farm (Farm Owner)
        └─ Coop / Batch
            ├─ Daily Logs
            ├─ Weight Samples
            ├─ Vaccination Records
            └─ Expenses
7. Expected Benefits
Earlier detection of mortality issues, reducing preventable losses
Clear, comparable performance data across batches and farms
No missed technology protocol breach due to automated scheduling and reminders
Company-wide visibility for reporting — useful for harvest volume and market demand projections
Installable, low-friction access for management roles via PWA, without the overhead of maintaining separate native apps
8. Open Decisions
Whether the Cooperative Chairman can drill into individual caretaker-level logs, or is limited to aggregated views
Whether Super Admin operates through a dedicated back-office interface or an elevated view within the Chairman's website
9. Implementation Phases
Phase
Focus
Phase 0 — Foundation
Core data structures and role-based access setup
Phase 1 — MVP
Android logging app and single-farm PWA dashboards
Phase 2 — Health & Scheduling
CTO views, animal health and weight tracking
Phase 3 — Cost & Oversight
Expense tracking, alerts,Company roll-up dashboard
Phase 4 — Platform Maturity
Super Admin back-office, offline sync hardening, public launch


