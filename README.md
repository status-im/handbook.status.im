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

The `master` branch is built by [our own Jenkins](https://ci.status.im/job/website/job/handbook.status.im/).
