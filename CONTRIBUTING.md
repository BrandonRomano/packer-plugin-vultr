# Contributing to `packer-builder-vultr`

We would love to get your feedback, thoughts, and overall improvements to `packer-builder-vultr`! 

## Overview

- All Code should run through `go fmt`

## Getting started

Packer-builder-vultr supports `go modules` so you can pull down the repo outside of your `$GOPATH`.

You can also run:
`go get -u github.com/vultr/packer-builder-vultr`

## Versioning 

Packer-builder-vultr follows [SemVer](http://semver.org/) for versioning. New functionality will result in a increment to the minor version. While, 
bug fixes will result in a increment to the patch version. 

## Releases
Releases of new versions are done as their independent pull requests - They will also be done by the maintainers.

To release a new version of `packer-builder-vultr` we must do the following.

- Make the appropriate updates to `CHANGELOG.md`. This should include the 
    - Version, 
    - List of fix/features with accompanying pull request ID
    - Description of each fix/feature
    
```
## v0.0.1 (2019-06-12)

### Fixes
* Fixed random bug #12
```
- Submit a pull request with the following changes
- Once the pull request is merged in - create a new tag and publish.
