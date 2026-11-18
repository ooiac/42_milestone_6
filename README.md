# Milestone 6 — ft_transcendence, final exam, résumé

The last milestone of my 42 Common Core. It combines a team web application with the final exam and a résumé. Unlike the earlier milestones, only one of these is a software project in this repository.

## ft_transcendence — Who Knows Best?

[`ft_transcendence/`](ft_transcendence/) contains **Who Knows Best?**, our multiplayer *myth or fact* quiz. Rather than using the classic Pong approach, the team built a timed quiz: players decide whether a statement is true, earn points for correct and quick answers, and lose points for wrong ones.

Matches support rooms, bots, and tournaments. The application also has accounts, player history, leaderboards, achievements, and translations in English, Portuguese, and French.

### Stack and architecture

- **Frontend:** React and TypeScript.
- **Backend:** Fastify on Node.js.
- **Database:** PostgreSQL for accounts and match-related data.
- **Real-time matches:** WebSockets for game-state updates.
- **Deployment:** Docker Compose, with HTTPS for local development.

The project was built by `caida-si`, `alehenri`, `mlima-de`, `rsommer`, and `hjuma`.

### Run locally

```sh
cd ft_transcendence
make
```

Open `https://localhost:8443`. Docker and Docker Compose are required. The local certificate is self-signed, so the browser may show a security warning. For environment variables, commands, and a detailed feature breakdown, see the [existing ft_transcendence README](ft_transcendence/README.md), which is maintained separately.

## Final exam

The final Common Core exam is an assessed exercise, not a repository application. I've listed it here as part of the milestone rather than adding example code that isn't an official submission.

## Résumé

The résumé is the other final milestone requirement. Like the exam, it isn't a program with source files or build instructions. There is no placeholder project or fake deliverable to document here.
