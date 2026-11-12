# LOOP 24/7 Autonomous Publisher Engine

This repository runs a 24/7 cloud cron trigger on GitHub's free infrastructure to automatically publish scheduled Instagram Reels for `@learnzy.neet` on time, even when all dashboard tabs and computers are closed.

- **Target Endpoint**: `https://buffer-superprofile.vercel.app/api/cron/publish`
- **Cadence**: Every 10 minutes (`*/10 * * * *`)
- **Cost**: **$0.00 Forever** (Unlimited GitHub Actions on public repositories)
