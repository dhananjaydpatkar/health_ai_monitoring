

# Clinical AI Shadow-Mode Monitoring Platform (India)

> [!WARNING] 
> **Not a Proposal, Pitch Deck, or Sacred Prophecy:** Put down the procurement forms—this is neither a formal proposal nor an official recommendation. It is merely an unfiltered brain dump of my own ramblings, parked here before my memory garbage-collects it, in the wildly optimistic hope that someday someone (even future me) finds it vaguely useful.

A governance-led, privacy-preserving monitoring platform enabling **multi-centric shadow-mode evaluation of healthcare AI solutions** across Indian hospitals—eliminating centralized patient data pooling bottlenecks while rigorously evaluating clinical accuracy, operational behavior, safety & risk, evidence generation quality, and cost/scale-readiness.

---

## Core Documents & Authoritative Criteria Registry

| Resource | Purpose & Audience | Link |
| :--- | :--- | :--- |
| **Evaluation Metrics Explorer** *(External Authoritative Registry)* | Interactive single source of truth for all category-specific evaluation criteria, One-Time Onboarding Gates, Ongoing Monitoring metrics, formulas, input sources, and target benchmarks across all 5 pillars. | [Evaluation Metrics Explorer](https://catch-evals.s3.ap-south-1.amazonaws.com/Evaluation_Metrics_Explorer.html) |
| **2-Page Executive Summary** | Boardroom-ready brief covering the India multi-centric data challenge, shadow-mode paradigm shift, 5-pillar governance architecture, and post-pilot pathways. | [summary.md](./summary.md) |
| **Detailed Architecture & Monitoring Framework** | Comprehensive blueprint detailing objectives, stakeholder model, pre-deployment ethics/IT gates, 5-pillar & two-cadence governance (referencing the Metrics Explorer), cross-check reconciliation, telemetry hook APIs, drift monitoring, scheduled reports, and phased implementation roadmap. | [architecture_and_framework.md](./architecture_and_framework.md) |

---

## Visual Diagrams & Animations

> **Note:** All images, dashboard mockups, and animations in `images/` and `animations/` are representative visuals; wherever metrics, case counts, or charts are shown, they use dummy/illustrative data points only.

### Architecture & Governance Diagrams (`images/`)
- **[Paradigm Shift: Centralized Pooling vs. Shadow-Mode Monitoring](./images/india_data_paradigm_shift.png)** — Why moving AI to hospitals in shadow mode resolves DPDP, IEC/IRB, and heterogeneity friction in India.
- **[5-Pillar & Two-Cadence Evaluation Architecture](./images/five_pillars_framework.png)** — High-level overview of the 5 monitoring pillars, 5 clinical solution categories, and One-Time vs. Ongoing cadences anchored to the Evaluation Metrics Explorer.
- **[Reference System Architecture](./images/platform_system_architecture.png)** — Zero-PHI-egress Hospital Edge Zone connected via mTLS webhooks to the Sovereign Central Monitoring Platform.
- **[Real-Time Executive Dashboard Mockup](./images/executive_dashboard_mockup.png)** — Illustrative multi-site live monitoring view with sensitivity drift curves, site-wise 5-pillar heatmap, reconciliation breakdown, and scheduled executive alerts.
- **[End-of-Pilot Decision Matrix & Vendor Loop](./images/pilot_decision_matrix.png)** — Go / Conditional-Go / No-Go scale-up governance alongside the AI vendor diagnostic improvement loop.

### Interactive Process Animations (`animations/`) — *Credits: Google Gemini 4*
- **[Shadow-Mode Live Data Flow & Cross-Check Engine](./animations/shadow_mode_data_flow.gif)** — Animated dual-path clinical vs. shadow AI flow showing concordant verification and discordant blinded adjudication. *(Animation credit: Google Gemini 4)*
- **[End-to-End Platform Lifecycle](./animations/end_to_end_platform_lifecycle.gif)** — Animated walkthrough separating **Stage 0 (One-Time Platform Governance Prerequisite + Periodic Revision Loop)** from the repeatable **5-Stage Per-Solution / Per-Pilot Lifecycle** (Enlistment → Hospital Selection → Ethics/IT Readiness → Multi-Month Shadow Run → Scale-Out or Rework). *(Animation credit: Google Gemini 4)*
- **[Multi-Month Telemetry & Drift Simulation](./animations/multi_month_telemetry_drift.gif)** — 24-week multi-hospital pilot showing automated detection of a Tier-3 hardware calibration shift, vendor patch deployment, and scheduled monthly executive reports. *(Animation credit: Google Gemini 4)*
