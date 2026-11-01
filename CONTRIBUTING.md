# Contributing to BikeNetKit

First off, thank you for considering contributing to BikeNetKit! ❤️ It's 
people like you that make BikeNetKit such a great toolkit.

## Table of contents

- [Code of Conduct](#code-of-conduct)
- [How Can I Contribute?](#how-can-i-contribute)
- [AI usage policy](#ai-usage-policy)
- [Pull Request Process](#pull-request-process)

## Code of conduct

This project and everyone participating in it is governed by our 
[Code of Conduct](CODE_OF_CONDUCT.md). By participating, you are 
expected to uphold this code.

## How can I contribute?

All types of contributions are encouraged and valued. See below for different ways to help and details about how this project handles them. Please make sure to read the relevant section before making your contribution. It will make it a lot easier for us maintainers and smooth out the experience for all involved. The community looks forward to your contributions. 🎉

> And if you like the project, but just don't have time to contribute, that's fine. There are other easy ways to support the project and show your appreciation, which we would also be very happy about:  
> - Star the project  
> - Post on social media about it. We suggest the hashtag: #BikeNetKit  
> - Refer this project in your project's `README`  
> - Mention the project at local meetups and tell your friends/colleagues

### 🐛 Reporting bugs

Before creating bug reports, please check existing issues to avoid 
duplicates. When you create a bug report, include as many details as 
possible using our [bug report template](https://github.com/BikeNetKit/.github/blob/main/.github/ISSUE_TEMPLATE/bug_report.md) that automatically pops up when you press `New issue`.

### 📝 Improving documentation

Documentation improvements are always welcome, including:  
- Fixing typos  
- Adding examples  
- Clarifying confusing sections

Please use our 
[documentation template](https://github.com/BikeNetKit/.github/blob/main/.github/ISSUE_TEMPLATE/documentation) that automatically pops up when you press `New issue`.

### 💡 Suggesting features

Feature requests are very welcome, also if you are not a coder! Let us know what is missing/improvable. Please use our 
[feature request template](https://github.com/BikeNetKit/.github/blob/main/.github/ISSUE_TEMPLATE/feature_request.md) that automatically pops up when you press `New issue`.

### 🔧 Implementing features/code
Look for issues labeled `good first issue` or `help wanted` for 
great places to start.

Before creating a new enhancement, please open a feature request issue or ask in an existing issue to discuss first, to make sure such a feature aligns with our visions and is not already being implemented. Please use our 
[feature request template](https://github.com/BikeNetKit/.github/blob/main/.github/ISSUE_TEMPLATE/feature_request.md) that automatically pops up when you press `New issue`.


## AI usage policy

TLDR: **No AI contributions accepted.**

The goal of BikeNetKit is for people - researchers, software developers - to create tools for people - planners, researchers, engaged citizens. This goal necessitates a collaborative effort by a human community with limited resources. The maintainers of this community should not be burdened with reviews and technical debts of "AI slop" code, apart from [many other problems associated with such code](https://blog.codeberg.org/protecting-our-floss-commons-from-llms.html). 

Therefore, BikeNetKit does not accept contributions/comments by or with assistance of large language models (LLMs)/generative AI tools. Maintainers may close issues, reject pull requests, or delete comments without explanation if they suspect such an origin.[^1] We are open to revising this policy at a later date, in case new tools appear that mitigate the problems of existing tools.

[^1]: One singular, historic exception is the repository [`bikenetkit.org`](https://github.com/BikeNetKit/bikenetkit.org) for the already finished visualization platform, developed by one contractor who used LLM-assistance.

Thus, when approaching BikeNetKit for the first time, through an issue or pull request, please let us know 1) What motivates you to contribute, and 2) How you use the software yourself. ❤️ We would love to know how people like you engage with BikeNetKit! 

## Development setup

### Getting Started

1. Fork the repository on GitHub
2. Clone your fork locally
3. Create a branch for your changes (see our [naming conventions](NAMING_CONVENTIONS.md))
4. Install the dev environment. We strongly recommend via [Pixi](https://pixi.prefix.dev/latest/), by running:
`pixi init --import environment-dev.yml`  
More information, for the example growbikenet: https://docs.bikenetkit.org/GrowBikeNet/installation/#development-installation

### Testing

Unit tests should be written for any new functionality that gets added to the project. Please add these tests to the `/tests/test_MODULE.py` file, for the respective `MODULE`.
Tests should follow the naming convention of `test_name_of_function`, where `name_of_function` is the name of the newly added function.
Ensure that the outputs of the function are what you expect, given exhaustive example inputs. For changes to functions that already exist, make sure to check if the tests that already exist still pass without issues. It is good practice to run all tests before submitting a Pull Request.

Running tests: `pytest`  

### Documentation

If you update docs, build them locally by running  
`sphinx-build docs/source docs/build`  
and check in the `docs/build` folder that the output is as expected.


## Pull Request Process

### Before Submitting

Update the documentation if you have changed or added features.

### Submitting

1. Push your branch to your fork.

2. Open a Pull Request against the `main` branch.

3. Fill out the [PR template](PULL_REQUEST_TEMPLATE.md) completely that shows up automatically.

4. Wait for review. We aim to respond within 7 days.

### PR Checklist

- [ ] My code follows the project's style guidelines
- [ ] I have performed a self-review of my own code
- [ ] I have commented my code, particularly in hard-to-understand areas
- [ ] I have updated the documentation
- [ ] My changes generate no new warnings
- [ ] I have added tests that prove my fix/feature works
- [ ] New and existing tests pass locally


### Code Style

- Use prettier and ruff for formatting via pre-commit ([config](pre-commit-config.yaml) included)
- Write self-documenting code with meaningful variable names
- Follow our [naming conventions](NAMING_CONVENTIONS.md)

### Testing

- All new features must include tests
- Tests should be deterministic (no flaky tests)


---

*Thank you for contributing! 🎉*

If you have questions, reach out to: contact@bikenetkit.org
