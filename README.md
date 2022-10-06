# deweb

This repository accompanies a post on my blog - [lifelongstudent.io](https://nir.galons.io/blog/2020/releasing-software-is-hard/), about automate GitHub releases by [Semantic Versioning - SemVer](https://semver.org) specification.

To achieve it we're using:
  1. [commitizen](https://github.com/commitizen/cz-cli) with a [Conventional Commits](https://www.conventionalcommits.org) configuration.
  2. [semantic-release](https://github.com/semantic-release/semantic-release) to determining the next version number, generating the release notes, and publishing the package.
  3. And GitHub actions to do it all automatically and run on every `milestone` `closed` event.
