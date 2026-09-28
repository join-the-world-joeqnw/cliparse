# cliparse

Small TypeScript CLI: CSV to JSON converter

## What it does

- Ships as an ESM binary
- Strict tsconfig, no any
- commander-based subcommands
- npm link friendly

## How to use

```bash
npx . convert data.csv -d ';'
# or after npm link: cliparse convert data.csv
```

## Installation

```bash
npm install
npm run build
```

## Project structure

```text
├── .github/
│   └── workflows/
│       └── ci.yml
├── docs/
│   ├── configuration.md
│   ├── development.md
│   └── usage.md
├── examples/
│   └── quickstart.md
├── scripts/
│   └── dev.sh
├── src/
│   └── index.ts
├── .gitignore
├── CHANGELOG.md
├── CONTRIBUTING.md
├── LICENSE
├── SECURITY.md
├── package.json
└── tsconfig.json
```

## Development

```bash
npm install
```

## Why

Needed this for myself; figured others might too.

## License

MIT - see [LICENSE](LICENSE).
