<!--
This readme is based on a template for a new npm-package. See more here: https://github.com/Qualifyze/npm-package-template
-->
@qualifyze/npm-package-template
===============================

## _What_ it does?
<!-- Describe in very simple terms what this package does. Keep it factual -->

<!-- Delete this standard template description example here -->
This NPM package is a template that is used for hosting an NPM package on a dedicated git-repository.

While this package may also be deployed to an NPM repository, it should not be used in any project. It's sole purpose is
to initialize a new repository with a blueprint for an NPM package.

## _Why_ is it needed?

<!-- Describe in very simple terms of why this package is valuable. Refer to potential alternatives, if applicable and list the advantages and disadvantages -->

<!-- Delete this standard template description example here -->

- To reduce the overhead in initializing a new NPM package on its own repository.
- To provide a company-wide standard on how an NPM-Package is to be structured.

In comparison to [push-templates](https://github.com/Qualifyze/dev-infrastructure/pull/25), this classic repository
template allows you to make deviations to the standard easier.

## _How_ it is to be used?

<!-- Describe, with example snippets how this package can be used to deliver the aforementioned values -->

### Getting started

Install the package:

```bash
npm install @qualifyze/npm-package-template
```

Import it:

```typescript
import * as npmPackageTemplate from "@qualifyze/npm-package-template"
```


### Clone and Build

When developing, clone this repository locally and run build:
```bash
git clone git@github.com:Qualifyze/npm-package-template.git
npm run build
```

### Contributing Code

This package uses [husky](https://www.npmjs.com/package/husky) for some handy git pre-commit hooks.

To skip verification by husky, use `git commit --no-verify`.

For further issues while committing code (especially if your are using [nvm](https://github.com/nvm-sh/nvm#readme))
see [the husky troubleshooting section](https://typicode.github.io/husky/#/?id=troubleshoot).


### Publish a new Version

Update the version number in the [package.json](package.json) and get it merged into the `main` branch. The package will
be automatically deployed to the NPM repository.

<!-- Delete this todo list when done -->
### Todo list
- [ ] Create a new repository, using this repository as a template.
- [ ] Search for `npm-package-template` and replace it with whatever name you gave to your package. When replacing, skip the link on top of this Readme.
- [ ] Update package description in [package.json](package.json).
- [ ] When all the points above are done, update this readme, following the instructions in the comment.
