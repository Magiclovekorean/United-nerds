# United Nerds

**United Nerds** is a movement that aims to stop discrimination, segregation, and indirect discrimination against nerds (people who are different).

## 📖 About the Project

This is a website built with Astro that presents the United Nerds movement. The project aims to raise awareness about discrimination against nerds and promote inclusion and acceptance of people who are different.

## 🚀 Technologies Used

- **Astro** - Modern web framework for building fast static sites
- **CSS** - Global styles with variables and responsiveness
- **Noto Sans** - Google Font for typography

## 📁 Project Structure

```
/
├── public/
│   ├── favicon.svg
│   ├── icon.webp
│   └── github-icon.astro
├── src/
│   ├── components/
│   │   ├── Index/
│   │   │   ├── About.astro
│   │   │   └── Header.astro
│   │   └── Nav.astro
│   ├── layouts/
│   │   └── Layout.astro
│   ├── pages/
│   │   └── index.astro
│   └── styles/
│       └── global.css
├── astro.config.mjs
├── package.json
└── pnpm-lock.yaml
```

## 🔧 Commands

All commands are run from the project root, in a terminal:

| Command              | Action                                          |
| :------------------- | :----------------------------------------------- |
| `pnpm install`       | Install dependencies                             |
| `pnpm dev`           | Start the development server at `localhost:4321` |
| `pnpm build`         | Build the site for production to `./dist/`      |
| `pnpm preview`       | Preview the local build before deploying         |
| `pnpm astro ...`     | Run CLI commands like `astro add`, `astro check` |
| `pnpm astro -- --help` | Get help using the Astro CLI                   |

## 📄 Pages and Components

### Home Page (`index.astro`)
Home page includes:
- **Header**: Main title "UNITED NERDS"
- **About**: Section explaining what the United Nerds movement is

### Components

- **Nav.astro**: Main navigation with links to:
  - Home page
  - GitHub repository to contribute
  
- **Hero.astro**: Component that displays the main title of the movement

- **About.astro**: Component that contains the description and message of the movement

- **Layout.astro**: Main layout that includes:
  - Meta tags and document configuration
  - Loading of the Noto Sans font from Google Fonts
  - Base HTML structure with the Nav component

## 🎨 Styles

The project uses a dark theme with:
- Background color: `#292E38`
- Text color: white with variations
- Font: Noto Sans (Google Fonts)
- Sticky navigation with icons and hover effects

## 📚 Resources

- [Astro Documentation](https://docs.astro.build)

## 🧰 VS Code Tasks (.vscode/tasks.json)

This repository includes a public `.vscode/tasks.json` file to make development easier in VS Code.

- Available task:
  - `pnpm: dev` — runs the development server (Vite) and is configured to auto-run when the folder opens in VS Code.
- How to run manually:
  - Open the Command Palette and run: “Tasks: Run Task” → select `pnpm: dev`.
- Auto-run behavior:
  - The task has `runOn: folderOpen`, so VS Code will prompt to run it when you open the workspace.
