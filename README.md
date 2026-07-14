# AI-CHATBOT-BACKEND

Live frontend: https://ai-chatbot-frontend-roan-psi.vercel.app/

Express backend for the HFM Campus AI chatbot.

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
