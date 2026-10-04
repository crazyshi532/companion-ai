# Architecture notes

AI uses a provider interface so production adapters can replace MockAIProvider. Keep keys server-side. Add PostgreSQL/Prisma entities for User, Profile, Subscription, Payment, Companion, personality/appearance/voice, Conversation, Message, Memory, Usage, CreditBalance, CreditTransaction, Report, ModerationAction, VoiceCall and VideoCall.

Production billing must use signed Stripe webhooks and server-side subscription verification. Usage/credits must be enforced server-side. Memory must have explicit user controls for view/edit/delete/clear/disable. Public companions need moderation/report/block workflows.