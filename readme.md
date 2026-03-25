# Workshop@Festival of Learning 2026

Website for the Workshop at the Festival of Learning 2026 — a workshop exploring the future of education, learning analytics, and technology-enhanced learning.

## Site Structure

- **Homepage** — Banner with event details, about section, goals & objectives, expected outcomes
- **Schedule** — Programme timetable
- **Organisers** — Organising committee profiles
- **Privacy Policy** — Legal compliance

## Getting Started

### Prerequisites

- [Hugo Extended v0.151+](https://gohugo.io/installation/)
- [Node v22+](https://nodejs.org/en/download/)
- [Go v1.24+](https://go.dev/doc/install)

### Install Dependencies

```bash
npm install
```

### Development

```bash
npm run dev
```

### Build

```bash
npm run build
```

## Customisation

| What | Where |
|---|---|
| Site title & base URL | `hugo.toml` |
| Logo, nav button, metadata | `config/_default/params.toml` |
| Navigation menus | `config/_default/menus.en.toml` |
| Colors & fonts | `data/theme.json` |
| Social links | `data/social.json` |
| Homepage content | `content/english/_index.md` |
| Schedule | `content/english/pages/schedule.md` |
| Organisers | `content/english/organisers/` |

## Credits

Built with [Hugoplate](https://github.com/zeon-studio/hugoplate) — a Hugo + Tailwind CSS starter template by [Zeon Studio](https://zeon.studio/), released under the [MIT License](https://github.com/zeon-studio/hugoplate/blob/main/LICENSE).
