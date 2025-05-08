# IndicVue

Ce dépôt est un environnement de test pour l'intégration continue et le déploiement continu (CI/CD) avec Nuxt 3. Il sert de modèle pour mettre en place et tester des workflows GitHub Actions.

## Fonctionnalités

- Basé sur Nuxt 3 avec TypeScript
- Configuration CI/CD via GitHub Actions
- Tests automatisés lors des pull requests
- Déploiement automatique lors des fusions vers la branche principale

## Prérequis

- Node.js 18.x ou supérieur
- npm, yarn, pnpm ou bun

## Installation

```bash
# npm
npm install

# pnpm
pnpm install

# yarn
yarn install

# bun
bun install
```

## Développement

Lancez le serveur de développement sur `http://localhost:3000` :

```bash
# npm
npm run dev

# pnpm
pnpm dev

# yarn
yarn dev

# bun
bun run dev
```

## Workflows CI/CD

Ce projet contient plusieurs workflows GitHub Actions dans le dossier `.github/workflows/` :

- **Lint & Test** : Exécuté à chaque push et pull request
- **Build & Deploy** : Exécuté automatiquement lors des fusions dans la branche principale

## Production

Construisez l'application pour la production :

```bash
# npm
npm run build

# pnpm
pnpm build

# yarn
yarn build

# bun
bun run build
```

Prévisualisez la version de production en local :

```bash
# npm
npm run preview

# pnpm
pnpm preview

# yarn
yarn preview

# bun
bun run preview
```

## Modules Nuxt utilisés

- @nuxt/fonts
- @nuxt/icon
- @nuxt/image
- @nuxt/scripts
