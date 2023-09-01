This is a [Next.js](https://nextjs.org/) project template.

## This application use the following packages

- [Next.js](https://nextjs.org/)
- [TypeScript](https://www.typescriptlang.org/)
- [Tailwind CSS](https://tailwindcss.com/)
- [shadcn/ui](https://ui.shadcn.com/)

## Getting Started

To use this template:

```bash
npx create-next-app --example "https://github.com/5thComrade/nextjs-starter-template" <YOUR_APP_NAME>
```

To spin up the dev server:

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

## Important - Committing Code

**This application uses [eslint](https://eslint.org/) and [prettier](https://prettier.io/) for linting and code formatting.
There is a pre-commit hook that runs before every commit (achieved using [husky](https://typicode.github.io/husky/)). This pre-commit hook will identify any linting or formatting issues in the code and may abort your commit if it encounters any such issues. This is a preventive step taken to ensure the code quality is supreme.**

**Follow the below steps to fix code quality issues**

1. Run the below npm script to fix **prettier** related issues

```bash
npm run format:write
```

2. For **eslint** related issues, I highly recommend to visit the **Problems** tab on the VSCode integrated terminal or run the below command. Identify the issue and directly fix it in your code.

```bash
npm run eslint
```
