# Vite + React starter

The base for new [Frend](https://github.com/meetfrend) projects: Vite, React, TypeScript, Tailwind CSS v4 and shadcn/ui.

```bash
pnpm install
pnpm dev
```

| Script | What it does |
| --- | --- |
| `pnpm dev` | Dev server with hot reload |
| `pnpm build` | Typecheck and build for production |
| `pnpm typecheck` | TypeScript only |
| `pnpm lint` | oxlint |

Add components with `pnpm dlx shadcn@latest add <name>`. Theme tokens live in `src/index.css`. `@/` points to `src/`.
