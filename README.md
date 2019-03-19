<!--
# -*- mode: jinja -*-
-->

About alps
==========

Home: http://alps.comp-phys.org/

Package license: ALPS

Feedstock license: BSD 3-Clause

Summary: Algorithms and Libraries for Physics Simulations

The ALPS project (Algorithms and Libraries for Physics Simulations) is an
open-source effort aiming at providing high-end simulation codes for strongly
correlated quantum mechanical systems as well as C++ libraries for simplifying
the development of such code. ALPS strives to increase software reuse in the
physics community.


Current build status
====================

[![Linux](https://img.shields.io/circleci/project/github/conda-forge/alps-feedstock/master.svg?label=Linux)](https://circleci.com/gh/conda-forge/alps-feedstock)
[![OSX](https://img.shields.io/travis/conda-forge/alps-feedstock/master.svg?label=macOS)](https://travis-ci.org/conda-forge/alps-feedstock)
[![Windows](https://img.shields.io/appveyor/ci/conda-forge/alps-feedstock/master.svg?label=Windows)](https://ci.appveyor.com/project/conda-forge/alps-feedstock/branch/master)

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-alps-green.svg)](https://anaconda.org/conda-forge/alps) | [![Conda Downloads](https://img.shields.io/conda/dn/conda-forge/alps.svg)](https://anaconda.org/conda-forge/alps) | [![Conda Version](https://img.shields.io/conda/vn/conda-forge/alps.svg)](https://anaconda.org/conda-forge/alps) | [![Conda Platforms](https://img.shields.io/conda/pn/conda-forge/alps.svg)](https://anaconda.org/conda-forge/alps) |

Installing alps
===============

Installing `alps` from the `conda-forge` channel can be achieved by adding `conda-forge` to your channels with:

```
conda config --add channels conda-forge
```

Once the `conda-forge` channel has been enabled, `alps` can be installed with:

```
conda install alps
```

It is possible to list all of the versions of `alps` available on your platform with:

```
conda search alps --channel conda-forge
```


About conda-forge
=================

[![Powered by NumFOCUS](https://img.shields.io/badge/powered%20by-NumFOCUS-orange.svg?style=flat&colorA=E1523D&colorB=007D8A)](http://numfocus.org)

conda-forge is a community-led conda channel of installable packages.
In order to provide high-quality builds, the process has been automated into the
conda-forge GitHub organization. The conda-forge organization contains one repository
for each of the installable packages. Such a repository is known as a *feedstock*.

A feedstock is made up of a conda recipe (the instructions on what and how to build
the package) and the necessary configurations for automatic building using freely
available continuous integration services. Thanks to the awesome service provided by
[CircleCI](https://circleci.com/), [AppVeyor](https://www.appveyor.com/)
and [TravisCI](https://travis-ci.org/) it is possible to build and upload installable
packages to the [conda-forge](https://anaconda.org/conda-forge)
[Anaconda-Cloud](https://anaconda.org/) channel for Linux, Windows and OSX respectively.

To manage the continuous integration and simplify feedstock maintenance
[conda-smithy](https://github.com/conda-forge/conda-smithy) has been developed.
Using the ``conda-forge.yml`` within this repository, it is possible to re-render all of
this feedstock's supporting files (e.g. the CI configuration files) with ``conda smithy rerender``.

For more information please check the [conda-forge documentation](https://conda-forge.org/docs/).

Terminology
===========

**feedstock** - the conda recipe (raw material), supporting scripts and CI configuration.

**conda-smithy** - the tool which helps orchestrate the feedstock.
                   Its primary use is in the construction of the CI ``.yml`` files
                   and simplify the management of *many* feedstocks.

**conda-forge** - the place where the feedstock and smithy live and work to
                  produce the finished article (built conda distributions)


Updating alps-feedstock
=======================

If you would like to improve the alps recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`conda-forge` channel, whereupon the built conda packages will be available for
everybody to install and use from the `conda-forge` channel.
Note that all branches in the conda-forge/alps-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](https://conda.io/docs/user-guide/tasks/build-packages/define-metadata.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](https://conda.io/docs/user-guide/tasks/build-packages/define-metadata.html#build-number-and-string)
   back to 0.

Feedstock Maintainers
=====================

* [@dolfim](https://github.com/dolfim/)

