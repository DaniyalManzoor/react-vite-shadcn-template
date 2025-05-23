# Vite React Template

A modern, high-performance React + Vite + TypeScript template for building scalable web applications. This template is designed for rapid development, easy customization, and best practices out of the box.

## Features

- ⚡️ Lightning-fast development with Vite
- 🧑‍💻 TypeScript support
- 🎨 Tailwind CSS for utility-first styling
- 🧩 Modular, reusable component structure
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
vite-react-template/
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
git clone https://github.com/your-username/vite-react-template.git
cd vite-react-template
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
