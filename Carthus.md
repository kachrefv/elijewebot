# Carthus.md

## Project Overview

Elijeweb is a Next.js application designed to function as an AI sales assistant for Meta platforms. It automates customer interactions, manages orders, tracks stock, and provides sales insights directly from the Meta inbox. The project is built using Next.js, React, and TypeScript for its core functionality, with Tailwind CSS providing a utility-first approach to styling.

## Key Components

*   **`app/`**: The primary directory for application pages, layouts, and components.
    *   **`app/layout.tsx`**: Defines the root HTML structure, global metadata, font imports, and initial dark mode handling for the entire application.
    *   **`app/page.tsx`**: The main landing page component, containing the core UI logic, feature lists, and FAQ sections.
    *   **`app/globals.css`**: Global stylesheets, integrating Tailwind CSS directives, custom CSS, and Google Font imports.
*   **`public/`**: Stores static assets such as images and favicons.
*   **`package.json`**: Manages project dependencies, defines development scripts (e.g., `dev`, `build`, `start`), and holds project metadata.
*   **`tailwind.config.ts`**: Configures Tailwind CSS, including custom themes, color palettes, font families, and dark mode settings.
*   **`next.config.mjs`**: The main configuration file for Next.js, allowing for custom build settings and environment variables.
*   **`tsconfig.json`**: TypeScript compiler configuration, ensuring type safety and proper compilation of the project.

## Development Workflow

To get started with the Elijeweb project, follow these steps:

1.  **Install Dependencies**: Navigate to the project root in your terminal and install the required packages:
    ```bash
    npm install
    # or
    yarn install
    # or
    pnpm install
    ```
2.  **Run Development Server**: Start the local development server:
    ```bash
    npm run dev
    # or
    yarn dev
    # or
    pnpm dev
    ```
3.  **Access Application**: Open your web browser and navigate to `http://localhost:3000` to view the application.
4.  **Development**: Begin editing the application by modifying files within the `app/` directory, particularly `app/page.tsx`. Changes will be hot-reloaded automatically.