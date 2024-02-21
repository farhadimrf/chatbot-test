# React Chat

React Chat is a simple project for testing and integrating the "react-chatbot-task" component into your React applications. This project provides a basic chat application that uses the chatbot component for interactive communication.

## Features

-  Integration of the "react-chatbot-task" component.
-  Basic chat UI for user interaction.
-  Easy-to-follow project structure for testing and extension.

## Getting Started

To get started with the React Chat project, follow these steps:

```bash
git clone https://github.com/farhadimrf/chatbot-test.git

cd chatbot-test

npm install
```

then run with

```bash
npm run dev

# or

yarn dev
```

## Ducument

in this test chatbot test
first install package from npm

```basg
npm install react-chatbot-task
```

then install tailwind

```basg
npm install tailwind
```

after installation add tailwind content reader to `tailwind.config.ts`

```bash
import type { Config } from "tailwindcss";

const config: Config = {
   content: [
   ///,
      "./node_modules/react-chatbot-task/**/*.{js,ts,jsx,tsx,mdx}",
   ],
   plugins: [],
};
export default config;
```

then run app

```bash
npm run dev

# or

yarn dev
```
