## Installation

Clone the project

```bash
  git clone https://github.com/NEET-Vs/SpoilerAlert.git
```

Go to the project directory

```bash
  cd SpoilerAlert
```

Install dependencies

```bash
  pnpm i --frozen-lockfile
```

Build the project

```bash
  pnpm run build
```

Spin the server

```bash
  pnpm run preview
```

## Running Tests

To run tests, run the following command.

For specific `pnpm run test / cy / test:cy:e2e` make sure the server already spin before do a test.

Do a complete test; unit testing & e2e

```bash
  pnpm run test
```

Run Vitest

```bash
  pnpm run test:vitest
```

Test Vitest with coverage mode

```bash
  pnpm run test:vitest:coverage
```

Run Cypress

```bash
  pnpm run test:cy
```

Test e2e with Cypress

```bash
  pnpm run test:cy:e2e
```

CI test command

```bash
pnpm run test:ci
```

Husky test command

```bash
pnpm run test:husky
```

## DOC

For Tailwind Icon

- [icones](https://icones.js.org/)
- [iconify](https://icon-sets.iconify.design/)

For Styles

- [Nuxt Tailwind Config](https://tailwindcss.nuxtjs.org/getting-started/setup)
- [Tailwind](https://tailwindcss.com/docs)
- [Nuxt Chakra-UI](https://next.vue.chakra-ui.com/components/flex)
