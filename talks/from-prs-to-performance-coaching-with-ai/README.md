# From PRs to Performance

**Using metrics and AI to coach stronger engineering teams.**

*Metrics should start conversations, not end careers.*

Presented at [Stir Trek 2026](https://stirtrek.com).

## Slides

[from-prs-to-performance-coaching-with-ai.pdf](./from-prs-to-performance-coaching-with-ai.pdf)

## Speaker

**Eric Martin**, Director of Software Engineering, [KODE Health](https://www.kodehealth.com)

- LinkedIn: [ericemartin1](https://www.linkedin.com/in/ericemartin1/)
- GitHub: [@ericemartin](https://github.com/ericemartin)

Eric is the Director of Engineering at KODE Health, bringing 25 years of expertise in software development to his role. Specializing in revenue cycle systems for healthcare, Eric has built and led teams that automate and track 1 billion communications annually. Eric holds a degree in Information Systems from Ohio State University and an MBA from Keller Graduate School of Management. He is a co-patent holder for an innovative obfuscation of PII used in print and digital composition and delivery. Throughout his career, Eric has demonstrated a passion for helping engineers grow and achieve their next level of professional development. His leadership and commitment to innovation have left a lasting impact for customers and organizations.

## Abstract

Velocity is useful, but it is not leadership. Most organizations either stop at team velocity and "gut feel," or they overcorrect into individual scoreboards that erode trust and create perverse incentives. This talk shares a pragmatic middle path: how engineering leaders can use metrics to understand delivery health, code quality, and collaboration, without turning measurement into micromanagement.

I built an internal metrics web application that connects to common systems like code repositories and agile/project tools (GitHub and Linear in my case, but the approach generalizes to Jira and other platforms). It tracks velocity and estimation trends over time, compares individual and team patterns, and adds pull request analysis to surface quality signals. I also integrated AI (Claude) to review commits and PR discussions and generate a quality assessment across four dimensions: code quality (DRY/SOLID), testing habits, adherence to standards, and collaboration in code review.

This session is designed for senior engineers through executive technology leaders. You will learn which metrics are actually useful, how to implement a dashboard in your environment, and how to apply guardrails so metrics drive coaching and continuous improvement rather than fear or gaming. The examples and demo are fully offline using anonymized or mock data and precomputed AI outputs, so the approach works even with limited connectivity.

**What's in it for you:** you'll leave with a concrete dashboard blueprint and an implementation plan you can apply immediately: what to measure, how to visualize it, how to layer in AI responsibly, and how to use the signals to coach, improve standards, and raise delivery confidence.

## Key Takeaways

- A leadership-oriented metrics framework: outcomes vs system signals vs behaviors (and what not to measure)
- A practical dashboard design that combines velocity, estimation reality ("hours per point"), and PR signals
- How to use AI as an assistant for qualitative insights (and how to calibrate it so it does not become "truth")
- Guardrails for trust: privacy, transparency, and preventing metric gaming
- A step-by-step path to build this in your org using APIs from your existing tools

## 45-Minute Outline

1. **Why most engineering metrics fail in practice** (5 min)
2. **Velocity, estimation, and forecasting that leaders can actually use** (10 min)
   - Team velocity per cycle, averages, "hours per point" trends
   - Comparing individual patterns to team patterns without weaponizing it
3. **Pull request signals that reveal quality and delivery risk** (10 min)
   - Review cycles, rework patterns, standards drift, collaboration signals
4. **AI-assisted quality analysis, responsibly** (12 min)
   - Code quality, testing quality, standards, collaboration
   - Calibrating with spot checks and known baselines; using confidence labels
5. **How to apply the signals: coaching, leveling expectations, and intervention** (6 min)
6. **Build plan: how to implement this dashboard in your environment** (2 min)
