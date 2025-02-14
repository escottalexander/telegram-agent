# Telegram Agent

This Telegram agent uses ElizaOS to  

## Quick start
Create a `.env` file with *at least* the telegram bot key and openai key variables filled. The rest are optional.

Update `character.ts` to match the personality and traits you are looking for.

You can also add a `knowledge.json` file to the `src` directory for the agent to be seeded with knowledge. It will use this for RAG as it responds to messages.

Make sure you have `node 23.3 +` installed and run the following:
```bash
    pnpm i
    pnpm start
```

