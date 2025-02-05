## My reflections

1. The styled wrapper returned is already a component, so no need to put it into another component function.

2. RSC's main purpose is optimisation. The actual KB it saves might not be huge, depending on app size and design.

## Next 13 + styled-components

This repo is meant to be used as part of an exercise in [The Joy of React](https://www.joyofreact.com/).

## Running a development server

First, install the dependencies:

```bash
$ npm install
```

Then, start a local development server:

```bash
$ npm run dev
```

**Note:** Unlike create-react-app, we need to run the `dev` command, not `start`. The `start` command is used to run a _production_ server; we'll learn more about that later in the course.
