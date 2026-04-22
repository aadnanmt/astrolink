# Linktree Astro Migration

This directory contains the migrated Astro version of the modern linktree alternative originally created by **ZeX**.

The goal of this migration is to improve maintainability and developer experience by leveraging Astro's component-based architecture.

## Project Structure

Inside of your Astro project, you'll see the following folders and files:

```text
/
├── public/
├── src/
│   ├── components/
│   ├── data/
│   ├── layouts/
│   └── pages/
│       └── index.astro
└── package.json
```

Any static assets, like images, can be placed in the `public/` directory.

## Commands

All commands are run from the root of the project, from a terminal:

| Command       | Action                                       |
| :------------ | :------------------------------------------- |
| `bun install` | Installs dependencies                        |
| `bun dev`     | Starts local dev server at `localhost:4321`  |
| `bun build`   | Build your production site to `./dist/`      |
| `bun preview` | Preview your build locally, before deploying |

## Acknowledgments

- The original static HTML/CSS version was created by [ZeX](github.com/ddosnotification/links-portfolio), as per the `LICENSE` file.
- This version was migrated to Astro to facilitate easier updates and management.
