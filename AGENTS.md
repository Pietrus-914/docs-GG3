# GG3 documentation — agent instructions

## About this project

- This is the official documentation site for [GG3](https://gg3.org), built on [Mintlify](https://mintlify.com).
- Pages are MDX files with YAML frontmatter (`title`, `description`).
- Configuration lives in `docs.json`.
- Run `mint dev` to preview locally and `mint broken-links` to validate links.

## Terminology (use these spellings)

- **GG3** — the platform (not "gg3", "GG-3", or "Gg3").
- **GGX** — the token (BEP-20 on BNB Smart Chain).
- **G-Bucks** — internal currency, fixed value `100 G-Bucks = 1 USD`. Not a cryptocurrency.
- **Quest** / **MainQuest** / **SubQuest** — capitalize when referring to the platform concept.
- **GG-Button** — daily button on the dashboard (hyphenated, capital G).
- **Chest** — reward container (singular: Chest; types: Common, Rare, Unique, Epic, Legendary).

## Style preferences

- Use active voice and second person ("you").
- Keep sentences concise — one idea per sentence.
- Use sentence case for headings (`## Quest Hierarchy`, not `## QUEST HIERARCHY`).
- Bold for UI elements: Click **Settings**.
- Code formatting for file names, commands, paths, addresses (e.g. `0x7bedaA6e5f43e1d83d667CfE770252a32532369E`).
- Always include the warning **"Beware of scams!"** next to the GGX contract address.

## Content boundaries

- Do not document internal admin tools, partner-private endpoints, or unannounced features.
- Tokenomics numbers (allocations, APRs, vesting) must match the canonical values in `tokenomics/`.
- Do not introduce price predictions or financial advice.
