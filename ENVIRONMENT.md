
## PSP_ENCRYPTION_KEY
Server-only. AES-256-GCM key material for creator PSP secrets (`psp_credentials`). At least 32 random characters.

## MIGRATION_URL
Owner connection to Neon, used only by `bun scripts/migrate.ts` (never at runtime). Must differ from DATABASE_URL (rout_app). Not needed on Vercel.
