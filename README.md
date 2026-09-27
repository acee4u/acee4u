<div align="center">

# prithwijit_ghosh

*a schema, not a sentence.*

**System Architecture · Platform Engineering · AI/ML** — Kolkata, IN

[Portfolio](https://prithwig.vercel.app) · [Résumé](https://prithwig.vercel.app/prithwijit-ghosh-resume.pdf) · [Writing](https://prithwiblogs.vercel.app) · [LinkedIn](https://linkedin.com/in/greninja) · [dev.prith@proton.me](mailto:dev.prith@proton.me)

</div>

<br>

```sql
-- migrations/000_init.sql
-- Up

CREATE TABLE prithwijit_ghosh (
  based_in       TEXT      NOT NULL DEFAULT 'Kolkata, IN',
  role           TEXT      NOT NULL DEFAULT 'Sr. Software Developer',
  specializes_in TEXT[]    NOT NULL DEFAULT ARRAY['system architecture', 'platform engineering', 'ai/ml'],
  currently      TEXT      NOT NULL DEFAULT 'building the parts of a system nobody notices until they break',
  cgpa           NUMERIC   NOT NULL DEFAULT 8.17 CHECK (cgpa <= 10.0)
);

-- Half the job is writing the feature.
-- The other half is making sure it's still true six migrations later.
```

<br>

### `modules/` — things that shipped

| module | what it does | stack |
|---|---|---|
| [**InkVisage**](https://github.com/GreNxNja/InkVisage) | AI tattoo platform — AR body preview, style-generation, Meilisearch-driven discovery, real-time multi-role marketplace | `react` `typescript` `prisma` `socket.io` |
| [**GeoVisionAI**](https://github.com/GreNxNja/GeoVisionAI) | Interpolates the gaps between satellite passes — encoder-decoder CNN turning stills into smooth cloud motion | `python` `pytorch` `openlayers` |
| [**NextRead**](https://github.com/GreNxNja/nextRead-beta) | Book recommender trained on a reader's actual taste, not the bestseller list | `tanstack` `supabase` |
| **Epiphany** 🏆 | Study-path optimisation + an NLP tutor bot, load-tested to 100+ concurrent sessions — AI Unite Hackathon winner | `next.js` `convex` `transformers` |

<br>

### `migrations/` — how we got here

```
021_rajwada-infotech.sql       Mar 2026 → present   · Sr. Software Developer
    ALTER SYSTEM ADD MODULE finance, inventory;
    ALTER SYSTEM ADD workflow rbac, configurable_approvals;
    -- release engineering owned end-to-end: versioned deploys, SQL Server
    -- migration authoring, zero-downtime cache invalidation across a
    -- multi-container stack (node.js / sql server / redis / nginx)
    --
    -- FIX: systemic balance-sheet discrepancy, traced through a dozen
    -- interdependent tables to root-cause in account-classification
    -- logic + orphaned ledger entries. no rollback needed — forward fix.

014_shahparpay-solutions.sql   Mar 2026 → May 2026  · Full Stack Developer
    CREATE TABLE payments, distributor_ops;
    ALTER TABLE dashboard ADD auth, activity_log, reporting;
    -- core db architecture + external financial API integrations

001_techno-india-university.sql                     2021 → 2025
    CREATE EXTENSION "ai/ml";
    -- b.tech computer science, cgpa 8.17/10
    -- 🏆 ai unite hackathon — winner   (epiphany)
    -- 🥈 smart india hackathon — runner-up (myrtle)
```

<br>

### `EXPLAIN ANALYZE` — the stack, by query cost

```
Input   typescript · python · java · cpp · sql
Drive   react · next.js · node.js · hono · bun · tanstack
Tone    postgresql · sql server · supabase · prisma · redis · socket.io
Infra   aws ec2 · docker · nginx · n8n · oauth
Rack    pytorch · transformers
```

<br>

### `certifications.log`

`anthropic` MCP · 2026 — `coursera/ibm` Data Science · 2025 — `udemy` AI Mastery · 2025 — `stanford` Machine Learning · 2024 — `iit bombay e-yantra` Robotics/VLSI · 2023

<br>

```sql
-- migrations/000_init.sql
-- Down

-- rollback not available.
-- this build is permanent — but PRs are welcome.
```

<div align="center">
<br>

[github.com/GreNxNja](https://github.com/GreNxNja) · [linkedin.com/in/greninja](https://linkedin.com/in/greninja) · [prithwiblogs.vercel.app](https://prithwiblogs.vercel.app)

</div>
