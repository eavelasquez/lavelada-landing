# La Velada Landing

This is a landing page for La Velada, a boxing event organized by the well-known streamer [Ibai Llanos](https://twitch.tv/ibai).

## Preview

<img width="1799" alt="Screenshot from 2023-05-20" src="https://repository-images.githubusercontent.com/643387733/3416676f-01ac-4c77-96d9-a55fee8c9bf6">

## 🚀 Project Structure

This project is built with [Astro](https://astro.build), a new framework for building websites using JavaScript, HTML, and CSS. Inside of this project, you'll see the following folders and files:

```
/
├── public/
│   ├── assets/
│   ├── boxers/
│   ├── fonts/
│   ├── favicon.svg
├── src/
│   ├── components/
│   │   ├── Advertisements.astro
│   │   ├── Background.astro
│   │   ├── Footer.astro
│   │   ├── Header.astro
│   │   ├── Hero.astro
│   │   ├── Map.astro
│   │   └── Notice.astro
│   └── pages/
│       └── index.astro
├── astro.config.mjs
├── package.json
└── tailwind.config.js
```

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                    | Action                                           |
| :------------------------- | :----------------------------------------------- |
| `pnpm install`             | Installs dependencies                            |
| `pnpm run dev`             | Starts local dev server at `localhost:3000`      |
| `pnpm run optimize:all`    | Optimize all images in `./public/`               |
| `pnpm run build`           | Build your production site to `./dist/`          |
| `pnpm run preview`         | Preview your build locally, before deploying     |
| `pnpm run astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `pnpm run astro -- --help` | Get help using the Astro CLI                     |

**Note:** To excute the `optimize:all` command, you need to have [WebP](https://developers.google.com/speed/webp) installed on your machine.
