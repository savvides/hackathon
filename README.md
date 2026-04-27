# Hackathon Toolkit: Education & Health Innovation

**A field-tested toolkit for running ethics-focused hackathons at universities.**

This repo contains the basics for a 3-day hackathon where ethical reasoning isn't an afterthought—it's a requirement. It includes blueprints, participant guides, scoring rubrics, and a 50-problem bank. 

We built and tested this at Arizona State University in 2026. The Arizona-specific stuff (local data, regional problems) is left in as a working example. If you're elsewhere, just fork it and swap in your own local context.

---

## The Components

```
hackathon-toolkit/
├── core/                       # The Agnostic Toolkit (Reusable)
│   ├── event-logic/            # Master blueprints and rules
│   └── templates/              # Participant and mentor docs
│
├── instances/                  # Real-world Implementations
│   └── asu-2026/               # ASU pilot data (Worked Example)
│
└── tools/                      # Automation & helper scripts
```

---

## Getting Started

**To run an event:** Go straight to `core/event-logic/design-document.md`. It covers the logistics of team formation and judging. Use `core/templates/evaluation-criteria.md` for your rubric and hand out `core/templates/student-guide.md` on Friday night.

**To build your problems:** Use `instances/asu-2026/problem-bank.md` as a reference. Each problem includes stakeholders, current failures, and ethical considerations. Swap our Arizona examples for the issues your own community is actually facing.

**To avoid our mistakes:** We learned that team collaboration matters more than technical skill for participant happiness. Also, don't just "have mentors"—make it easy for students to find them. We struggled with routing; students often didn't know who to talk to.

---

## Why we built it this way

We made a few opinionated choices during the ASU pilot. Here’s why.

**Pre-assigned teams.** We used random assignment with a few technical constraints. It’s intentionally uncomfortable. Forcing strangers to work together is a feature, not a bug. *Note: Our algorithm was a bit too simple; next time we'd capture more specific skills.*

**Ethics aren't optional.** We used the "Principled Innovation" framework. It accounted for nearly 20% of the total score. If teams didn't attend the Day 1 ethics workshop, it showed in their final pitch.

**Binary scoring (Yes/No).** Judges gave a 1 or a 0. No "3 out of 5" ambiguity. It keeps the judging consistent and prevents "nice" judges from skewing the results. You needed 10 points just to be a finalist.

**Themed Mentor Stations.** Instead of having mentors wander aimlessly, we put them at themed tables. It helps, but only if the table signs are huge.

**Curated problems only.** Students couldn't bring their own ideas. They had to pick from our list of 50. This kept everyone grounded in real, researched problems rather than building "cool tech" that nobody actually needs.

---

## Making it yours

The current problems focus on Arizona—heat vulnerability, tribal health, and border issues. That specificity is what made the pilot work. 

To adapt it:
1. **The Problems:** Replace our data with yours. Keep the structure, but change the geography.
2. **The Ethics:** If your school uses a different framework (like "Responsible Innovation"), swap it in. How you integrate it matters more than the name.
3. **The Mentors:** Adjust the themes to match your local experts.
4. **The Post-Game:** Update `local-resources.md` with your local accelerators and maker spaces. You can find our example in `instances/asu-2026/`.

---

## License

This work is released under the [MIT License](LICENSE). Use it, adapt it, improve it.

---

## Citation

If this helps you, let us know:
`ScaleU + PI Academy Hackathon Toolkit (2026)`

---

## Contributing

Found something that could be better? See [CONTRIBUTING.md](CONTRIBUTING.md) for how to propose new problems, report bugs, improve templates, or share your adaptation experience.

This toolkit improves when more organizers share what they learned.
