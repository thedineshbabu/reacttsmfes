# Webpack 5 Module Federation with React/Typescript

![Workflow](https://github.com/dwyl/repo-badges/blob/master/svg/build-passing.svg)
This project shows a container application loading remote components

Workflow:

- `app1` expose CounterAppOne component.
- `app2` expose CounterAppTwo header component.
- `host` import CounterAppOne and CounterAppTwo component.

## Running Demo

Run `yarn build` and `yarn start` to run Lerna commands. This will `Host`, `App1`, `App2` build and serve your apps on ports `3000`, `3001`, `3002` respectively.
