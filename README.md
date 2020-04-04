# Learning yarn

Just one of the things I'm learning. https://github.com/hchiam/learning

`yarn` is like `npm`, but better (in my opinion).

If you're already using `npm`, there's [a very minimal migration and learning curve](https://yarnpkg.com/lang/en/docs/migrating-from-npm).

How `yarn` relates to `npm`: https://www.sitepoint.com/yarn-vs-npm/ (from 2016)

More info: https://yarnpkg.com

* Concurrency for faster installations.
* Exact installed versions recorded by default.
* Checksums before executing packages.
* Can work offline for packages you've installed before.
* Less verbose CLI install messages.
* A minor downside: older npm packages may not work or be installable.

Install `yarn`: https://yarnpkg.com/en/docs/install

## [Example commands](https://yarnpkg.com/lang/en/docs/migrating-from-npm/#toc-cli-commands-comparison)

### Setup deps

`yarn` or `yarn add` = `npm install`

([You can use `yarn import` to generate a `yarn.lock` file from an existing `package-lock.json`](https://yarnpkg.com/blog/2018/06/04/yarn-import-package-lock/))

### Install package as dep, dev dep, or globally

`yarn add <...>` = `npm install <...> --save`

`yarn add <...> --dev` = `npm install <...> --save-dev`

`yarn global add <...>` = `npm -g install <...>`

* _**WARNING**_: it's `global add` and _NOT_ `add global` (`yarn add global` installs a package literally named `global`).

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

`yarn upgrade --latest` = upgrade dependencies while ignoring the version range specified in `package.json` (could help with security updates)
