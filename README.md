# AI-CHATBOT-BACKEND

Express backend for the CampusAI chatbot.

## Local development

```bash
npm install
cp .env.example .env
npm run dev
```

Required environment variables:

- `MISTRAL_API_KEY`
- `FRONTEND_URI` for the deployed frontend origin

## Render

- Root directory: repository root
- Build command: `npm install`
- Start command: `npm start`

Set these environment variables in Render:

- `MISTRAL_API_KEY`
- `FRONTEND_URI`
