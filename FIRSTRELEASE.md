# Checklist for setting up releases

Follow the steps below in order to setup releases in a BikeNetKit repo with package PACKAGENAME.

## Preliminaries
- [ ] All tested, commited, and merged on main
- [ ] Decide on a new version number X.Y.Z using [semantic versioning](https://semver.org). For a first release the recommended version is 0.1.0.

## Set up pypi releases
### On pypi
- [ ] pypi: Account settings > Your projects > Publishing > Add a new pending publisher > GitHub 
    - PyPI Project Name: PACKAGENAME
    - Owner: BikeNetKit
    - Repository name: PACKAGENAME
    - Workflow name: publish.yml
    - Environment name: pypi

### On Github
- [ ] Settings > Environments > New environment without extra configuration: pypi
- [ ] Pull requests > Labels > New label, color red: `autorelease: tagged` (the space is important!)
- [ ] Add and configure `.github/workflows/publish.yml`
- [ ] Add and configure `setup.py`
- [ ] Add and configure `pyproject.toml`
- [ ] Add and configure `PACKAGENAME/__init__.py`

## Set up Github releases (with sphinx docs)
- [ ] Add and configure `PACKAGENAME/_version.py`
- [ ] Add and configure `release-please-config.json`
- [ ] Add and configure `.release-please-manifest.json`
- [ ] Add and configure `docs/changelog.md`
- [ ] Add and configure `docs/conf.py`

## Set up conda releases
- [ ] Generate the `recipe.yaml` (v1) with these grayskull commands: https://conda-forge.org/docs/maintainer/adding_pkgs/#generating-the-recipe
- [ ] Add the recipe and license to a new PR in the [staged-recipes](https://github.com/conda-forge/staged-recipes)
- [ ] Wait for reviewers to approve (can take weeks!): https://conda-forge.org/docs/maintainer/adding_pkgs/#feedback-and-revision

To make a new release, follow [NEWRELEASE.md](NEWRELEASE.md).
