# First Aid App

This project was converted to a React + Vite application. I backed up the original static files in the `backup/` folder.

## Project structure (important files)

```
firstaid-app/
├── index.html          # Vite entry (mounts React app)
├── package.json
├── src/
│   ├── main.jsx
│   ├── App.jsx
│   └── index.css
├── backup/             # original static files saved here
```

## Run locally

1. Install dependencies

```powershell
npm install
```

2. Start dev server

```powershell
npm run dev
```

Visit the URL printed by Vite (usually http://localhost:5173).

## Notes

- The original `index.html`, `css/style.css`, `js/main.js`, and `README.md` were copied to `backup/`.
- Use `git status` / `git log` to review commits before pushing further changes.

Happy hacking!