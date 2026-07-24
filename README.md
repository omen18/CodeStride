<div align="center">

# CodeStride

**Your developer productivity command center.**

> Track your GitHub activity, commit streaks, PR analytics, and coding goals in one clean, self-hostable dashboard — no enterprise plan, no vendor lock-in.

[![CI](https://github.com/omen18/codestride/actions/workflows/ci.yml/badge.svg)](https://github.com/omen18/codestride/actions/workflows/ci.yml)
[![License: MIT](https://img.shields.io/badge/license-MIT-blue.svg)](./LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](./CONTRIBUTING.md)
[![Stack](https://img.shields.io/badge/stack-Next.js%2016%20%7C%20Supabase%20%7C%20TypeScript-blue)](./DEVELOPMENT.md)
[![Stars](https://img.shields.io/github/stars/omen18/codestride?style=flat&color=yellow)](https://github.com/omen18/codestride/stargazers)
[![Forks](https://img.shields.io/github/forks/omen18/codestride?style=flat&color=blue)](https://github.com/omen18/codestride/network/members)
[![Contributors](https://img.shields.io/github/contributors/omen18/codestride?color=brightgreen)](https://github.com/omen18/codestride/graphs/contributors)
[![Last Commit](https://img.shields.io/github/last-commit/omen18/codestride)](https://github.com/omen18/codestride/commits/main)
[![Views](https://komarev.com/ghpvc/?username=omen18&label=Views&color=blueviolet)](https://github.com/omen18/codestride)
[![GitHub Sponsors](https://img.shields.io/github/sponsors/omen18?label=sponsors&color=ea4aaa)](https://github.com/sponsors/omen18)
[![Good First Issues](https://img.shields.io/github/issues/omen18/codestride/good%20first%20issue?label=good%20first%20issues&color=7057ff)](https://github.com/omen18/codestride/issues?q=is%3Aissue+is%3Aopen+label%3A%22good+first+issue%22)
[![Help Wanted](https://img.shields.io/github/issues/omen18/codestride/help%20wanted?label=help%20wanted&color=008672)](https://github.com/omen18/codestride/issues?q=is%3Aissue+is%3Aopen+label%3A%22help+wanted%22)

**[Live Demo](https://codestride-silk-kappa.vercel.app)** · **[Dev Guide](./DEVELOPMENT.md)** · **[Report Bug](https://github.com/omen18/codestride/issues/new?template=bug_report.md)** · **[Request Feature](https://github.com/omen18/codestride/issues/new?template=feature_request.md)** · **[Discussions](https://github.com/omen18/codestride/discussions)** · **[Sponsor](https://github.com/sponsors/omen18)**

<br />

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2Fomen18%2Fcodestride&project-name=codestride&repository-name=codestride&env=NEXT_PUBLIC_SUPABASE_URL,NEXT_PUBLIC_SUPABASE_ANON_KEY,SUPABASE_SERVICE_ROLE_KEY,NEXTAUTH_URL,NEXTAUTH_SECRET,GITHUB_ID,GITHUB_SECRET,ENCRYPTION_KEY&envDescription=Supabase%20keys%2C%20GitHub%20OAuth%20app%20credentials%2C%20and%20a%20NextAuth%20secret&envLink=https%3A%2F%2Fgithub.com%2Fomen18%2Fcodestride%2Fblob%2Fmain%2FDEVELOPMENT.md)

⭐ **If CodeStride saves you time, [star the repo](https://github.com/omen18/codestride/stargazers)** — it helps more developers discover it.

</div>

---

## Demo & Showcase

<div align="center">

### ⚡ Hero Landing Page
<img src="./public/assets/screenshots/hero-preview.png" alt="CodeStride Hero - Your Code Has A Pulse" width="100%" />
<br />
<em>Your Code Has A Pulse — real-time contributions, active streak tracking, merge rate, and heatmap widgets</em>

<br /><br />

### 🎯 Developer Progress & Features
<img src="./public/assets/screenshots/about-features.png" alt="CodeStride Features - Clearer Home for Developer Progress" width="100%" />
<br />
<em>Live GitHub signals, PR momentum analytics, goal tracking, and shareable developer profiles</em>

<br /><br />

### 🔐 Authentication Flow
<img src="./public/assets/screenshots/signin-preview.png" alt="CodeStride Sign-In with GitHub" width="85%" />
<br />
<em>Seamless GitHub OAuth authentication with self-hostable zero vendor lock-in</em>

<br /><br />

<table>
  <tr>
    <td width="50%" align="center">
      <img src="./public/assets/gifs/dashboard-demo.gif" alt="CodeStride dashboard demo" width="100%" />
      <br />
      <em>Dashboard: streaks, PR analytics, activity heatmap, and goals</em>
    </td>
    <td width="50%" align="center">
      <img src="./public/assets/gifs/feature-hover-demo.gif" alt="CodeStride widget demo" width="100%" />
      <br />
      <em>Interactive widgets: real-time GitHub data in action</em>
    </td>
  </tr>
  <tr>
    <td colspan="2" align="center">
      <img src="./public/assets/gifs/year_wrapped.gif" alt="CodeStride Year Wrapped" width="70%" />
      <br />
      <em>Year Wrapped: your annual coding journey, visualized</em>
    </td>
  </tr>
</table>

</div>

---

## Table of Contents

- [Why CodeStride?](#why-codestride)
- [Demo & Showcase](#demo--showcase)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Project Structure](#project-structure)
- [Architecture](#architecture)
- [API Documentation](#api-documentation)
- [Getting Started](#getting-started)
- [Docker Development Setup](#docker-development-setup)
- [FAQ](#faq)
- [Roadmap](#roadmap)
- [Contributing](#contributing)
- [Community](#community)
- [Built With](#built-with)
- [Sponsors](#sponsors)
- [Star History](#star-history)
- [License](#license)
- [Maintainers](#maintainers)
- [Contributors](#contributors)

---

## Why CodeStride?

Most developers track their work across multiple disconnected tools — GitHub for commits, Jira for tasks, Notion for goals, Slack for standups. None of them give you the full picture.

**CodeStride solves this by:**

- Consolidating GitHub contributions, PR metrics, and streak data in one view
- Helping you set and visualize personal coding goals with progress tracking
- Keeping your data yours — fully self-hostable with zero vendor lock-in
- Deploying in minutes on the free tier of Next.js + Supabase + Vercel

---

## Features

| Feature | Description |
|---|---|
| **GitHub OAuth** | Sign in with GitHub — no separate account needed |
| **Commit Activity Chart** | Visualize daily commit activity with 7d / 14d / 30d / 90d range selector |
| **Commit Streak Tracker** | Current streak, longest streak, and active days |
| **PR Analytics** | Average review time, merge rate, open/closed PR counts |
| **Top Repositories** | Ranked list of most active repos over any time range |
| **Goal Tracker** | Set and track personal coding goals with progress bars |
| **Public Profile** | Shareable public profile page at `/u/[username]` with stats and badges |
| **Repository Spotlight** | Pin up to 3 repositories to showcase on your public profile |
| **GitHub Achievements** | Automatically synced GitHub achievement badges on your public profile |
| **Leaderboard** | Opt-in public leaderboard ranked by streak, commits, and PRs |
| **Discord Integration** | Streak reminders and milestone alerts via Discord webhooks |
| **Wakatime Integration** | Accurate coding time and language usage from Wakatime |
| **Multi-Account Support** | Link and switch between multiple GitHub accounts |
| **Weekly Email Digest** | Optional Monday morning summary of your coding habits |
| **Data Export** | Download all your data in JSON format |
| **AI Weekly Insights** | Groq-powered natural language summary of your weekly activity |
| **Heatmap Themes** | Default and colour-blind-friendly heatmap colour schemes |
| **Year Wrapped** | Annual coding journey recap with animated visualizations |
| **Real-time Dashboard** | Live updates via Supabase Realtime with polling fallback |

---

## Tech Stack

| Layer | Technology |
|---|---|
| Frontend | Next.js 16 (App Router), TypeScript, Tailwind CSS |
| Auth | GitHub OAuth via NextAuth.js v4 |
| Database | Supabase (PostgreSQL) with Row Level Security |
| API | Next.js Route Handlers (`/app/api/`) |
| Charts | Recharts |
| AI | Groq API |
| Deployment | Vercel (free tier, auto-deploys from GitHub) |

---

## Project Structure

```
codestride/
├── src/
│   ├── app/
│   │   ├── api/
│   │   │   ├── auth/          # GitHub OAuth (NextAuth)
│   │   │   ├── metrics/       # Contributions, streak, PRs, repos
│   │   │   ├── goals/         # Goal CRUD
│   │   │   ├── leaderboard/   # Public leaderboard
│   │   │   ├── public/        # Public profile JSON API
│   │   │   └── user/          # Settings, data export, linked accounts
│   │   ├── dashboard/         # Authenticated dashboard
│   │   ├── u/[username]/      # Public profile pages
│   │   └── page.tsx           # Landing page
│   ├── components/            # Reusable UI components
│   └── lib/
│       ├── auth.ts            # NextAuth config
│       ├── supabase.ts        # Supabase admin client (server-side only)
│       ├── public-profile-data.ts  # GitHub API helpers for public profiles
│       └── github-achievements.ts  # Achievement sync logic
├── supabase/
│   └── migrations/            # Versioned schema migrations
├── e2e/                       # Playwright end-to-end tests
├── test/                      # Unit tests
└── .github/
    ├── workflows/ci.yml       # Type-check + lint on every PR
    └── ISSUE_TEMPLATE/        # Bug, feature, good-first-issue templates
```

---

## Architecture

New contributors can start with the [architecture overview](./docs/architecture.md) for Mermaid diagrams covering the Next.js frontend, API routes, Supabase schema, external services, and GitHub activity sync flow.

---

## API Documentation

CodeStride includes a documented REST API.

Documentation resources:

- `docs/api.md` — API usage guide
- `public/openapi.yaml` — OpenAPI 3.1 specification
- `/api-docs` — Interactive Swagger UI

After starting the development server, open:

`http://localhost:3000/api-docs`

---

## Getting Started

For local development and contributing, see **[DEVELOPMENT.md](./DEVELOPMENT.md)**.
To deploy your own instance, see the **[Self-Hosting Guide](./docs/self-hosting.md)**.


### Quick Start

**1. Clone and install**

```bash
git clone https://github.com/omen18/codestride.git
cd codestride
pnpm install
```

**2. Set up Supabase**

1. Create a free project at [supabase.com](https://supabase.com)
2. Run all migrations from `supabase/migrations/` in the SQL editor (in order)
3. Copy your Project URL, anon key, and service_role key from **Project Settings → API**

**3. Create a GitHub OAuth App**

1. Go to [GitHub → Settings → Developer Settings → OAuth Apps](https://github.com/settings/applications/new)
2. Set the callback URL to `http://localhost:3000/api/auth/callback/github`
3. Copy your Client ID and Client Secret

**4. Configure environment**

```bash
cp .env.example .env.local
```

### Environment Variables

> [!WARNING]
> Never commit `.env` or `.env.local` to Git. These files are pre-configured in `.gitignore`.

| Variable | Required | Description |
|---|---|---|
| `NEXT_PUBLIC_SUPABASE_URL` | Yes | Supabase project URL |
| `NEXT_PUBLIC_SUPABASE_ANON_KEY` | Yes | Supabase public anon key |
| `SUPABASE_SERVICE_ROLE_KEY` | Yes | Supabase service role key (server-side only) |
| `NEXTAUTH_URL` | Yes | Base URL of the app (`http://localhost:3000` locally) |
| `NEXTAUTH_SECRET` | Yes | Session encryption key — `openssl rand -base64 32` |
| `GITHUB_ID` | Yes | GitHub OAuth App Client ID |
| `GITHUB_SECRET` | Yes | GitHub OAuth App Client Secret |
| `ENCRYPTION_KEY` | Yes | 32-byte hex key — `openssl rand -hex 32` |
| `GITHUB_TOKEN` | No | Personal Access Token to raise GitHub API rate limits |
| `GITHUB_WEBHOOK_SECRET` | No | Webhook signature validation key |
| `UPSTASH_REDIS_REST_URL` | No | Upstash Redis endpoint for rate limiting |
| `UPSTASH_REDIS_REST_TOKEN` | No | Upstash Redis access token |
| `GROQ_API_KEY` | No | Groq API key for AI weekly insights |
| `NEXT_PUBLIC_APP_URL` | No | Public URL override for generating share links |

**5. Run locally**

```bash
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000) and sign in with GitHub.

**6. Run tests**

```bash
# Unit tests
pnpm test

# End-to-end tests (requires Chromium)
npx playwright install --with-deps chromium
pnpm run test:e2e
```

### E2E Test Suite (Playwright)

CodeStride ships a Playwright-based end-to-end suite covering the full user journey — OAuth sign-in, dashboard rendering, and API correctness. No real credentials needed; all external calls are mocked via `page.route()`.

| Spec file | Coverage |
|-----------|----------|
| `e2e/auth.spec.ts` | Landing page, sign-in button, OAuth redirect, unauthenticated redirects |
| `e2e/dashboard.spec.ts` | All 6 dashboard widgets render after mock login, no console errors |
| `e2e/goals.spec.ts` | Goal create/delete lifecycle with API payload verification |
| `e2e/streak.spec.ts` | Streak values display, freeze button triggers API call |
| `e2e/api.spec.ts` | Auth-gated API routes return 200/401 correctly |

```bash
# Install Playwright browsers (one-time)
npx playwright install --with-deps chromium

# Run the full suite (dev server auto-starts on port 3002)
pnpm run test:e2e

# Run a single spec
npx playwright test e2e/goals.spec.ts

# Interactive UI runner
npx playwright test --ui
```

The test server is configured in `playwright.config.mjs` and auto-starts on `http://127.0.0.1:3002` with placeholder credentials — no `.env.local` required. E2E tests also run on every PR via `.github/workflows/e2e.yml`.

### Visual Regression Tests

Playwright screenshot assertions cover the landing page, sign-in page, dashboard header, public profile, and 404 page.

```bash
# Run visual regression tests
npx playwright test -c playwright.visual.config.mjs

# Update baselines
npx playwright test -c playwright.visual.config.mjs --update-snapshots
```

Baselines are stored in `tests/snapshots/`. Use the same Linux/Chromium environment as CI to avoid OS-specific rendering differences. The suite uses a `1280x720` viewport and fails at >0.1% pixel difference.

---

## Docker Development Setup

CodeStride includes Docker support for local development, allowing contributors to get started quickly without manually installing dependencies or configuring environments.

### Prerequisites

- Docker Desktop (Windows/macOS) or Docker Engine (Linux)
- Docker Compose v2+

Verify installation:

```bash
docker --version
docker compose version
```

### Configure Environment Variables

Copy the example environment file:

```bash
cp .env.example .env.local
```

Fill in the required values as described in the Environment Variables section above.

### Start the Application

Build and start the development container:

```bash
docker compose up --build
```

The application will be available at:

```text
http://localhost:3000
```

### Stop the Application

```bash
docker compose down
```

### Hot Reload Support

The project source code is mounted into the container using Docker volumes.

Any changes made to files on your host machine are automatically reflected inside the container, enabling Next.js hot reload during development without rebuilding the image.

### Rebuild After Dependency Changes

If you modify `package.json` or install new dependencies:

```bash
docker compose down
docker compose up --build
```

### Troubleshooting

Remove containers and rebuild from scratch:

```bash
docker compose down -v
docker compose up --build
```

View container logs:

```bash
docker compose logs -f
```

---

## FAQ

Answers to questions new contributors and self-hosters ask most often. For deeper setup detail, see [DEVELOPMENT.md](./DEVELOPMENT.md) and the [Self-Hosting Guide](./docs/self-hosting.md).

<details>
<summary><strong>How do I configure GitHub OAuth?</strong></summary>

1. Go to [GitHub → Settings → Developer Settings → OAuth Apps](https://github.com/settings/applications/new) and create a new OAuth App.
2. Set the **Authorization callback URL** to:
   - Local dev: `http://localhost:3000/api/auth/callback/github`
   - Production: `https://<your-domain>/api/auth/callback/github`
3. Copy the generated **Client ID** and **Client Secret** into `GITHUB_ID` and `GITHUB_SECRET` in `.env.local`.
4. Make sure `NEXTAUTH_URL` matches the base URL you're running on, and `NEXTAUTH_SECRET` is set (generate one with `openssl rand -base64 32`).

</details>

<details>
<summary><strong>Why is login not working?</strong></summary>

This is almost always one of the following:

- **Callback URL mismatch** — the URL registered on your GitHub OAuth App must exactly match `NEXTAUTH_URL` + `/api/auth/callback/github`, including protocol and trailing slashes.
- **Missing/incorrect `NEXTAUTH_SECRET`** — sessions will silently fail without it.
- **Stale `.env.local`** — restart `pnpm dev` after changing any auth-related env vars; Next.js doesn't hot-reload env files.
- **Supabase RLS blocking the user row** — check that the relevant migrations from `supabase/migrations/` have been applied in order.

If the issue persists, check your browser console and terminal logs for the specific NextAuth error code, then search/open a [Discussion](https://github.com/omen18/codestride/discussions).

</details>

<details>
<summary><strong>How do I obtain Supabase credentials?</strong></summary>

1. Create a free project at [supabase.com](https://supabase.com).
2. Open **Project Settings → API**.
3. Copy:
   - **Project URL** → `NEXT_PUBLIC_SUPABASE_URL`
   - **anon public key** → `NEXT_PUBLIC_SUPABASE_ANON_KEY`
   - **service_role key** → `SUPABASE_SERVICE_ROLE_KEY` (server-side only — never expose this in client code or commit it)
4. Run all SQL files in `supabase/migrations/` via the Supabase SQL editor, in order, before starting the app.

</details>

<details>
<summary><strong>Why are GitHub metrics not loading?</strong></summary>

- You're likely hitting **GitHub's unauthenticated API rate limit**. Set the optional `GITHUB_TOKEN` (a personal access token) in `.env.local` to raise the limit significantly.
- Check that your GitHub OAuth scopes were granted during sign-in — if you denied a permission, re-authenticate by signing out and back in.
- If you're self-hosting behind a proxy or firewall, confirm outbound requests to `api.github.com` aren't being blocked.
- Look at the server logs/terminal for the specific API error (403 usually means rate-limited; 401 means a token problem).

</details>

<details>
<summary><strong>How do I run tests?</strong></summary>

```bash
# Unit tests
pnpm test

# End-to-end tests (Playwright, first-time setup)
npx playwright install --with-deps chromium
pnpm run test:e2e

# Run a single e2e spec
npx playwright test e2e/goals.spec.ts

# Visual regression tests
npx playwright test -c playwright.visual.config.mjs
```

E2E tests use mocked external calls (no real GitHub/Supabase credentials needed) and also run automatically on every PR via `.github/workflows/e2e.yml`.

</details>

<details>
<summary><strong>How can I contribute?</strong></summary>

1. Browse [open issues](https://github.com/omen18/codestride/issues) and start with one labeled `good first issue`.
2. Comment on the issue to get assigned before starting work.
3. Fork the repo, branch off `main` (e.g. `feat/issue-42-description`), and open a PR.
4. Before pushing, make sure CI passes locally:
   ```bash
   pnpm run lint && pnpm run type-check
   ```
5. See [CONTRIBUTING.md](./CONTRIBUTING.md) for commit message style, branch naming conventions, and the review process.

Questions are welcome anytime in [Discussions](https://github.com/omen18/codestride/discussions).

</details>

<details>
<summary><strong>Which Node.js and pnpm versions are supported?</strong></summary>

| Tool | Version | Check |
|------|---------|-------|
| Node.js | >= 20 | `node -v` |
| pnpm | >= 9 | `pnpm -v` |
| Git | any | `git --version` |

Install pnpm via `corepack enable` or `npm install -g pnpm` if you don't already have it.

If your local versions differ and you hit install/build errors, aligning your Node.js/pnpm version with the table above is the first thing to check.

</details>

---

## Roadmap

### Shipped

These features are live in the current version.

| Feature | Notes |
|---|---|
| GitHub OAuth sign-in | |
| Commit activity chart | 7d / 14d / 30d / 90d range selector |
| Commit streak tracker | Current, longest, active days |
| PR analytics widget | Review time, merge rate, open/closed counts |
| Top repositories widget | |
| Weekly goal tracker | |
| Dark mode + heatmap themes | Default and colour-blind-friendly |
| Responsive mobile layout | |
| Public profile (`/u/[username]`) | Shareable stats page |
| Repository Spotlight | Pin up to 3 repos on public profile |
| GitHub Achievements sync | Scraped and cached from GitHub profile |
| Public leaderboard | Opt-in, ranked by streak / commits / PRs |
| Discord webhook integration | Streak reminders and milestone alerts |
| Wakatime integration | Coding time and language breakdown |
| Multi-account GitHub linking | Switch accounts on the dashboard |
| Weekly email digest | Opt-in Monday morning summary |
| Data export | Full JSON dump of user data |
| AI weekly insights | Groq-powered natural language summary |
| Streak freeze | Protect streak during planned breaks |
| RSS feed | Atom feed at `/u/[username]/feed.xml` |
| Year Wrapped | Animated annual coding journey recap |
| Real-time dashboard | Live Supabase Realtime sync with polling fallback |

### In Progress / Planned

Want to contribute? Pick an item below and open an issue or start a PR.

| Feature | Difficulty | Issue |
|---|---|---|
| Contribution heatmap calendar | Intermediate | [#18](https://github.com/omen18/codestride/issues/18) |
| Chart type toggle (bar / line) | Intermediate | [#17](https://github.com/omen18/codestride/issues/17) |
| Language breakdown widget | Intermediate | [#32](https://github.com/omen18/codestride/issues/32) |
| Activity feed | Intermediate | [#33](https://github.com/omen18/codestride/issues/33) |
| Auto-progress goals from commits | Advanced | [#34](https://github.com/omen18/codestride/issues/34) |
| GitLab integration | Advanced | [#6](https://github.com/omen18/codestride/issues/6) |
| Jira integration | Advanced | — |
| Team dashboards | Advanced | — |
| Embeddable stats widgets | Intermediate | — |
| Mobile app (React Native) | Advanced | — |

---

> For caching best practices used in this project, see [Caching Guidelines](docs/caching.md).

## Contributing

CodeStride actively welcomes contributors of all skill levels.

Setup takes under 10 minutes — see [DEVELOPMENT.md](./DEVELOPMENT.md) for the full walkthrough.

### How to contribute

1. Browse [open issues](https://github.com/omen18/codestride/issues) — start with `good first issue`
2. Comment on the issue to get assigned before starting work
3. Fork → branch (`feat/issue-42-description`) → PR against `main`
4. Ensure CI passes: `pnpm run lint && pnpm run type-check`

See **[CONTRIBUTING.md](./CONTRIBUTING.md)** for commit style, branch naming, and the review process.

Questions? Open a [Discussion](https://github.com/omen18/codestride/discussions).

---

## Built With

CodeStride is built on best-in-class open-source infrastructure. Sponsoring helps us keep using these tools and exposes them to 224+ active contributors.

| Partner | Role in CodeStride |
|---|---|
| [Supabase](https://supabase.com) | PostgreSQL database, auth, Row Level Security, and Realtime sync |
| [Vercel](https://vercel.com) | Hosting, CI/CD, and preview deployments |
| [Groq](https://groq.com) | AI-powered weekly coding insights |
| [Wakatime](https://wakatime.com) | Coding time tracking and language analytics |

---

## Sponsors

CodeStride is free and open source, built by **224+ contributors** worldwide. Sponsoring directly funds:

- **Supabase and Vercel infrastructure** — keeping the hosted demo fast and free for every contributor
- **Groq API costs** — powering AI weekly insights for all users
- **Maintainer time** — code review, issue triage, and release management

With **130+ stars**, **369 forks**, **800+ merged PRs**, and **224 contributors**, CodeStride is one of the most active open-source developer-productivity projects on GitHub. Your logo here reaches a highly technical, actively coding audience.

### Sponsor Tiers

| Tier | Amount | Perks |
|---|---|---|
| Coffee | $5 / mo | Your name in this README |
| Backer | $15 / mo | Name + priority response on issues |
| Champion | $50 / mo | Name + logo in README + feature request priority |
| One-time | $10+ | One-time thanks, no recurring commitment |

### Current Sponsors

> Be the first sponsor — your logo or name will appear here. See tiers above.

**[Sponsor CodeStride on GitHub →](https://github.com/sponsors/omen18)** · **[Buy Me a Chai →](https://www.buymeachai.in/codestride)**

Want a standalone sponsor brief to share with your company's finance team? See [docs/SPONSORS.md](./docs/SPONSORS.md).

---

## Community

Have questions, ideas, or want to connect with other contributors?

- **[GitHub Discussions](https://github.com/omen18/codestride/discussions)** — ask questions, share ideas, show what you've built
- **[Open an Issue](https://github.com/omen18/codestride/issues/new/choose)** — bug reports, feature requests, and good-first-issues
- **[Email the maintainer](mailto:)** — for anything else

All contributors are expected to follow the [Code of Conduct](./CODE_OF_CONDUCT.md).

---

## Star History

<div align="center">

<a href="https://star-history.com/#omen18/codestride&Date">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/svg?repos=omen18/codestride&type=Date&theme=dark" />
    <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/svg?repos=omen18/codestride&type=Date" />
    <img alt="Star History Chart" src="https://api.star-history.com/svg?repos=omen18/codestride&type=Date" width="600" />
  </picture>
</a>

</div>

---

## License

MIT — see [LICENSE](./LICENSE) for details.

---

## Maintainers

| Name | GitHub | Role |
|---|---|---|
| Yash Raj Sharan | [@omen18](https://github.com/omen18) | Founder & Maintainer |

---

## Contributors

Thanks to everyone who has helped build CodeStride. Want to join the list? See [CONTRIBUTING.md](./CONTRIBUTING.md) and pick a [good first issue](https://github.com/omen18/codestride/issues?q=label%3A%22good+first+issue%22).

<div align="center">

<a href="https://github.com/omen18/codestride/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=omen18/codestride" alt="Contributors" />
</a>

</div>

---

<div align="center">

Built by the CodeStride community · [codestride-silk-kappa.vercel.app](https://codestride-silk-kappa.vercel.app)

Star this repo if CodeStride is useful to you.

</div>
