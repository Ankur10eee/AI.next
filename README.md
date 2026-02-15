# Gravity - AI Tech Enthusiasts Website

## Git & Deployment

> [!IMPORTANT]
> **Do NOT upload the `node_modules` folder to Git.**
> This folder contains thousands of dependency files and is automatically excluded by `.gitignore`.
>
> When you clone or download this project on a new machine, simply run:
> ```bash
> npm install
> ```
> This command reads `package.json` and reconstructs the `node_modules` folder for you.

## Getting Started

1.  **Install Dependencies**:
    ```bash
    npm install
    ```

2.  **Start Dev Server**:
    ```bash
    npm run dev
    ```
    Live at `http://localhost:5173`.

## Features
- Dynamic AI News Feed
- Companies with Hover Interaction
- Dark Mode / Glassmorphism Design
piler is not enabled on this template because of its impact on dev & build performances. To add it, see [this documentation](https://react.dev/learn/react-compiler/installation).

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.
