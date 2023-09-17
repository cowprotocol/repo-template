# CoW Protocol Github Repository Template

This repository contains the CoW Protocol Github Repository Template, providing a base, non-language specific
repository structure and documentation / general errata.

## Defaults

The following defaults are set for all repositories created from this template:

- [x] `main` branch
- [x] `develop` branch
- [x] `cla-signatures` branch (for CLA workflow signatures)
- [x] Licenses
    - [x] GPL v3.0 license
    - [x] MIT license
    - [x] Apache 2.0 license
- [x] Issue templates
  - [x] Bug report
  - [x] Feature request
  - [x] Improvement request
  - [x] Research-related issue
- [x] Pull request template
- [x] Contributing guidelines
- [x] [Contributor Covenant Code of Conduct](https://www.contributor-covenant.org/version/1/4/code-of-conduct/)
- [x] Security Policy for smart contract repositories
- [x] Integration with project board

## Using the Template

If configuring a language-specific repository (for a feature implementation, or template), it is recommended to fork
this repository, and adjust the contents to suit the needs of the new repository.

### All repositories

- [ ] Search for all instances of `repo-template` present in repository documentation and replace with the new repository name.
- [ ] Update the `README.md` file to reflect the new repository's purpose.
- [ ] Rename the applicable license to `LICENSE` and remove non-applicable licenses.
- [ ] Remove the `SECURITY.md` file if the repository is not a security-sensitive repository.

### Internal-facing repositories

- [ ]  Remove the `CODE_OF_CONDUCT.md` file if the repository is not a community-facing repository.
- [ ]  Optionally remove the CLA workflow if the repository.

### Workflows

#### Add to Project

If the repository should be tracked as part of the `CoW` project, leave the `Add to Project` workflow as-is. If the
repository should not be tracked as part of the `CoW` project, remove the workflow.

#### CLA

The CLA workflow has already been included and configured as part of this template. Additional details if required
for the CLA workflow can be found in the [CLA repository](https://github.com/cowprotocol/cla).

## Developers

If updating the repository template:

- [ ] Update the `README.md` file to reflect any new features or changes to the template.
- [ ] Make use of `repo-template` as the repository name for the template.
