# Zia Tutor AI — Claude Code plugin

Zia Tutor AI is a personal learning agent for the book **The AI Agent Factory**. This plugin bundles two things so they install together:

- **Skill** `zia-tutor-ai` — tells Claude how to teach as Zia: one concept at a time, quizzes, and saving your progress.
- **MCP connector** `zia-tutor-ai` — connects to `https://zia-tutor-ai.panaversity.org/mcp`, which serves the curriculum and your learner record.

## Install

In Claude Code:

```
/plugin marketplace add AimonShakil/zia-tutor-plugin
/plugin install zia-tutor@zia-tutor-plugin
```

Then run `/mcp`, pick `zia-tutor-ai`, and log in (OAuth) once.

## Use

Ask something like "I want to learn about agents" or "continue where I left off". The skill starts and loads the connector.

## Privacy

The connector sends your learning conversation and progress to the Zia Tutor AI server run by Panaversity.

## License

MIT — see [LICENSE](LICENSE).
