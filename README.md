This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

```bash
yarn create next-app reactsetup
```

## Steps

1. Add TypeScript

```bash
yarn add typescript @types/react @types/node -D

# A tsconfig.json and a next-env.d.ts are created for us.
yarn dev
```

2. Add ESLint

```bash
yarn add eslint -D

yarn eslint --init
```

3. Add Prettier

```bash
yarn add prettier eslint-plugin-prettier eslint-config-prettier -D
```

4. Add EditorConfig

Install the VSCode plugin `editorconfig.editorconfig` and generate and new file ny clicking with the right click on the Explorer.

5. Add Styled Components

```bash
yarn add styled-components
yarn add @types/styled-components -D
```

6. Import images

```bash
yarn add next-images
yarn add babel-plugin-inline-react-svg -D
```

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `pages/index.js`. The page auto-updates as you edit the file.
