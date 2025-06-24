# TaleWeaver

## Project Overview

TaleWeaver is a web application designed to help writers outline and plan their novels. The project uses **React**, **TypeScript**, and **Vite** with **Tailwind CSS** for styling. It is intended as a foundation for experimenting with OpenAI powered features for story generation and planning assistance.

## Setup Instructions

1. Install [Node.js](https://nodejs.org/) version 18 or higher.
2. Clone this repository and install the dependencies:
   ```bash
   npm install
   ```
3. Provide an OpenAI API key as an environment variable named `OPENAI_API_KEY` when you start the app. See the [OpenAI documentation](https://platform.openai.com/docs/api-reference/authentication) for details.
4. Start the development server:
   ```bash
   npm run dev
   ```

## Basic Usage

Running `npm run dev` launches Vite on <http://localhost:5173>. The default page is minimal, so you can begin adding components in `src/` to build out your story planning interface.

To create a production build, run:
```bash
npm run build
```
Preview the build locally with:
```bash
npm run preview
```

## Dependencies

The project relies on the following main packages:

- [React](https://react.dev/)
- [Vite](https://vitejs.dev/)
- [TypeScript](https://www.typescriptlang.org/)
- [Tailwind CSS](https://tailwindcss.com/)
- [lucide-react](https://lucide.dev/)
- [ESLint](https://eslint.org/) (for linting)

Development commands are defined in `package.json`:

```bash
npm run dev       # Start a local dev server
npm run build     # Build for production
npm run preview   # Preview the build locally
npm run lint      # Run ESLint checks
```

## Environment Variables

Vite uses environment variables prefixed with `VITE_`. For details, see the [Vite environment guide](https://vitejs.dev/guide/env-and-mode.html). When integrating the OpenAI API you may place your API key in a `.env` file as `OPENAI_API_KEY` or export it in your shell.

## OpenAI Integration

This project is prepared for future integration with the OpenAI API. Consult the [OpenAI API documentation](https://platform.openai.com/docs) to learn how to generate API keys and interact with the endpoints.
