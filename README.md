# FlexBlog

This project was built during Origamid's [CSS Flexbox](https://www.origamid.com/curso/css-flexbox) course.

## Getting started

There are three scripts available (note that [PNPM](https://pnpm.io) was used for dependency management and script execution), see the ones below:

### dev

Starts a server in development mode with support for live updating in the browser.

```bash
pnpm run dev
```

Then open your browser to `http://localhost:5173` to view the project.

### build

Creates a production version of the project, all source code is minified and placed inside a `dist` folder in the project root.

```bash
pnpm run build
```

That's it, the project is ready to be deployed.

### preview

This script is used to view the previously built production version.

```bash
pnpm run preview
```

Then open your browser to `http://localhost:4173` to view the project.

### Format the code

> [!NOTE]
> Only for VSCode editor

To format the code during development (when saving a file) mode the \*Prettier extension is required. To do this, create a `settings.json` file inside the `.vscode` folder in the root of the project directory, as in the example below:

```
.vscode/
    extensions.json
    settings.json    <--- this file
public/
src/
...
```

Inside it, places these lines below:

```json
{
  "editor.formatOnSave": true,
  "editor.defaultFormatter": "esbenp.prettier-vscode"
}
```

That's it! 🎉

## Recommended extensions

- [EditorConfig](https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig)
- [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)
