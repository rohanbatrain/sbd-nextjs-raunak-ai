# sbd-nextjs-raunak-ai

**Raunak AI** is the advanced AI interface for the Second Brain Database, providing a seamless chat experience with RAG capabilities, tool usage, and document management.

## Features

-   **Chat Interface**: Conversational UI for interacting with AI agents.
-   **RAG Support**: Retrieval-Augmented Generation for context-aware answers.
-   **Tool Integration**: Support for MCP (Model Context Protocol) tools.
-   **Document Management**: Upload and manage documents for RAG.
-   **Settings**: Configure AI models and preferences.

## Tech Stack

-   **Framework**: [Next.js 16](https://nextjs.org/)
-   **Language**: TypeScript
-   **Styling**: [Tailwind CSS 4](https://tailwindcss.com/)
-   **State Management**: [Zustand](https://github.com/pmndrs/zustand)
-   **Markdown**: React Markdown
-   **UI Components**: Radix UI, Lucide React
-   **Animations**: Framer Motion

## Prerequisites

-   Node.js 20+
-   pnpm (recommended) or npm/yarn

## Getting Started

1.  **Install dependencies**:
    ```bash
    pnpm install
    ```

2.  **Set up environment variables**:
    Copy `.env.example` to `.env.local` and configure the necessary variables.
    ```bash
    cp .env.example .env.local
    ```

3.  **Run the development server**:
    ```bash
    pnpm dev
    ```
    Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Scripts

-   `pnpm dev`: Run the development server.
-   `pnpm build`: Build the application for production.
-   `pnpm start`: Start the production server.
-   `pnpm lint`: Run ESLint.
-   `pnpm test`: Run unit tests with Jest.
-   `pnpm test:e2e`: Run end-to-end tests with Playwright.
-   `pnpm storybook`: Start Storybook for component development.

## Project Structure

-   `app/`: Next.js App Router pages and layouts.
-   `components/`: Reusable UI components.
-   `lib/`: Utility functions and shared logic.
-   `store/`: Zustand state management stores.
-   `hooks/`: Custom React hooks.

## License

Private
