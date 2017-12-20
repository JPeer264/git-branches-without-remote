# git-branch-info WIP

Get branch information about the current repo

## Installation

```sh
$ npm i git-branch-info --save
```
or
```sh
$ yarn add git-branch-info
```

## Usage

```js
const gitBranchInfo = require('current-git-branch');

gitBranchInfo(); // object with information of process.cwd() - empty if no repo
gitBranchInfo('any/git/repo'); // object with information of the directory 'any/git/repo' - empty if no repo
```

## LICENSE

MIT © [Jan Peer Stöcklmair](https://www.jpeer.at)
