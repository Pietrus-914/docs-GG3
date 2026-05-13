# GG3 Documentation

Official documentation for [GG3](https://gg3.org) — an AI-powered community engagement platform for gaming and Web3.

Live docs are deployed via [Mintlify](https://mintlify.com) and configured by [`docs.json`](./docs.json).

## Repository structure

```
docs.json          Mintlify configuration (navigation, theme, branding)
favicon.png        Favicon
introduction.mdx   Landing page
logo/              GG3 brand logo (light + dark)
images/            Shared media assets
ai-agents/         GG3 AI Agents — Gideon, Swarm, why AI
airdrop/           GGX airdrop seasons
community/         Social links
getting-started/   Mission & vision
integrations/      External integrations and S2S postbacks
overview/          Platform mechanism, gamification, rewards, store, FAQ, dictionary
tokenomics/        GGX token description, utility, distribution, staking, liquidity mining
```

## Local preview

Install the Mintlify CLI and run it from the repo root:

```bash
npm i -g mint
mint dev
```

The local preview runs at <http://localhost:3000>.

## Publishing

Pushes to `main` are deployed automatically via the Mintlify GitHub App. Connect the app from the [Mintlify dashboard](https://dashboard.mintlify.com/settings/organization/github-app) if it is not already wired up.

## Contributing

See [`CONTRIBUTING.md`](./CONTRIBUTING.md) for content and style guidelines, and [`AGENTS.md`](./AGENTS.md) for AI-assistant context.
