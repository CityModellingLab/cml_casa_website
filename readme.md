### Installation

This uses Quarto.

On a Mac, you can install Quarto:

```shell
brew install quarto
```

### Testing changes

```shell
quarto preview
```

Quarto will build the various quarto mark down files and spin up a local server.
```
(base) ➜  cml_casa_website git:(master) quarto preview
Preparing to preview
[ 1/15] projects/proj/proj1/AI4CI_overview.qmd
[ 2/15] projects/index.qmd
[ 3/15] index.qmd
[ 4/15] presentations/old_pres/pres1/presentation1.qmd
[ 5/15] presentations/index.qmd
[ 6/15] presentations/pres/AUM_pres/AUM_presentation.qmd
[ 7/15] people/index.qmd
[ 8/15] people/profiles/tom/tom.qmd
[ 9/15] people/profiles/clara/clara.qmd
[10/15] people/profiles/claude/claude.qmd
[11/15] people/profiles/esra/esra.qmd
[12/15] people/profiles/bea/bea.qmd
[13/15] people/profiles/gerry/gerry.qmd
[14/15] people/profiles/maria/maria.qmd
[15/15] people/profiles/adam/adam.qmd

Watching files for changes
Browse at http://localhost:6831/
GET: /
```

### Deployment
GitHub is configured to take the latest changes from Master, and deploy them on citymodellinglab.uk