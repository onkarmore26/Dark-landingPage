# SvelteKit Starter - Prismic Minimal

This is a minimal SvelteKit starter template integrated with Prismic CMS, TailwindCSS, and additional development tools.

## Features

- **SvelteKit** for modern web development
- **Prismic** CMS integration
- **TailwindCSS** for styling
- **GSAP** for animations
- **ESLint & Prettier** for code formatting and linting

## Getting Started

### Prerequisites

Ensure you have the following installed:

- [Node.js](https://nodejs.org/) (LTS recommended)
- [npm](https://www.npmjs.com/) or [pnpm](https://pnpm.io/)

### Development

To start the development server:

```sh
npm run dev
```

This will run the project locally with hot-reloading.

### Build for Production

To create a production build:

```sh
npm run build
```

To preview the production build:

```sh
npm run preview
```

### Linting & Formatting

- Check linting:
  ```sh
  npm run lint
  ```
- Format code:
  ```sh
  npm run format
  ```

## Scripts

| Command           | Description                        |
| ----------------- | ---------------------------------- |
| `npm run dev`     | Start the development server       |
| `npm run build`   | Build the project for production   |
| `npm run preview` | Preview the production build       |
| `npm run check`   | Run type checking with SvelteCheck |
| `npm run lint`    | Check code for linting issues      |
| `npm run format`  | Format the code using Prettier     |

## Dependencies

### Development Dependencies

- `eslint`, `prettier`, `tailwindcss`, `vite`
- `@sveltejs/kit`, `@tailwindcss/typography`
- `svelte-check`, `typescript`

### Production Dependencies

- `@prismicio/client`, `@prismicio/svelte`
- `gsap`, `clsx`

## License

This project is licensed under the [MIT License].

---

Happy coding! 🚀
