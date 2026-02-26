# Hackathon Toolkit: Education & Health Innovation

**A complete, field-tested toolkit for running ethics-integrated hackathons at university scale.**

This repository contains everything you need to organize a 3-day hackathon with mandatory ethical reasoning built into the judging criteria: event blueprint, participant guide, mentor brief, scoring rubric, a 50-problem bank, and post-event analysis methodology.

The toolkit was developed and tested at Arizona State University in 2026. Arizona-specific content (problem bank, regional data, entrepreneurship resources) is preserved as a worked example — fork the repo and adapt it to your institution and region.

---

## What's Inside

```
hackathon-toolkit/
├── templates/                  # The 4 documents you need to run a hackathon
│   ├── design-document.md      # Full event blueprint: schedule, rules, judging, team formation
│   ├── student-guide.md        # Participant-facing guide with schedule, rubric, mentor info
│   ├── evaluation-criteria.md  # 26-point binary scoring rubric
│   └── mentor-briefing.md      # One-page mentor brief: context, stations, logistics
│
├── problem-bank/               # 50 curated challenge problems
│   └── problem-bank.md         # Education × Health problems with ethical considerations
│
├── post-mortem/                # Reference case study from the 2026 ASU event
│   ├── results.md              # Final rankings and scoring methodology
│   ├── student-feedback-analysis.md   # Survey analysis, team dynamics findings, recommendations
│   └── mentor-feedback-report.md      # Mentor utilization, structural assessment
│
└── resources/                  # Post-hackathon pathways
    └── entrepreneurship-resources.md  # Example post-hackathon pathways (ASU/Arizona — adapt to your region)
```

---

## How to Use This

**Running your own hackathon:** Start with `templates/design-document.md`. It covers event structure, registration, team formation algorithm, rules, judging process, and support systems. The `evaluation-criteria.md` gives you a ready-to-use rubric. The `student-guide.md` is what you hand to participants. The `mentor-briefing.md` is what you hand to mentors.

**Building a problem bank:** `problem-bank/problem-bank.md` contains 50 example problems (Arizona education/healthcare), each with: problem statement, affected stakeholders, current inadequate solutions, regional context, global context, ethical considerations, and prototype scope. Use the structure as a template — replace the problems with challenges relevant to your domain and region.

**Learning from our mistakes:** The `post-mortem/` folder contains unfiltered analysis of what worked and what didn't. Key findings: team collaboration quality was the single largest driver of participant satisfaction (3.1-point NPS gap between effective and struggling teams), and mentor utilization had a discovery/routing problem, not a quality problem.

---

## Key Design Decisions (and Why)

These are the structural choices that shaped this hackathon. They're documented here so you can make informed decisions about what to keep and what to change.

**Pre-assigned teams of 4.** Teams were formed before the event using stratified random assignment with hard constraints (each team has at least 1 technical member, mixed experience levels). This is deliberately uncomfortable — navigating team dynamics with strangers is a core learning objective. Post-event data showed the pre-assignment model works when the matching algorithm has sufficient signal. The matching algorithm's inputs were too coarse (binary technical/non-technical). Future iterations should capture more granular skill profiles.

**Mandatory ethical framework.** Principled Innovation (PI) was not optional. It was a judging criterion worth 5 of 26 points. A 2-hour workshop on Day 1 grounded all teams in the framework before building began. 50% of students reported PI significantly shaped their approach; 19% treated it as a checkbox. The workshop quality directly predicted framework adoption — when the workshop landed, ethical reasoning followed.

**Binary scoring rubric.** Each criterion scores 1 (meets) or 0 (doesn't). This reduces inter-judge variance compared to Likert scales. 26 possible points across 8 dimensions. A minimum threshold of 10 points was required for finalist eligibility.

**Station-based mentoring.** Mentors were organized into themed stations (Education & Operations, Student Wellness, Health & AI/Tech) plus roaming mentors. Station-expertise matching scored 4.80/5. The physical layout (booth seating vs. table seating) created friction — use tables with visible station labels.

**Curated problem bank (not open-ended).** Teams selected from a pre-curated bank of 50 problems rather than defining their own. This ensures all projects are grounded in real, researched challenges with identified stakeholders. The problem bank was the highest-rated structural element (4.56/5).

---

## Adapting to Your Context

This toolkit was built for Arizona State University, with problems focused on Arizona's healthcare workforce crisis, tribal health, border health, and heat vulnerability. The regional specificity is intentional — it grounds problems in real data and real stakeholders rather than abstract challenges.

To adapt for your institution and region:

1. **Problem bank:** Replace Arizona-specific data points with your region's equivalent challenges. Keep the structure (problem statement → stakeholders → current solutions → regional context → global context → ethical considerations → prototype scope).

2. **Design document:** Update participant eligibility, venue, dates, prize structure, and organizational contacts. The schedule, rules, and judging process are transferable.

3. **Ethical framework:** Principled Innovation is ASU's framework. Substitute your institution's equivalent (responsible innovation, design ethics, value-sensitive design, etc.) — or adopt PI directly. The integration pattern matters more than the specific framework.

4. **Mentor structure:** The station-based model with expertise matching works. Adapt station themes to match your problem domains. Ensure 2–3 roaming mentors on Day 1 (we had 1, which was critically insufficient).

5. **Resources:** Replace with your institution's entrepreneurship ecosystem. The structure (accelerators, maker spaces, funding competitions, state programs) is universal.

---

## License

This work is released under the [MIT License](LICENSE). Use it, adapt it, improve it.

---

## Citation

If you use this toolkit, a link back is appreciated but not required:

```
ScaleU + PI Academy Hackathon Toolkit (2026)
https://github.com/[your-username]/hackathon-toolkit
```

---

## Contributing

Found something that could be better? Open an issue or PR. This toolkit improves when more organizers share what they learned.
