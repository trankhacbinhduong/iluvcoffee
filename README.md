# Getting started

## `Introduction`

- Layer above NodeJS
- Abstract common Node.js frameworks (Express/Fastify)

### `Features`

- Scalable
- Testable
- Maintainable
- Loosely-coupled

### `Platform Agnosticism`

- REST API
- Microservice
- Web Sockets
- GraphQL

## `Setup Environment`

### `Install NodeJS`

```bash
node --version
```

### `Install Nest CLI`

```bash
npm i -g @nestjs/cli

# Check Nest version
nest --version

# Check Nest CLI
nest --help
```

## `Generate Nest Application`

```bash
nest new iluvcoffee
```

### `Start Nest Application`

```bash
cd iluvcoffee && npm run start
```

### `Nest Hello World`

```
localhost:3000
```

## `Nest Structure`

```
- src
  - app.controller.ts
  - app.controller.spec.ts
  - app.module.ts
  - app.service.ts
  - main.ts
- test
  - jest-e2e.json
- .env
- .eslintrc.js
- .gitignore
- .prettierrc
- nest-cli.json
- package.json
- README.md
- tsconfig.build.json
- tsconfig.json
```
