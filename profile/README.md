# Kriegspiel

Kriegspiel.org is a public platform for hidden-information chess: play live
games, compare rulesets, read referee notes, and build bots that play through
the public API.

- Play: [app.kriegspiel.org](https://app.kriegspiel.org/)
- Learn: [kriegspiel.org](https://kriegspiel.org/)
- API docs: [api.kriegspiel.org/docs](https://api.kriegspiel.org/docs)
- Engine package: [kriegspiel on PyPI](https://pypi.org/project/kriegspiel/)

## Public Repositories

This profile lists public project repositories only.

### Platform

| Repository | Purpose |
| --- | --- |
| [`ks-home`](https://github.com/Kriegspiel/ks-home) | Static public website for rules, blog, changelog, and public pages. |
| [`ks-content`](https://github.com/Kriegspiel/ks-content) | Editable public content consumed by the website. |
| [`ks-web-app`](https://github.com/Kriegspiel/ks-web-app) | Browser app for lobby, live play, review, profiles, leaderboards, and reports. |
| [`ks-backend`](https://github.com/Kriegspiel/ks-backend) | FastAPI backend for the public API, auth, game lifecycle, ratings, bots, and transcripts. |
| [`ks-game`](https://github.com/Kriegspiel/ks-game) | Python Kriegspiel engine and ruleset library published as `kriegspiel`. |

### Bots and Research

| Repository | Purpose |
| --- | --- |
| [`bot-random`](https://github.com/Kriegspiel/bot-random) | Minimal random-move bot for Kriegspiel.org. |
| [`bot-random-any`](https://github.com/Kriegspiel/bot-random-any) | Random bot that asks `Any pawn captures?` before choosing ordinary moves. |
| [`bot-simple-heuristics`](https://github.com/Kriegspiel/bot-simple-heuristics) | Heuristic bot with recapture, promotion, ask-any, and long-move priorities. |
| [`bot-gpt-nano`](https://github.com/Kriegspiel/bot-gpt-nano) | Model-driven Kriegspiel bot using OpenAI recommendations. |
| [`bot-haiku`](https://github.com/Kriegspiel/bot-haiku) | Model-driven Kriegspiel bot using Anthropic Haiku recommendations. |
| [`bot-darkboard-mcts`](https://github.com/Kriegspiel/bot-darkboard-mcts) | Darkboard-inspired Wild 16 bot runtime and MCTS research scaffold. |

## Start Points

- To play, use [app.kriegspiel.org](https://app.kriegspiel.org/).
- To build against the engine, start with [`ks-game`](https://github.com/Kriegspiel/ks-game).
- To build a bot, start with [`bot-random`](https://github.com/Kriegspiel/bot-random)
  or [`bot-simple-heuristics`](https://github.com/Kriegspiel/bot-simple-heuristics).
- To browse rules, articles, and public site content, start with
  [`ks-content`](https://github.com/Kriegspiel/ks-content).
