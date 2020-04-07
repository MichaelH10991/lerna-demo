# lerna-demo

[![lerna](https://img.shields.io/badge/maintained%20with-lerna-cc00ff.svg)](https://lerna.js.org/)

## Useful Links

---

- [lerna website](https://lerna.js.org/)

- [lerna github](https://github.com/lerna/lerna)

## Commands

---

Lerna commands are executed from the root package.json.

run `npx lerna --help` for list of learna commands.

### To create a new package

`npm run create <package_name>`

### To run tests

`npm run test`

### Update a package

`npm run new-version`

- This will bump the version number of the package after you have made a commit

### [Add Module](https://github.com/lerna/lerna/tree/master/commands/add#readme)

`npm run add express@4.17.1 --scope=@lerna-demo/api`

`npm run add @babel/core --scope=@lerna-demo/frontend --dev`
