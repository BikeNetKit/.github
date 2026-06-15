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
- [ ] Click `Releases`
- [ ] Draft a new release
- [ ] Tag+Release title: Create tag called `vX.Y.Z` (Target: main)
- [ ] Release notes: Copy-paste from `changelog.md`
- [ ] Save draft
- [ ] Click `Releases`: Check draft. Edit. Click `Publish release`.
- [ ] Update last release version in development table of the [.github profile README](https://github.com/BikeNetKit/.github/blob/main/profile/README.md), and [Status](https://pypi.org/classifiers/) if needed

## Conda forge
TBD

## Afterwards
- [ ] If package is in use, run `pip PACKAGENAME --upgrade` or `pixi upgrade PACKAGENAME`
- [ ] Eventually: Announce / Newsletter / etc.
