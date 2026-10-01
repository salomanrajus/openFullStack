# OpenFullStack Course Practice

This repository contains notes and exercises for the OpenFullStack course. The course focuses on modern JavaScript, React single-page applications, and RESTful or GraphQL services built with Node.js. It also covers TypeScript, React Native, databases, debugging, continuous integration, containers, and runtime configuration.

Course work is organized by part and exercise. The exercises are intended to be completed alongside the course material and often build on earlier work.

## Repository layout

```text
.
├── part0/
│   └── README.md                 # Course overview and guidance
└── part1/
    └── excercise-1.1/            # First React and Vite exercise
        ├── package.json
        ├── index.html
        └── src/
            ├── App.jsx
            ├── App.css
            ├── index.css
            └── main.jsx
```

The exercise folder name is spelled `excercise-1.1` in the repository.

## Current exercise

`part1/excercise-1.1` is a React application built with Vite. It currently contains the Vite starter page, including a click counter, React and Vite links, and responsive styling. Use it as the starting point for the course exercise; future parts and exercises can be added in their own folders.

## Run the app

Install a supported version of [Node.js](https://nodejs.org/) and npm. The locked Vite version requires Node.js 20.19 or later in the 20.x line, or 22.12 or later.

From the repository root, run:

```sh
cd part1/excercise-1.1
npm ci
npm run dev
```

Vite prints the local URL in the terminal. Run the remaining project scripts from `part1/excercise-1.1` as well:

| Command | Purpose |
| --- | --- |
| `npm run dev` | Start the development server with hot module replacement. |
| `npm run build` | Create a production build in `dist/`. |
| `npm run preview` | Preview the production build locally. |
| `npm run lint` | Run ESLint on the project. |

Each exercise may have its own dependencies and scripts, so check its `package.json` before running commands.
