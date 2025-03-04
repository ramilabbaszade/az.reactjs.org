<h1 align="center">React Azerbaijani Documentation</h1>
<div align="center">

This repo contains the source code and documentation powering [az.reactjs.org](https://az.reactjs.org/).

🇦🇿 [Azerbaijani Version](https://github.com/reactjs/az.reactjs.org/blob/master/README.az.md) | 📖 [Glossary](https://github.com/reactjs/az.reactjs.org/blob/master/glossary.md) | 💅 [Style Guide](https://github.com/reactjs/az.reactjs.org/blob/master/style-guide.md) | ✅ [Progress: 100% Core, 50% Other](https://www.isreacttranslatedyet.com/)
</div>

## Getting started

### Prerequisites

1. Git
1. Node: any 8.x version starting with 8.4.0 or greater
1. Yarn: See [Yarn website for installation instructions](https://yarnpkg.com/lang/en/docs/install/)
1. A fork of the repo (for any contributions)
1. A clone of the [az.reactjs.org repo](https://github.com/reactjs/az.reactjs.org) on your local machine

### Installation

1. `cd az.reactjs.org` to go into the project root
1. `yarn` to install the website's npm dependencies

### Running locally

1. `yarn dev` to start the hot-reloading development server (powered by [Gatsby](https://www.gatsbyjs.org))
1. `open http://localhost:8000` to open the site in your favorite browser

## Contributing

### Guidelines

The documentation is divided into several sections with a different tone and purpose. If you plan to write more than a few sentences, you might find it helpful to get familiar with the [contributing guidelines](https://github.com/reactjs/az.reactjs.org/blob/master/CONTRIBUTING.md#guidelines-for-text) for the appropriate sections.

### Create a branch

1. `git checkout master` from any folder in your local `az.reactjs.org` repository
1. `git pull origin master` to ensure you have the latest main code
1. `git checkout -b the-name-of-my-branch` (replacing `the-name-of-my-branch` with a suitable name) to create a branch

### Make the change

1. Follow the "Running locally" instructions
1. Save the files and check in the browser
  1. Changes to React components in `src` will hot-reload
  1. Changes to markdown files in `content` will hot-reload
  1. If working with plugins, you may need to remove the `.cache` directory and restart the server

### Test the change

1. If possible, test any visual changes in all latest versions of common browsers, on both desktop and mobile.
1. Run `yarn check-all` from the project root. (This will run Prettier, ESLint, and Flow.)

### Push it

1. `git add -A && git commit -m "My message"` (replacing `My message` with a commit message, such as `Fix header logo on Android`) to stage and commit your changes
1. `git push my-fork-name the-name-of-my-branch`
1. Go to the [az.reactjs.org repo](https://github.com/reactjs/az.reactjs.org) and you should see recently pushed branches.
1. Follow GitHub's instructions.
1. If possible, include screenshots of visual changes. A Netlify build will also be automatically created once you make your PR so other people can see your change.

## Translation

If you are interested in translating `az.reactjs.org`, please see the current translation efforts at [isreacttranslatedyet.com](https://www.isreacttranslatedyet.com/).

If you would like to add a new term or change an existing one please change make you changes to [glossary.md](https://github.com/reactjs/az.reactjs.org/blob/master/glossary.md) file in the repository and make a PR. In this documentation, all the terms are consistent across the documentation; so, when making a PR, let us know the decision behind the change.

## Troubleshooting

- `yarn reset` to clear the local cache

## License

Content submitted to [az.reactjs.org](https://az.reactjs.org/) is CC-BY-4.0 licensed, as found in the [LICENSE-DOCS.md](https://github.com/open-source-explorer/reactjs.org/blob/master/LICENSE-DOCS.md) file.
