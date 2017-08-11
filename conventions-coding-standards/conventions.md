# Conventions in OpenMined

## Naming Conventions
### Files & Folders
All conventions below apply by default. This means that if there is no existing language-specific convention that contradicts it (e.g. Python snake case)
* All names should be in lowercase and joined with dashes (e.g. `this-is-a-name`).

## Branch Conventions
* `master` is `protected`, contributors should open a Pull Request against `master`.
* Branch names have the following tags:
  * `bug` - fixing bugs in existing code
  * `chore` - updating tooling or cleanup
  * `docs` - adding/updating docs
  * `feature` - adding new features, work on a feature
  * `tool` - adding modules/tools, development candy
* Branch names should follow the following structure:
`<tag>/<feature-name>--<brief-description-of-changes>`
  * Example: `feature/he--key-rotation-add` or `chore/webpack--update-to-2`


## Commit Conventions
* One commit per logical change
* Be descriptive (no `Update README.md`)

## Pull Request Conventions
* Tag the issue your PR addreses using a GitHub keyword, e.g. `Closes #1`
