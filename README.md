# event-me

All the events you never knew you needed to attend!


## Overview

This is a simple full-stack web project for educational purposes, to demonstrate the functionality and value of moving from JS to TS gradually.

It is part of Anjana's course [TypeScript First Steps](https://anjana.dev/typescript-first-steps) on [FrontendMasters](https://frontendmasters.com/teachers/anjana-vakil/).

## Installation

> **Node version:** to ensure compatibility with the project's dependencies, use **Node 20–24** (LTS). You can install it from [nodejs.org](https://nodejs.org/en/download).

```
cd backend
npm i 
cd ../frontend
npm i
```

## Running in development

Run the backend and frontend in separate terminals.

1) Run the backend API

Install backend dependencies and launch the dev server:

```
cd backend
npm i
npm run dev
```

The API will be available at `http://localhost:3000/api`.

Leave the backend running in this terminal.

3) Run the frontend client

In a _new_ terminal, install frontend dependencies and launch the dev server:


```
cd frontend
npm i
npm run dev
```

Open the app at `http://localhost:5173`.

Leave the frontend running in this terminal.


## Branches

The [`main`](https://github.com/vakila/event-me/tree/solution) branch contains the starting point for the course exercises, which involve migrating from JS to TS and fixing the app's (intentional) bugs in the process.

The [`solution`](https://github.com/vakila/event-me/tree/solution) branch contains a reference solution for the workshop exercises. But there is more than one way to type a script, so your solution might differ!