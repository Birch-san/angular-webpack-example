# First-time setup

1. Get [yarn](https://yarnpkg.com/)

2. Install all dependencies

```bash
yarn install
```

# Local development

Start the Webpack service:

```bash
yarn start
```

Watches live your changes to source, and compiles. Serves website via in-memory server on port 8080

# Production release

```bash
yarn build
```

Outputs something somewhere (probably `dist/`).