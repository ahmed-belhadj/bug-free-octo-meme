# app

## Installation

Install all the dependencies:
```zsh
yarn install
```

## Usage

After the installation is complete:
- Run `yarn dev` to start the development server on http://localhost:3000
- Visit http://localhost:3000 to view the application

`package.json` includes the following `scripts`:
```json
"scripts": {
  "dev": "next",
  "build": "next build && tsc --project tsconfig.server.json",
  "lint": "eslint . --ext .ts,.tsx"
}
```
These scripts refer to the different stages of developing the application:
- `dev` - starts Next.js in development mode
- `build` - builds the application for production usage
- `lint` - runs ESLint
