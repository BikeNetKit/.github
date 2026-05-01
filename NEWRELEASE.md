# Checklist for new releases

Follow the steps below to make a new release in a BikeNetKit repo.

## Preliminaries
- [ ] all tested, commited, and merged on main

## Versioning pip
- [ ] open releasevxxx branch
- [ ] pyproject.toml update version
- [ ] growbikenet/_version.py update version
- [ ] .release-please-manifest.json update version
- [ ] docs/conf.py update version
- [ ] update docs/changelog.md 
- [ ] update README.md
- [ ] merge, during pull request set autorelease:tagged

## Versioning Github
- [ ] click Releases
- [ ] Draft a new release
- [ ] Tag+Release title: Select tag with new version (Target: main)
- [ ] Release notes: Copy-paste from changelog.md
- [ ] Save draft
- [ ] click Release: See draft. Edit. Publish release.
- [ ] .github update release version in development table

## Conda forge
TBD

## Afterwards
- [ ] If package is in use, `pip PACKAGE --upgrade` or `pixi upgrade PACKAGE`
- [ ] Eventually: Announce / Newsletter / etc.