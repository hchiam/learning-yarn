# Learning yarn

Just one of the things I'm learning. https://github.com/hchiam/learning

Install `yarn`: https://yarnpkg.com/en/docs/install

Info on how `yarn` relates to `npm`: https://www.sitepoint.com/yarn-vs-npm/ (from 2016)

More info: https://yarnpkg.com

* Concurrency for faster installations.
* Exact installed versions recorded by default.
* Checksums before executing packages.
* Can work offline for packages you've installed before.

## Example commands

### Setup deps

`yarn` or `yarn install` = `npm install`

### Install package as dep, dev dep, or globally

`yarn add <...>` = `npm install <...> --save`

`yarn add <...> --dev` = `npm install <...> --save-dev`

`yarn global add <...>` = `npm -g install <...>`

### Uninstall package

`yarn remove <...>` = `npm uninstall <...> --save`

### Upgrade package version

`yarn upgrade <...>` = `npm update <...> --save`

### Common commands you might use/customize

`yarn run test` = `npm run test`

`yarn run build` = `npm run build`

`yarn run start` = `npm run start`

### Other stuff

`yarn why` = dependency graph and helps you see if you explicitly added a package

`yarn licenses` (no `npm` equivalent)
