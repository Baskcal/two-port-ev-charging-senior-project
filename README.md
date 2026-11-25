# Two-Port EV Charging Senior Project

Shared documents for a senior project on allocating limited building power between two EV charging requests. The project is still in progress. The proposed implementation uses a simulator and an isolated low-voltage two-channel bench model.

## Which file should I open?

| Status | File | Purpose |
| --- | --- | --- |
| **Final template** | [Senior Project template_Final Version.docx](<template/Senior Project template_Final Version.docx>) | Formatting and report-structure template. It is **not** the finished project report. |
| **Main work in progress** | [Senior Project Working Draft - Public Copy.docx](<drafts/Senior Project Working Draft - Public Copy.docx>) | Current manuscript snapshot. Some template placeholders and unfinished sections remain. Student ID numbers are withheld in this public copy. |
| **Current related-work draft** | [EV Charging Related Work - Revised with ML.docx](<drafts/EV Charging Related Work - Revised with ML.docx>) | Most recent Sections 2.2–2.3 draft, including the proposed machine-learning forecasting extension. Review before merging into the main manuscript. |
| **Previous related-work draft** | [EV Charging Related Work - Revised.docx](<drafts/EV Charging Related Work - Revised.docx>) | Earlier edited version, kept for comparison. It does not include the ML study. |
| **Raw research draft** | [Elicit related-work output](<research/Elicit - EV Charging Related Work Ranking and Draft Sections 2.2–2.3.docx>) | Elicit's initial ranking and generated text. It contains working notes and citation issues; use the revised draft above for current prose. |
| **Concept brief** | [02_Two_Port_EV_Charging_Proposal.pdf](<proposal/02_Two_Port_EV_Charging_Proposal.pdf>) | Proposed technical scope and evaluation plan, dated 6 November 2026. Plans may change as the project develops. |

The [research screenshots](research/) show search results from **Kira's Pawn**. They are search leads, not verified references. The writing tool itself is maintained in its [separate GitHub repository](https://github.com/NasirAldeen/kiras-pawn).

## Current project direction

- Share a changing charging-power budget between two ports while respecting site and port limits.
- Compare equal allocation, departure-aware allocation, and a forecast-assisted method using the same scenarios.
- Record building load and charging-session data. Evaluate whether a small learning model improves near-term load forecasts and charging outcomes against simple forecasts.
- Enforce the power limit from current measurements even when forecasts are wrong.
- Use simulation for any three-phase constraints; the bench hardware demonstrates shared-supply allocation at low voltage.

The documents describe proposed methods, not completed experiments or measured performance.

## Public-copy note

The local working draft is actively edited in Word. The copy here is a saved snapshot prepared for public sharing; its student ID numbers were removed. The local original was not changed. When the team updates the manuscript, publish a new reviewed snapshot so readers can distinguish it from the current one.
