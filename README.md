# ts-toolkit-cli-app

Learning TypeScript by building tiny CLIs

## Examples

```bash
npx . convert data.csv -d ';'
# or after npm link: cliparse convert data.csv
```

## Install

```bash
npm install
npm run build
```

## Highlights

- Strict tsconfig, no any
- npm link friendly
- commander-based subcommands
- Ships as an ESM binary

## Project structure

```text
├── .github/
│   └── workflows/
│       └── ci.yml
├── docs/
│   ├── roadmap.md
│   └── usage.md
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

## License

MIT licensed, see LICENSE.
