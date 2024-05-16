## [Installation](https://nextjs.org/docs/getting-started/installation#installation)
System Requirements:

- [Node.js 18.17](https://nodejs.org/) or later.
- macOS, Windows (including WSL), and Linux are supported.

## [Automatic Installation](https://nextjs.org/docs/getting-started/installation#automatic-installation)

We recommend starting a new Next.js app using [`create-next-app`](https://nextjs.org/docs/app/api-reference/create-next-app), which sets up everything automatically for you. To create a project, run:

Terminal

```
npx create-next-app@latest portfolio
```

On installation, you'll see the following prompts:

Terminal

```
> cd portfolio
> code .
> What is your project named? my-app
> Would you like to use TypeScript? No / Yes
> Would you like to use ESLint? No / Yes
> Would you like to use Tailwind CSS? No / Yes
> Would you like to use `src/` directory? No / Yes
> Would you like to use App Router? (recommended) No / Yes
> Would you like to customize the default import alias (@/*)? No / Yes
> What import alias would you like configured? @/*
```

After the prompts, `create-next-app` will create a folder with your project name and install the required dependencies.

If you're new to Next.js, see the [project structure](https://nextjs.org/docs/getting-started/project-structure) docs for an overview of all the possible files and folders in your application.

> **Good to know**:
> 
> - Next.js now ships with [TypeScript](https://nextjs.org/docs/app/building-your-application/configuring/typescript), [ESLint](https://nextjs.org/docs/app/building-your-application/configuring/eslint), and [Tailwind CSS](https://nextjs.org/docs/app/building-your-application/styling/tailwind-css) configuration by default.
> - You can optionally use a [`src` directory](https://nextjs.org/docs/app/building-your-application/configuring/src-directory) in the root of your project to separate your application's code from configuration files.

---

## [Run the Development Server](https://nextjs.org/docs/getting-started/installation#run-the-development-server)

1. Run `npm run dev` to start the development server.
2. Visit `http://localhost:3000` to view your application.
3. Edit `app/page.tsx` (or `pages/index.tsx`) file and save it to see the updated result in your browser.
