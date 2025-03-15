# Vite + React + ESLint + Prettier

A minimal setup for Vite + React projects:

- **React 19** with TypeScript for building user interfaces
- **Vite** for fast development and optimized production builds
- **ESLint** with flat config format for static code analysis
- **Prettier** integrated through ESLint for consistent code formatting
- **TypeScript** for type safety and improved developer experience

## Features

### Vite

Vite provides an extremely fast development experience with:
- Lightning-fast hot module replacement (HMR)
- Optimized production builds
- Out-of-the-box support for TypeScript, JSX, and CSS

This project uses [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc/blob/main/README.md) which uses [SWC](https://swc.rs/) for Fast Refresh.

### ESLint Configuration

The ESLint setup uses the modern flat config format and includes:

- **typescript-eslint**: Advanced TypeScript linting with type-checking
- **eslint-plugin-react-hooks**: Enforces Rules of Hooks and other best practices
- **eslint-plugin-react-refresh**: Validates components are safe for Fast Refresh
- **eslint-plugin-react-x** and **eslint-plugin-react-dom**: React-specific rules for better practices
- **eslint-plugin-import**: Import/export validation with TypeScript support
- **eslint-plugin-prettier**: Seamlessly integrates Prettier with ESLint

### Prettier Integration

Prettier is integrated through ESLint using the `eslint-plugin-prettier` configuration, enabling:
- Consistent code formatting across the project
- Automatic fixing of formatting issues alongside linting errors
- No conflicts between ESLint's stylistic rules and Prettier formatting

## Getting Started

Clone this repository

```bash
git clone git@github.com:leotaozeng/vite-react-eslint-prettier.git
```

Install dependencies:

```bash
pnpm install
```

Start the development server:

```bash
pnpm run dev
```

Run linting:
```bash
pnpm run lint
```

## Customizing

You can customize the ESLint and Prettier configuration by modifying the `eslint.config.js` file, which uses the modern ESLint flat config format.
