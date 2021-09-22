# Description

This repository is the source for https://handbook.status.im/.

It is built using [mdBook](https://rust-lang.github.io/mdBook/).

# Development

You will need to [install mdBook](https://github.com/rust-lang/mdBook#installation).

To start a server that also builds the page use:
```
mdbook serve
```
Will expose the built page under http://localhost:3000/.

# Continuous Integration

Two branches are built by [our Jenkins instance](https://ci.status.im/):

* `master` is deployed to https://handbook.status.im/ by [CI](https://ci.status.im/job/website/job/handbook.status.im/)
* `develop` is deployed to https://dev-handbook.status.im/ by [CI](https://ci.status.im/job/website/job/dev-handbook.status.im/)

PRs should be made for `develop` branch and `master` should be [rebased](https://git-scm.com/book/en/v2/Git-Branching-Rebasing) on `develop` once changes are verified.
