# Checklist for new releases

Follow the steps below in order to make a new release in a BikeNetKit repo with package PACKAGENAME.

## Preliminaries
- [ ] all tested, commited, and merged on main

## Versioning pip
- [ ] Decide on a new version number X.Y.Z using [semantic versioning](https://semver.org).
- [ ] open releaseXYZ branch
- [ ] pyproject.toml update version
- [ ] PACKAGENAME/_version.py update version
- [ ] .release-please-manifest.json update version
- [ ] docs/conf.py update version
- [ ] update docs/changelog.md 
- [ ] update README.md
- [ ] merge, during pull request set autorelease:tagged
- [ ] Check that the new version was updated at https://pypi.org/project/PACKAGENAME/

## Versioning Github
- [ ] click Releases
- [ ] Draft a new release
- [ ] Tag+Release title: Select tag with new version (Target: main)
- [ ] Release notes: Copy-paste from changelog.md
- [ ] Save draft
- [ ] click Release: See draft. Edit. Publish release.
- [ ] .github update last release version in development table

## Conda forge
TBD

## Afterwards
- [ ] If package is in use, `pip PACKAGENAME --upgrade` or `pixi upgrade PACKAGENAME`
- [ ] Eventually: Announce / Newsletter / etc.