# Contributing
To setup and test, follow these steps:

```sh
git clone https://github.com/voorhoede/open-source-project.git
cd open-source-project
npm ci
npm test
```

## General Prerequisites
Node.js, [latest LTS is recommended](https://nodejs.org/en/about/releases/).

### Tips

## Publishing
1. Update `changelog.md` with relevant changes and stage with `git add`.
1. Run `npm version --force` with the appropiate version bump to include the changelog changes in the same commit.
1. This should automatically push the commit and new version tag to trigger publishing from CI.
