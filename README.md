# Manual Monorepo

# Steps to reproduce issue
1. Run `yarn` at root level to install dependencies.
2. Change directory to backend `cd packages/backend` and run `yarn build` and the `yarn dev`.
3. Now you will see the error (SyntaxError: Unexpected token 'export') which I want to get rid of...