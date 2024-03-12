# Sveltekit SaaS Full-Stack

Techstack:
sveltekit, pocketbase, stripe
Everything you need to build a Svelte project, powered by [`create-svelte`](https://github.com/sveltejs/kit/tree/main/packages/create-svelte).

## Creating a project

If you're seeing this, you've probably already done this step. Congrats!

```bash
# create a new project in the current directory
npm create svelte@latest

# create a new project in my-app
npm create svelte@latest my-app
```

## Developing

Once you've created a project and installed dependencies with `npm install` (or `pnpm install` or `yarn`), start a development server:

```bash
npm run dev

# or start the server and open the app in a new browser tab
npm run dev -- --open
```

## Building

To create a production version of your app:

```bash
npm run build
```

You can preview the production build with `npm run preview`.

> To deploy your app, you may need to install an [adapter](https://kit.svelte.dev/docs/adapters) for your target environment.


## Pocketbase back-end
Open Source backend for your next SaaS and Mobile app in 1 file written in go. Light-weight (Firebase, supabase alternative). Can support up to 10,000 concurrent user on low spec hosting server.
(PocketBase can easily serve 10,000+ persistent realtime connections on a cheap $4 Hetzner CAX11 VPS (2vCPU, 4GB RAM)).

[Pocketbase install](https://pocketbase.io/docs/) - Follow the official documentation
[Download Pocketbase](https://github.com/pocketbase/pocketbase/releases/download/v0.22.3/pocketbase_0.22.3_windows_amd64.zip)

To run pocketbase type:
./pocketbase serve

STRIPE ENV


## About deployment

Front-end page - Cloudflare

Back-end - DigitalOcean
