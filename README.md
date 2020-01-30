# jq zsh plugin

Interactively build [jq](https://stedolan.github.io/jq/) expressions.

This zsh plugin gives you jq superpowers!

## Table of contents

- [Usage](#usage)
- [Key bindings](#key-bindings)
- [Demos](#demos)
  - [Interactive jq query construction](#interactive-jq-query-construction)
  - [Insert jq query in the middle of a pipeline](#insert-jq-query-in-the-middle-of-a-pipeline)

## Usage

- type out a command that you expect to produce json on it's standard output
- press alt + j and interactively write a jq expression
- press enter, and the jq expression is appended to your initial command!

## Key bindings

To bring up the JQ query builder, press `alt + j`.

During interactive querying, the following shortcuts can be used:

| Shortcut | Effect |
| ------ | -------- |
| `shift + up` | Scroll up |
| `shift + down` | Scroll down |
| `alt + up` | Scroll up full page |
| `alt + down` | Scroll down full page |

## Demos

### Interactive jq query construction

[![asciicast](https://asciinema.org/a/296765.svg)](https://asciinema.org/a/296765)

### Insert jq query in the middle of a pipeline

[![asciicast](https://asciinema.org/a/296767.svg)](https://asciinema.org/a/296767)
