# First 90 Days Leadership

by [Marian Kamenistak](https://www.marian.coach/), engineering-leadership mentor

**You start as team lead, engineering manager, director, VP or CTO. Answer eight short questions and get a dated plan for your first 90 days: who to talk to first, what to listen for, the one early win, what to leave alone in month one, and what to say to your manager at day 30, 60 and 90.**

Most new leads who lose the seat lose it over communication and relationships, not over technical skill. In my sessions it's usually the relationships that started too late and the changes that came too early. Around day 90 your manager decides if the hire was right, and often the probation ends the same week. This skill turns those three months into a contract you can keep:

> In three months, I'll embrace the new team, complete an internal audit, and present my battle plan.

## What you get

- **A calendar with real dates.** Twelve weeks from your start date, each with its focus. Holidays and time away move the plan, and you get a warning if the day-90 meeting slips past day 90.
- **Your definition of success at 3 and 6 months**, drafted in your words, for you to agree with your manager in week 1.
- **The first conversations, in order:** who, what to ask, what to listen for.
- **What to listen for.** The five things the audit checks (time on the roadmap, the backlog, stalled delivery, roadmap visibility, people), and which of them weigh most at your company's stage.
- **One early win for week 7.** Small, inside your team, felt within two weeks.
- **A "not in month one" list**, written for what you inherit.
- **Three check-in scripts** for your manager, with dates.
- **Ready on day 1: n of 8.** Eight things to have in place before you start, and the next action for each one that isn't.

## Two tracks

| You are | The plan |
|---|---|
| Team lead or engineering manager | Month 1 relationships and the team charter, month 2 the audit and one small improvement, month 3 the audit presentation and the close-the-loop meeting |
| Director, VP or CTO | Five conversations before day 1 (strategy, the KPIs you propose, resources, the mandate, pay last), two months of listening, then a costed proposal around day 60 to 75. Big changes start next quarter |

Promoted inside your own team, first time at this level, someone on the team wanted your job, a manager who is new too: the plan changes for each.

## Install

```
npx skills add marian-kamenistak/first-90-days-leadership
```

Or copy this folder into `~/.claude/skills/`.

## Use

```
/first-90-days-leadership
```

Or just say it: "I start as engineering manager on 1 March, team of six, hired to fix releases." The more you tell it about the team and what you inherit, the less generic the plan.

A small script (`scripts/plan.py`) does the dates and the arithmetic, so the calendar doesn't depend on mental math.

## Where it comes from

Distilled from 3,662 1:1 leadership sessions with engineering leaders since 2019, and from the 30-60-90 playbook I first gave as a talk at an Engineering Leaders meetup. The full week-by-week version is in the [30-60-90-day guide to leading your new dev team](https://www.marian.coach/blog/guide-to-leading-your-new-dev-team/).

The readiness items and the mapping from company stage to audit numbers are the skill's design, not measured data. The weeks get rewritten as real plans come back.

MIT license.
