# TV Layout

A modern, responsive TV screen layout built with Astro and Tailwind CSS.

## Features

- Responsive grid layout
- Animated promotional content
- News ticker with headers
- Video feed display
- Modern UI with Tailwind CSS

## Project Structure

```
src/
  ├── components/
  │   ├── TVLayout.astro      # Main layout component
  │   ├── SidebarPanel.astro  # Left sidebar with logo and promotions
  │   ├── Footer.astro        # Bottom section with news and customer promo
  │   └── MainContent.astro   # Main content area for video feed
  ├── layouts/
  │   └── Layout.astro        # Base layout with Tailwind CSS
  └── pages/
      └── index.astro         # Main page
```

## Getting Started

1. Install dependencies:
   ```bash
   npm install
   ```

2. Start the development server:
   ```bash
   npm run dev
   ```

3. Build for production:
   ```bash
   npm run build
   ```

## Customization

- Add your logo to `/public/placeholder-logo.png`
- Add promotional images to `/public/promo1.jpg`, `/public/promo2.jpg`, etc.
- Add customer promotional image to `/public/customer-promo.jpg`
- Update news items in the Footer component
- Add video URL to the MainContent component

## Technologies Used

- Astro
- Tailwind CSS
- TypeScript

```sh
npm create astro@latest -- --template minimal
```

[![Open in StackBlitz](https://developer.stackblitz.com/img/open_in_stackblitz.svg)](https://stackblitz.com/github/withastro/astro/tree/latest/examples/minimal)
[![Open with CodeSandbox](https://assets.codesandbox.io/github/button-edit-lime.svg)](https://codesandbox.io/p/sandbox/github/withastro/astro/tree/latest/examples/minimal)
[![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://codespaces.new/withastro/astro?devcontainer_path=.devcontainer/minimal/devcontainer.json)

> 🧑‍🚀 **Seasoned astronaut?** Delete this file. Have fun!

## 🚀 Project Structure

Inside of your Astro project, you'll see the following folders and files:

```text
/
├── public/
├── src/
│   └── pages/
│       └── index.astro
└── package.json
```

Astro looks for `.astro` or `.md` files in the `src/pages/` directory. Each page is exposed as a route based on its file name.

There's nothing special about `src/components/`, but that's where we like to put any Astro/React/Vue/Svelte/Preact components.

Any static assets, like images, can be placed in the `public/` directory.

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:4321`      |
| `npm run build`           | Build your production site to `./dist/`          |
| `npm run preview`         | Preview your build locally, before deploying     |
| `npm run astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `npm run astro -- --help` | Get help using the Astro CLI                     |

## 👀 Want to learn more?

Feel free to check [our documentation](https://docs.astro.build) or jump into our [Discord server](https://astro.build/chat).
