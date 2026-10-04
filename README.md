# CompanionAI

Runnable Next.js starter based on the supplied 916-line product specification.

## Run
```bash
npm install
npm run dev
```
Then open http://localhost:3000.

## Routes
/, /discover, /onboarding, /chat/luna, /voice/luna, /video/luna, /dashboard, /pricing, /settings, /admin.

## Current implementation
The project includes the premium dark UI, 8 adult demo companions, multi-step creator, interactive chat with a server-side mock AI provider, call experiences, dashboard/pricing/admin shells, provider abstraction, API route, and environment template.

## Production work still requiring credentials/infrastructure
PostgreSQL + Prisma, Auth.js/Supabase authentication, Stripe Checkout/webhooks, production AI provider, STT/TTS, avatar/video provider, object storage, persistent memory/usage/credit ledgers, rate limiting and full moderation/audit infrastructure should be connected before launch.

Mock providers keep local UI development usable without paid credentials.
