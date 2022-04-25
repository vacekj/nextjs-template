# Atris Next.js Template

Personal Next template with fast tooling and sensible defaults.

Features

- Rust-based tooling
- ChakraUI
- Cypress for E2E testing
- dprint formatter
- ESLint with Next config

## How to use it?

1. Use [pnpm](https://pnpm.io/) to create a new repo with this template:

```bash
pnpm create next-app -- --use-pnpm -e https://github.com/vacekj/nextjs-template my-next-app
```

2. Install additional dependencies:

- [dum](https://github.com/egoist/dum) for running `package.json` scripts
  - `brew install egoist/tap/dum`
