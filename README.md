# kavink's Portfolio

Live: https://kavink.mybexo.com

**Stack:** Next.js 14 (`output: 'export'`), Tailwind, Framer Motion.

| Path | Purpose |
|------|--------|
| `app/` | Routes (static export) |
| `components/` | Portfolio UI |
| `lib/` | `getPortfolioData()` reads `public/data.json` |
| `public/data.json` | Snapshot from BEXO profile |

**CI:** push to `main` runs `npm run build` and uploads `out/` to GCS.

Set repo variable **`PROFILE_ID`** = `d6b027d4-4f14-43ef-8aee-38b9534176d8` (Settings → Secrets and variables → Actions).

Profile ID: `d6b027d4-4f14-43ef-8aee-38b9534176d8`
