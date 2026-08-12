# BikeNetKit naming conventions

Here we describe all naming conventions we follow when developing BikeNetKit. Most of this is not a super strict rule set, more a guideline that has emerged that would be nice to follow so that all parts of the code base have a consistent look.

## Code

Please follow [PEP8](https://peps.python.org/pep-0008/). Much of this is already checked/fixed automatically by our [pre-commit hooks](pre-commit-config.yaml).

## Commits

Please start with a capital letter, use imperative form, and make it concise (max 50 characters) and human readable. Example: `Add seed point setting`  

More information here: https://chris.beams.io/git-commit

## Branches

Please use lowercase, add a prefix, separate words by hyphens, make it concise and human-readable. Example: `feature/add-seed-point-framework`

More information here: https://medium.com/@abhay.pixolo/naming-conventions-for-git-branches-a-cheatsheet-8549feca2534

## Exported data

As exported data also sometimes need to be imported in larger pipelines, we have converged to the following convention:

`<city>-<tool>-<algorithm>-<layer>[-<variant>].fileextension`, lowercase, single extension.
Example: `amsterdam_nl-growbikenet-betweenness-grid-with_bikenw.geojson`

For generating slugs from names, use our slugifier function `slugify()`, for now implemented here (to be moved to BikeNetLib): https://github.com/BikeNetKit/GrowBikeNet/blob/main/growbikenet/functions.py

## Underscores

Use leading underscores for names of functions and constants to show if they are meant to be internal to a specific package or so technical/auxiliary that they should not be accessed by users.

## Docstrings

Please follow the [numpy conventions](https://numpydoc.readthedocs.io/en/latest/format.html#docstring-standard). Every function must have a docstring.