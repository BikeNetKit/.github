# Checklist for new releases

Follow the steps below in order to make a new release in a BikeNetKit repo with package PACKAGENAME.

## Preliminaries
- [ ] All tested, commited, and merged on main
- [ ] Decide on a new version number X.Y.Z using [semantic versioning](https://semver.org).

## Versioning pip
- [ ] Create a new `releaseX.Y.Z` branch
- [ ] Update version in `PACKAGENAME/_version.py`
- [ ] Update version in `.release-please-manifest.json`
- [ ] Update version in `pyproject.toml`
- [ ] Update [Development Status](https://pypi.org/classifiers/) in `pyproject.toml`, if needed
- [ ] Update version and release date in `CITATION.cff`
- [ ] Update `docs/changelog.md `. Use [gitmojis](https://gitmoji.dev/).
- [ ] Update `README.md`
- [ ] Merge, during pull request set Labels > `autorelease: tagged`
- [ ] Check that the new version was updated at https://pypi.org/project/PACKAGENAME/

## Versioning Github
- [ ] Update last release version in development table of the [.github profile README](https://github.com/BikeNetKit/.github/blob/main/profile/README.md), and [Status](https://pypi.org/classifiers/) if needed
- [ ] Click `Releases`
- [ ] Draft a new release
- [ ] Tag+Release title: Create tag called `vX.Y.Z` (Target: main)
- [ ] Release notes: Copy-paste from `changelog.md`
- [ ] Save draft
- [ ] Click `Releases`: Check draft. Edit. Click `Publish release`.

## Conda forge
- [ ] Wait for some hours until the [regro-cf-autotick-bot](https://conda-forge.org/docs/maintainer/updating_pkgs/#how-does-regro-cf-autotick-bot-create-automatic-version-updates) has discovered the new release on PyPI
- [ ] Once done, there should be a PR here with the newest release (example growbikenet): https://github.com/pulls/search?q=is%3Aopen+is%3Apr+author%3Aregro-cf-autotick-bot+archived%3Afalse+growbikenet
- [ ] If there were no dependency and license changes, and all checks passed: Merge the PR
- [ ] If there were dependency or license changes, or not all checks passed: Use the hub tool to push updates/fixes to the branch as needed: https://conda-forge.org/docs/maintainer/updating_pkgs/#pushing-to-regro-cf-autotick-bot-branch
- [ ] Once all checks have passed, merge the PR
- [ ] Check that the new version was updated at https://anaconda.org/conda-forge/PACKAGENAME

## Afterwards
- [ ] If docs had new content that relied on the new conda version, rebuild them (without caching).
- [ ] If package is in use, run `pixi upgrade PACKAGENAME`
- [ ] Post on [LinkedIn](https://www.linkedin.com/company/bikenetkit)
- [ ] Post on [Mastodon](https://fosstodon.org/@bikenetkit)
- [ ] Post on [Bluesky](https://bsky.app/profile/bikenetkit.bsky.social)
