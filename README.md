# Welcome to Astro Simple Blog

A simple blog built using [Astro](https://astro.build)

![screenshot](screenshot.png)

## π Project Structure

Inside of your Astro project, you'll see the following folders and files:

```
/
βββ public/
β   βββ robots.txt
β   βββ favicon.ico
βββ src/
β   βββ components/
β   β   βββ Tour.astro
β   βββ pages/
β       βββ index.astro
βββ package.json
```

Astro looks for `.astro` or `.md` files in the `src/pages/` directory. Each page is exposed as a route based on its file name.

There's nothing special about `src/components/`, but that's where we like to put any Astro/React/Vue/Svelte/Preact components.

Any static assets, like images, can be placed in the `public/` directory.

## π§ Commands

All commands are run from the root of the project, from a terminal:

| Command           | Action                                       |
| :---------------- | :------------------------------------------- |
| `npm install`     | Installs dependencies                        |
| `npm run dev`     | Starts local dev server at `localhost:3000`  |
| `npm run build`   | Build your production site to `./dist/`      |
| `npm run preview` | Preview your build locally, before deploying |

## π Want to learn more?

Feel free to check [our documentation](https://github.com/withastro/astro) or jump into our [Discord server](https://astro.build/chat).

## Credits

- [Maxi Ferreira](https://github.com/Charca/astro-blog-template)
- [Edvinas DaneviΔius](https://github.com/Edvinas01/edvinas-dev)

## To-do

- [x] Make date human readable
- [ ] Refractor post slug route
