# commitlint-config-git-workflow

<img src="https://github.com/markusfalk/git-workflow/blob/master/git-workflow-logo.svg" alt="" height="150" width="150">

A commitlint configuration to use with git workflow: https://github.com/markusfalk/git-workflow

## Prerequisites

Setup [commitlint](https://commitlint.js.org)

## Installation

Install the git-workflow rules via npm:

```bash
npm i commitlint-config-git-workflow --save-dev
```

Extend your rules with the new rules:

```json
{
  "extends": [
    "git-workflow"
  ]
}
```
