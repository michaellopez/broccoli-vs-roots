# ssg-comparison

A repo for testing tools as static site generators (SSG).

It contains a sample site that demonstrates how some SSG are used.

It is the same sample site built with each tool. The output should be identical.

It is created for [our](http://www.weahead.se) use. But anyone who is interested is welcome to explore.

If you find anything that can be done better please file an issue or even better a PR. Thank you.


## Goals

Each SSG demonstrated in this repo must support/accomplish the following:

- Run on NodeJS.
- Watch for file changes.
- Live Reload.
- Linting JS on file changes.
- Linting CSS on file changes.
- Jade and/or Handlebars **with** partials and helpers in external files.
- Compiling/building anything on file changes, including partials and helpers.
- JSON as data for templates.
- Flexible file structure. The output needs to be identical to all other SSG.


## Requirements

- NodeJS & NPM (`brew install nodejs` or alternative)
- Broccoli Taco (`npm install -g broccoli-taco)
- Roots V3 (`npm install roots@pre -g`)


## Setup

| Broccoli Taco | Roots         |
|---------------|---------------|
| `npm install` | `npm install` |


## Develop

| Broccoli Taco         | Roots         |
|-----------------------|---------------|
| `broccoli-taco serve` | `roots watch` |


## Build

| Broccoli Taco         | Roots           |
|-----------------------|-----------------|
| `broccoli-taco build` | `roots compile` |
