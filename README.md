# Hermes skills by HugoAlbertBonet

A [Hermes Agent](https://hermes-agent.nousresearch.com/docs) skill tap.

| Skill | What it does |
|---|---|
| [`deadline-radar`](skills/deadline-radar/SKILL.md) | Tracks deadlines (with optional effort estimates) in memory, schedules reminders 3 days and 1 day before, and flags deadlines at risk. Built-in tools only: `memory`, `cronjob_manage`, `clarify`. |

## Install

```bash
hermes skills tap add HugoAlbertBonet/hermes-skills
hermes skills install HugoAlbertBonet/hermes-skills/deadline-radar
```

## Try it

```text
CSCI 599 A3 is due on Nov 20 at 23:59, about 10 hours of work left.
What's due this week? Am I on track?
Router done, about 6 hours left on A3.
I submitted A3.
```

Reminders are delivered to the chat where the deadline was added, so add deadlines from a messaging
platform (e.g. Telegram) to receive them there.

Written for the CSCI 599 (USC) Assignment 3 personal assistant; uses synthetic data only.
