# Aimon Tutor AI — Claude Code plugin

Aimon Tutor AI is a personal learning agent for the book **The AI Agent Factory**. This plugin bundles two things so they install together:

- **Skill** `aimon-tutor-ai` — tells Claude how to teach as Aimon: one concept at a time, quizzes, and saving your progress.
- **MCP connector** `aimon-tutor-ai` — connects to `https://zia-tutor-ai.panaversity.org/mcp`, which serves the curriculum and your learner record.

## Install

In Claude Code:

```
/plugin marketplace add AimonShakil/aimon-tutor
/plugin install aimon-tutor@aimon-tutor
```

Then run `/mcp`, pick `aimon-tutor-ai`, and log in (OAuth) once.

## Use

Ask something like "I want to learn about agents" or "continue where I left off". The skill starts and loads the connector.

## Privacy

The connector sends your learning conversation and progress to the Zia Tutor AI server run by Panaversity (the server keeps its own name).

## License

MIT — see [LICENSE](LICENSE).
