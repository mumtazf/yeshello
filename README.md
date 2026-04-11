# Say Hello 

This is a quick website I built using Astro. Saying hello is important! So why not make a website about it?


# Astro quick tutorial if you're interested

Astro is a framework that helps you quickly build HTML/CSS/JS websites. It is easy to use because it autocreates folder structures and supports react, vue, etc. so you can customize your website the way you'd like

1. How to start? 
   
```sh
npm create astro@latest -- --template minimal
```

2. Project Structure

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

3. 
All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:4321`      |
| `npm run build`           | Build your production site to `./dist/`          |
| `npm run preview`         | Preview your build locally, before deploying     |
| `npm run astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `npm run astro -- --help` | Get help using the Astro CLI                     |

Learn more [from their documentation](https://docs.astro.build)