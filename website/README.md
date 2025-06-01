# Nuxt Minimal Starter

Look at the [Nuxt documentation](https://nuxt.com/docs/getting-started/introduction) to learn more.

## Setup

Make sure to install dependencies:

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

## Development Server

Start the development server on `http://localhost:3000`:

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

## Production

Build the application for production:

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

Locally preview production build:

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

Check out the [deployment documentation](https://nuxt.com/docs/getting-started/deployment) for more information.


## Using ShadCN

```bash
bunx --bun shadcn-vue@latest add button #the add button here is your component name
```

## Using Inspirar UI
```bash
#Creating your Wesbite
bun create nuxt website

# Make sure these mf are globally scoped
npm install -g @tailwindcss/cli
npm install -g nuxi

# Installing tailwindCSS V4
bun install tailwindcss @tailwindcss/vite

#adding SHADCN
bunx --bun nuxi@latest module add shadcn-nuxt
bun add shadcn-vue@latest
bunx --bun shadcn-vue@latest init

# Adding Inspira UI 
bun add -d @inspira-ui/plugins clsx tailwind-merge class-variance-authority tailwindcss-animate
bun add @vueuse/core motion-v
bun add motion-v
```

## Note:
- If the command ain't work just get rid of the @latest ie "bunx shadcn-vue add "https://inspira-ui.com/r/pattern-background.json""
- also for some reason your desktop comp keeps blocking bun request just take note