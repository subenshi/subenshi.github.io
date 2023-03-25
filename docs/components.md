---
sidebar_position: 10
---

# Components

> Subenshi comes with a set of components that can be used to build your own solutions.

## CLI

This is where you want to get started with Subenshi. Is a terminal-based interactive CLI that allows you to create, manage and deploy your solutions.

```bash
mkdir my-project && cd "$_" # Create a new directory and navigate to it
npx subenshi-cli # start the CLI
```

| Repository |
|---|
| [subenshi/cli](https://github.com/subenshi/cli)  |

## Code templates

> Set of blueprints that you can use to build your own solutions.

To help you hit the ground running, Subenshi comes with a set of templates that
you can use to create your solutions. This templates covers a wide range of use
cases, from a NodeJS microservice, to Angular application and Admin panels.

| Repository |
|---|
| [subenshi/sources](https://github.com/subenshi/sources)  |

## Build templates

> Set of blueprints that you can use to deploy your own solutions.

Apart from code templates, Subenshi helps you apply a build templates to your
solutions. This templates are used to deploy your solutions to the different
cloud providers.

Think of it as a series of configuration files (like `Dockerfile`,
`docker-compose.yml`, `k8s.yaml`, etc) that once chosen are applied to your
microservice's codebase.

| Repository |
|---|
| [subenshi/build_templates](https://github.com/subenshi/build_templates)  |