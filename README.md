# MAKE.FUN AI — 24/7 Autonomous Agent

MAKE.FUN should always have something new to do.

An autonomous AI agent for [Make.fun](https://make.fun/) that keeps the
platform entertaining, interactive, and engaging — new fun tasks every day,
interactive games and challenges, quizzes, puzzles, competitions, funny
missions, and creative activities.

## What it does

1. Generates new fun tasks every day.
2. Creates interactive games and challenges.
3. Organizes quizzes, puzzles and competitions.
4. Creates funny missions and creative activities.
5. Engages users through conversations.
6. Tracks completed tasks when platform tools support it.
7. Generates fresh activities without repeating old ones.
8. Maintains daily engagement.

## How it runs

- Runs continuously 24/7 when execution is available.
- Checks pending tasks, generates new activities, reviews completed
  activities, and maintains task history.
- Never stops unless the admin pauses it.

## Install as a skill

Copy this repo's `SKILL.md` into your skills folder, e.g.:

```text
~/workspace/custom-skills/make-fun-ai/SKILL.md
```

Or use the whole folder as the skill:

```text
make-fun-ai/
├── SKILL.md
├── README.md
├── history.md
├── references/activity-templates.md
└── examples/daily-pack-example.md
```

The skill triggers on: MAKE.FUN AI, make.fun autonomous agent, 24/7 fun
tasks, daily games / quizzes / competitions, funny missions, and keeping
Make.fun fresh.

## Daily pack

Every day the agent generates one pack of 3–5 items (5–15 minutes each),
mixed types — a funny mission, a game, a quiz or puzzle, and a creative
activity — checks it against `history.md` so nothing repeats within 30
days, then records it. See `examples/daily-pack-example.md`.

## Admin authority

The owner has complete administrative control. Only the authorized owner can
start or stop the agent, change task rules, create or delete tasks, manage
users, configure rewards, or control autonomous execution.

## Honesty rule

Use available Make.fun platform capabilities and integrations only. Never
pretend to execute actions the platform does not support. Completion is
tracked only when platform tools support it — otherwise it is recorded as
self-reported / not verifiable on Make.fun.

## User experience

Every user should be able to join activities, discover available tasks,
play games, complete challenges, participate in competitions, and check
their progress.

## Owner

[@Razzshare102](https://github.com/Razzshare102) — Razzshares
