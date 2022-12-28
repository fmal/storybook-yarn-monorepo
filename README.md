# storybook-yarn-monorepo

Goal of this repo is to demonstrate a weird quirk when using sb@7 with Yarn. In the current state the production build works fine, but if you add `manager.js` in `storybook/.storybook` and run the build again paths in sb-addons imports in `storybook/dist/index.html` are messed.
