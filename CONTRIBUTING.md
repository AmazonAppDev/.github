# Contributing Guidelines

Thank you for your interest in contributing to our project. Whether it's a bug report, new feature, correction, or additional
documentation, we greatly value feedback and contributions from our community.

Please read through this document before submitting any issues or pull requests to ensure we have all the necessary
information to effectively respond to your bug report or contribution.

## Security issue notifications

If you discover a potential security issue in this project we ask that you notify AWS/Amazon Security via our [vulnerability reporting page](http://aws.amazon.com/security/vulnerability-reporting/). Please do **not** create a public GitHub issue.

## Submitting a PR

1. Fork the public AmazonAppDev repo to your GitHub account
2. We recommend creating a new branch in your fork to keep track of your changes e.g. `left-hand-navigation-drawer`
3. Make your changes, test, commit, and push to your fork
4. Create a pull request from your branch to the original repo. After approval, the original repo maintainer shall merge your changes
5. Remember to update your fork's main branch

```
git checkout main
git pull upstream main
git push origin main
```

## (If you have commit access) Making bug fixes

1. Create an issue in the repo describing the bug
2. Create a fix branch locally from the main repo:

```
git checkout -b fix/issue-number-description
```

1. Make changes and once finished commit to your branch
2. Create a pull request linking to the issue
3. After approval, squash merge the fix
4. Delete the fix branch

## Licensing

See the LICENSE file for our project's licensing. We will ask you to confirm the licensing of your contribution.
