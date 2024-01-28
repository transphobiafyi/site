# Contributing to transphobia.fyi

This is an open-source project and we welcome contributions from anyone on either the documentation or the code. 
Successful contributions must follow the contribution guidelines outlined here.

Once accepted (i.e. merged to `main`), the contribution will be built and deployed to production automatically.

## Git

This project uses the `git` version control system hosted on Github. If you are uncomfortable or unable to use git on
your computer, the files can be edited through the Github UI. Note that commit messages still need to follow the 
[Conventional Commits](#conventional-commits) format specified below.

## Issues

### Proposed

All new issues will be given the `proposed` label (`triage` for bugs) until a maintainer has a chance to review it and 
decide whether to accept it, reject it, or ask for changes.

### Accepted

Issues that are ready to receive contributions will have the `accepted` label. Pull requests for an issue will be
automatically rejected if the issue does not have this label.

## Conventional Commits

This project enforces the [conventional commit](https://www.conventionalcommits.org/en/v1.0.0/) standard. The issue must be stated in the footer of the commit in
the format `Issue: #<issue number>`.

### Example of a Documentation Commit Message

```
docs: elaborate on index.md

Add a section describing the purpose of this site.

Issue: #123
```

If editing through the Github UI, the above commit message would be mapped to the first line in the "Commit message"
field, and the rest of the body in the "Extended description" field.

### Example of a Development Commit Message

```
feat: add tag functionality

Add the capability to give posts a searchable tag.

Issue: #234
```

## Atomic Commits

Unless it isn't reasonable, any incoming pull request should have its commits squashed into a single (atomic)
commit. If your pull request has more than one commit, you should be able to provide a good reason why this is
preferred in your case.

All pull requests may only be merged by a rebase - merge commits will not be accepted.

## More Specific Documentation

### Contributors

See [CONTRIBUTING-content.md](./CONTRIBUTING-content.md)

### Developers

See [CONTRIBUTING-development.md](./CONTRIBUTING-development.md)
