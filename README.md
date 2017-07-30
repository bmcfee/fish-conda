# fish-conda

[![Build Status][travis-badge]][travis-link]
[![Slack Room][slack-badge]][slack-link]

Managing conda environments

## Install

With [fisherman]

```
fisher bmcfee/fish-conda
```

## Usage
List available environments:
```fish
condalist
```

Activate an environment:
```fish
condactivate ENV_NAME
```
or
```fish
ca ENV_NAME
```

Deactivate an environment:
```fish
deactivate
```
or
```fish
cda
```

[travis-link]: https://travis-ci.org/bmcfee/fish-conda
[travis-badge]: https://img.shields.io/travis/bmcfee/fish-conda.svg
[slack-link]: https://fisherman-wharf.herokuapp.com
[slack-badge]: https://fisherman-wharf.herokuapp.com/badge.svg
[fisherman]: https://github.com/fisherman/fisherman
