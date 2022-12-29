# Turinlabs frontend Theme

**A project build with CSS to style Turinlabs web applications**

## Getting Started

To install the Turinlabs Theme you'll need a Linux, Windows or MacOSX computer with a bash/zshell terminal, Node JS and NPM installed.

### Prerequisites

Please, make sure you have:

- Node JS v.16 or higher
- NPM v.8 or higher

### Installing via CLI

- Open a terminal and execute:

```bash
npm install @tutellus/turinlabs-theme
```

### Start the development environment

In order to see how the changes in these token values are affecting the UI where they are being implemented you can link this package:

- Run `npm run dev:link`
- Then, in your local repository (tutellus-components, ex.) run `npm run link:theme`

### Building for publish

- Open a terminal and execute:

```bash
npm run build
```

- Any `push` or `merge` to main branch will trigger a Github action.

### Bump version and Publish NPM package

After merging a pull request into the main branch you need to bump version based on changes:

- `npm run publish:major`
- `npm run publish:minor`
- `npm run publish:patch`
