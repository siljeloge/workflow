# Workflow repo for the CA

This project demonstrates a frontend development workflow using modern tools such as linting, formatting, unit testing, and end-to-end testing.

## Tech Stack

* Vanilla JavaScript
* ESLint
* Prettier
* Husky + lint-staged
* Vitest (unit testing)
* Playwright (end-to-end testing)

## Setup

Clone the repository and install dependencies:

```bash
npm install
```

## Available Scripts

Run development (Tailwind CSS):

```bash
npm run dev
```

Run linting:

```bash
npm run lint
```

Format code:

```bash
npm run format
```

Run unit tests (Vitest):

```bash
npm run test
```

Run end-to-end tests (Playwright):

```bash
npm run test:e2e
```

## Environment Variables

Create a `.env` file based on `.env.example`.

Required variables:

* EMAIL
* PASSWORD

## Notes

* Login tests use mocked API responses due to unstable external API
* Navigation tests use mocked venue data to ensure reliability
* Pre-commit hooks ensure code is formatted and linted before commits

## Submission

This project is submitted as a pull request from the `workflow` branch into the default branch.

