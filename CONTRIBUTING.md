# Contributing to HumEnv
We want to make contributing to this project as easy and transparent as possible.

## Installing the library
Install the library as suggested in the README.

## Formatting your code
**Type annotation**

Humenv is not strongly-typed, i.e. we do not enforce type hints, neither do we check that the ones that are present are valid. We rely on type hints purely for documentary purposes. Although this might change in the future, there is currently no need for this to be enforced at the moment.

**Formatting**

Before your PR is ready, you'll probably want your code to be checked. This can be done easily by installing
```
ruff format
```
and 
```
ruff check
```
from within the HumEnv cloned directory.

## Pull Requests
We actively welcome your pull requests.

1. Fork the repo and create your branch from `main`.
2. If you've added code that should be tested, add tests.
3. If you've changed APIs, update the documentation.
4. Ruff format and check the code.
5. Ensure the test suite pass.
6. If you haven't already, complete the Contributor License Agreement ("CLA").

When submitting a PR, we encourage you to link it to the related issue (if any) and add some tags to it.

## Contributor License Agreement ("CLA")
In order to accept your pull request, we need you to submit a CLA. You only need
to do this once to work on any of Facebook's open source projects.

Complete your CLA here: <https://code.facebook.com/cla>

## Issues
We use GitHub issues to track public bugs. Please ensure your description is
clear and has sufficient instructions to be able to reproduce the issue.

Facebook has a [bounty program](https://www.facebook.com/whitehat/) for the safe
disclosure of security bugs. In those cases, please go through the process
outlined on that page and do not file a public issue.

## License
By contributing to HumEnv, you agree that your contributions will be licensed
under the LICENSE file in the root directory of this source tree.
