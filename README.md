# Template for creating a new Node.JS package

This is a skeleton to get started with creating a new package to use in other projects

## Getting Started

* Fork/clone this repo giving it a meaningful name.
* Checkout the new repo
* Edit the package json and change the `name`, `description` and `repository` to match the new library.
    - Commit

## Developing

Write your code in the `src` folder, organizing as it fits best.

## Distributing

* Build the code `npm run build`
* Run `npm version patch|minor|major`. This will increment the version in `package.json` and will crete a tag with the name equal the version.
* Commit and push your changes, including the tags `git push origin --tags`

## Usage

In your project run `npm i git+ssh://git@github.com:workspace/node-package-name.git.git#semver:^1.0.0`
Include it in your files with `import 'node-package-name';` or `var someVar = require('node-package-name')`

## Versioning

Use [SemVer](http://semver.org/) for versioning.
