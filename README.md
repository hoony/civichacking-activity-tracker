Civic Hacking Activity Tracker
==============================
Tracker for activities of civic hacking community using Github API

## Requirements

  * [Node](http://nodejs.org/)
  * [NPM](http://npmjs.com/)

## Build
  1. **install dependencies**
  ```shell
  npm install
  ```

  1. **set GITHUB_SECRET_KEY to environment variable**
  ```shell
  export GITHUB_SECRET_KEY="GITHUB_SECRET_KEY"
  ```
  if you use [fishshell](http://fishshell.com/)
  ```shell
  set -x GITHUB_SECRET_KEY "GITHUB_SECRET_KEY"
  ```

  1. **build**
  ```bash
  node server.js
  ```


## Source
The following libraries are directly included as source code:

  * [Octonode](https://github.com/pksunkara/octonode)
  * [Underscore](http://underscorejs.org/)

## License
MIT License