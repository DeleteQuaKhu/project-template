# project-template

A GitHub template repository for new projects: a tiered rule system (`rules/`),
a task log and spec (`docs/`), and a verify + CI pipeline (`scripts/verify.sh`,
`.github/workflows/ci.yml`).

## Run

```bash
pnpm install
pnpm build
pnpm start
```

## Test

```bash
pnpm test
bash scripts/verify.sh   # typecheck + lint + test + build, in order
```

## Environment variables

Copy `.env.example` to `.env` and fill in real values. Never commit `.env*`;
`.env.example` is the only tracked env file.
