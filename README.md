About coin3d-rt-feedstock
=========================

Feedstock license: [BSD-3-Clause](https://github.com/realthunder/coin3d-feedstock/blob/main/LICENSE.txt)

Home: https://github.com/realthunder/coin

Package license: BSD-3-Clause

Summary: Coin3D with improved shadow renderering

Coind3D with improved support of shadow rendering

Current build status
====================


<table>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-coin3d--rt-green.svg)](https://anaconda.org/realthunder/coin3d-rt) | [![Conda Downloads](https://img.shields.io/conda/dn/realthunder/coin3d-rt.svg)](https://anaconda.org/realthunder/coin3d-rt) | [![Conda Version](https://img.shields.io/conda/vn/realthunder/coin3d-rt.svg)](https://anaconda.org/realthunder/coin3d-rt) | [![Conda Platforms](https://img.shields.io/conda/pn/realthunder/coin3d-rt.svg)](https://anaconda.org/realthunder/coin3d-rt) |

Installing coin3d-rt
====================

Installing `coin3d-rt` from the `realthunder/label/master` channel can be achieved by adding `realthunder/label/master` to your channels with:

```
conda config --add channels realthunder/label/master
conda config --set channel_priority strict
```

Once the `realthunder/label/master` channel has been enabled, `coin3d-rt` can be installed with `conda`:

```
conda install coin3d-rt
```

or with `mamba`:

```
mamba install coin3d-rt
```

It is possible to list all of the versions of `coin3d-rt` available on your platform with `conda`:

```
conda search coin3d-rt --channel realthunder/label/master
```

or with `mamba`:

```
mamba search coin3d-rt --channel realthunder/label/master
```

Alternatively, `mamba repoquery` may provide more information:

```
# Search all versions available on your platform:
mamba repoquery search coin3d-rt --channel realthunder/label/master

# List packages depending on `coin3d-rt`:
mamba repoquery whoneeds coin3d-rt --channel realthunder/label/master

# List dependencies of `coin3d-rt`:
mamba repoquery depends coin3d-rt --channel realthunder/label/master
```




Updating coin3d-rt-feedstock
============================

If you would like to improve the coin3d-rt recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`realthunder` channel, whereupon the built conda packages will be available for
everybody to install and use from the `realthunder` channel.
Note that all branches in the realthunder/coin3d-rt-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks, and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](https://docs.conda.io/projects/conda-build/en/latest/resources/define-metadata.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](https://docs.conda.io/projects/conda-build/en/latest/resources/define-metadata.html#build-number-and-string)
   back to 0.

Feedstock Maintainers
=====================

* [@realthunder](https://github.com/realthunder/)

