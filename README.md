# React Vite Shadcn Template

A modern, high-performance React + Vite + TypeScript template featuring [shadcn/ui](https://ui.shadcn.com/) components and Tailwind CSS. Designed for rapid development, easy customization, and best practices out of the box.

**You can use this repository as a template for your own projects by clicking the "Use this template" button on GitHub.**

## Features

- ⚡️ Lightning-fast development with Vite
- 🧑‍💻 TypeScript support
- 🎨 Tailwind CSS for utility-first styling
- 🧩 [shadcn/ui](https://ui.shadcn.com/) component library
- 🛠️ Linting and formatting with ESLint and Prettier
- 🧪 Ready for testing and CI
- 📦 Simple, extendable project structure

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v22+ recommended)
- [pnpm](https://pnpm.io/) (recommended)

### Installation

```zsh
pnpm install
```

### Development

```zsh
pnpm dev
```

### Build

```zsh
pnpm build
```

### Lint & Format

```zsh
pnpm lint
pnpm format
```

## Project Structure

```
react-vite-shadcn-template/
├── src/
│   ├── components/
│   │   └── ui/
│   │       └── button.tsx
│   ├── lib/
│   │   └── utils.ts
│   ├── App.tsx
│   ├── main.tsx
│   └── index.css
├── public/
│   └── vite.svg
├── package.json
├── vite.config.ts
├── tsconfig.json
└── ...
```

## Contributing

We welcome contributions! Please follow these steps:

### 1. Fork the repository

Click the **Fork** button at the top right of this page.

### 2. Clone your fork

```zsh
git clone https://github.com/your-username/react-vite-shadcn-template.git
cd react-vite-shadcn-template
pnpm install
```

### 3. Create a new branch

```zsh
git checkout -b feat/your-feature
```

### 4. Make your changes

- Follow the existing code style.
- Run `pnpm lint` and `pnpm format` before committing.

### 5. Commit your changes

We use [Conventional Commits](https://www.conventionalcommits.org/):

```zsh
git commit -m "feat(component): add new feature"
```

### 6. Push and open a Pull Request

```zsh
git push origin feat/your-feature
```

Open a Pull Request on GitHub and describe your changes.

### 7. Pre-commit Hooks

This repo uses Husky to enforce linting and formatting before commits. If you have issues, run:

```zsh
pnpm prepare
```

## License

MIT License
