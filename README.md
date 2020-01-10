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

`yarn` or `yarn install` = `npm install`

`yarn add <...>` = `npm install <...> --save`

`yarn add <...> --dev` = `npm install <...> --save-dev`

`yarn global add <...>` = `npm -g install <...>`

`yarn remove <...>` = `npm uninstall <...> --save`

`yarn upgrade <...>` = `npm update <...> --save`

`yarn why` = dependency graph and helps you see if you explicitly added a package

`yarn licenses` (no `npm` equivalent)
