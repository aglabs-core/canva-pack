Build command: pnpm install --ignore-scripts && pnpm --filter @workspace/pack-canva run build
Output dir: artifacts/pack-canva/dist/public
Env vars: NODE_ENV=production, BASE_PATH=/, PORT=3000


O workflow `quality.yml` executa a instalação do lockfile, a verificação de tipos e o build nos PRs e na branch `main`. O check também confere o HTML gerado.
