# How to Start the Project

## Prerequisites

- Node.js v20 or higher
- npm

## Installation

1. Install dependencies:

```bash
npm install
```

2. **Windows users only:** If you encounter an error about `@rollup/rollup-win32-x64-msvc`, run:

```bash
npm install @rollup/rollup-win32-x64-msvc
```

> This is a known npm bug with optional dependencies on Windows. See: https://github.com/npm/cli/issues/4828

## Running the Development Server

```bash
npm run dev
```

The site will be available at: **http://localhost:4321/**

## Available Scripts

| Command | Description |
|---------|-------------|
| `npm run dev` | Start development server |
| `npm run start` | Start development server (alias) |
| `npm run build` | Build for production |
| `npm run preview` | Preview production build |

## Pages

- `/` - Home page
- `/privacy` - Privacy policy
- `/terms` - Terms of service
- `/delete-account` - Account deletion page
