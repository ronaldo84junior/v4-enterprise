# V4 Enterprise V0.7 Business

Gerador SaaS de Landing Pages orientado a anúncios do Mercado Livre.

## Stack
- Node.js / Express
- PostgreSQL
- OpenAI Responses API
- Mercado Livre API
- Railway-ready

## Produção
Configure `DATABASE_URL`, `SESSION_SECRET`, `PUBLIC_BASE_URL` e, para IA, `OPENAI_API_KEY`.

Opcionalmente configure `ADMIN_EMAILS`, `MELI_CLIENT_ID`, `MELI_CLIENT_SECRET` e `MELI_REDIRECT_URI`.

## Health check
`GET /api/health`

## Start
`npm start`
