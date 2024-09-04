# @dotenvx/dotenvx Issue 371
Minimal reproduction for [issue 371](https://github.com/dotenvx/dotenvx/issues/371) in a pnpm + nx monorepo. In the issue, I am trying to run a nuxt project, but the problem exists here as well.

## Dependencies
For this example you will need [pnpm](https://pnpm.io/) version 9.9.0

## Installation
To install all other dependencies run `pnpm i`

## Running
To start this example, run `pnpm -- nx start @issue-371/app` from the monorepo root directory.

Alternatively, I've also added a `start:alt` script that will use `pnpx` to run `dotenvx`. This version works and can be run with `pnpm -- nx start:alt @issue-371/app`