# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.

```
crypto-dash-project
├─ .env
├─ eslint.config.js
├─ index.html
├─ package.json
├─ public
│  ├─ favicon.ico
│  └─ vite.svg
├─ README.md
├─ src
│  ├─ App.jsx
│  ├─ assets
│  │  └─ react.svg
│  ├─ components
│  │  ├─ CoinCards.jsx
│  │  ├─ CoinChart.jsx
│  │  ├─ FilterInput.jsx
│  │  ├─ Header.jsx
│  │  ├─ LimitSelector.jsx
│  │  ├─ SortSelector.jsx
│  │  └─ Spinner.jsx
│  ├─ index.css
│  ├─ main.jsx
│  └─ pages
│     ├─ about.jsx
│     ├─ coin-details.jsx
│     ├─ home.jsx
│     └─ not-found.jsx
├─ vite.config.js
└─ yarn.lock

```