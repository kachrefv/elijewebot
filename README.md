# Elijeweb Next.js Project

This is a Next.js project, converted from a Petite-Vue and Tailwind CSS single-file application.

## Getting Started

First, install the dependencies:

```bash
npm install
# or
yarn install
# or
pnpm install
```

Then, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

## Project Structure

- `app/`: Contains the main application logic and pages.
  - `layout.tsx`: The root layout for the application, handling global HTML structure and fonts.
  - `page.tsx`: The main landing page component, converted from the original Petite-Vue logic.
  - `globals.css`: Global styles, including Tailwind CSS directives and custom CSS.
- `public/`: Static assets.
- `tailwind.config.ts`: Tailwind CSS configuration.
- `postcss.config.mjs`: PostCSS configuration for Tailwind CSS.
- `next.config.mjs`: Next.js configuration.
- `package.json`: Project dependencies and scripts.
- `tsconfig.json`: TypeScript configuration.
- `.gitignore`: Specifies intentionally untracked files to ignore.
