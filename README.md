# Paso React

[![Live Demo](https://img.shields.io/badge/Live%20Demo-PasoReact-blue?style=flat-square)](https://passreact.netlify.app/)
[![React](https://img.shields.io/badge/React-16.13.1-informational?style=flat-square&logo=react)](https://reactjs.org/)
[![Create React App](https://img.shields.io/badge/CRA-3.4.1-lightgrey?style=flat-square)](https://create-react-app.dev/)

## Overview

Paso React is a modern landing page SPA built with Create React App. It combines responsive UI sections, reusable component structure, and client-side routing to showcase services, case studies, blog content, team profiles, and contact details.

The project is deployment-ready and works well on static hosts like Netlify.

## Live Demo

- https://passreact.netlify.app/

## Features

- Responsive multi-section landing page layout
- Reusable React components for pages and content blocks
- Smooth navigation with `react-router-dom`
- Bootstrap-driven UI with custom Sass styling
- Carousel and animated content support
- Production-ready build artifact in `build/`

## Tech Stack

- React 16.13.1
- Create React App
- React Router DOM
- Bootstrap 4
- Sass
- React Icons
- React Owl Carousel
- React Accessible Accordion
- React Bootstrap

## Installation

Clone the repository and install dependencies:

```bash
git clone <repository-url>
cd pasoReact
npm install
```

## Usage

Start the development server:

```bash
npm start
```

Open http://localhost:3000 in your browser. The development server reloads when code changes.

## Scripts

| Command | Description |
|--------|-------------|
| `npm start` | Start development server |
| `npm test` | Launch test runner |
| `npm run build` | Create production build in `build/` |
| `npm run eject` | Eject CRA configuration (one-way) |

### `npm run eject`

**Warning:** ejecting is irreversible. It copies all configuration files and dependencies (webpack, Babel, ESLint, etc.) into the project so you can maintain them directly.

## Deployment

Build the app for production:

```bash
npm run build
```

Deploy the generated `build/` directory to a static hosting provider such as Netlify, Vercel, or GitHub Pages.

## Configuration

No custom environment variables are required by default.

If environment-specific configuration is needed later, add a `.env` file to the project root and follow Create React App environment variable conventions.

## Project Structure

- `public/` — static assets and HTML template
- `src/` — source code, components, pages, and styles
- `src/components/` — reusable UI components
- `src/pages/` — page-level route components
- `src/router/` — routing configuration
- `build/` — production build output

## Learn More

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

- [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started)
- [React documentation](https://reactjs.org/)

### Additional Resources

- Code splitting: https://facebook.github.io/create-react-app/docs/code-splitting
- Analyzing bundle size: https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size
- Progressive Web App: https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app
- Advanced configuration: https://facebook.github.io/create-react-app/docs/advanced-configuration
- Deployment: https://facebook.github.io/create-react-app/docs/deployment
- `npm run build` fails to minify: https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify
