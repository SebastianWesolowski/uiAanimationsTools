# init-s-template

This project is a template for quickly creating a repository based on [s-template](https://github.com/SebastianWesolowski/s-template).

## Quick Start

**Note:** Before use, set the appropriate template in `remoteRepository` in `package.json` or provide it as a parameter.

```bash
yarn install
yarn init
yarn build
```

## Instructions

### Setup

1. Set the template `remoteRepository` in `package.json` or provide it as a parameter in commands
2. Install dependencies:

```bash
yarn install
```

### Usage

**Initialization:**

```bash
yarn init
# or
s-init --remoteRepository='https://github.com/SebastianWesolowski/s-template/tree/main/templates/node'
```

**Build:**

```bash
yarn build
# or
s-build --remoteRepository='https://github.com/SebastianWesolowski/s-template/tree/main/templates/node'
```

**Update:**

```bash
yarn update
# or
s-update --remoteRepository='https://github.com/SebastianWesolowski/s-template/tree/main/templates/node'
```

**Parameter `--remoteRepository` (required):** `https://github.com/SebastianWesolowski/s-template/tree/main/templates/[TEMPLATE_NAME]` (or `dev` instead of `main`). Can be set in `package.json` or provided directly in the command.

## s-update-manager

Tool for managing templates from the s-template repository. More information: [s-update-manager](https://github.com/SebastianWesolowski/s-update-manager)

## Available s-template templates

Full documentation: [https://github.com/SebastianWesolowski/s-template/tree/dev/templates](https://github.com/SebastianWesolowski/s-template/tree/dev/templates)

- **[NextJs/NextJs15-basic](https://github.com/SebastianWesolowski/s-template/tree/dev/templates/NextJs/NextJs15-basic)**
- **[NextJs/NextJs15](https://github.com/SebastianWesolowski/s-template/tree/dev/templates/NextJs/NextJs15)**
- **[mockTemplateWithImageWithConfig/templateCatalog](https://github.com/SebastianWesolowski/s-template/tree/dev/templates/mockTemplateWithImageWithConfig/templateCatalog)**
- **[mocks](https://github.com/SebastianWesolowski/s-template/tree/dev/templates/mocks)**
- **[nestjs](https://github.com/SebastianWesolowski/s-template/tree/dev/templates/nestjs)**
- **[nestjsModule](https://github.com/SebastianWesolowski/s-template/tree/dev/templates/nestjsModule)**
- **[node](https://github.com/SebastianWesolowski/s-template/tree/dev/templates/node)**
- **[startetNpmPackage/node](https://github.com/SebastianWesolowski/s-template/tree/dev/templates/startetNpmPackage/node)**
