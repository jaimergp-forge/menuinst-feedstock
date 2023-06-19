About menuinst-feedstock
========================

Feedstock license: [BSD-3-Clause](https://github.com/conda-forge/menuinst-feedstock/blob/main/LICENSE.txt)

Home: https://github.com/conda/menuinst/

Package license: BSD-3-Clause

Summary: cross platform install of menu items

Development: https://github.com/conda/menuinst

Documentation: https://github.com/conda/menuinst/wiki

Current build status
====================


<table>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-menuinst-green.svg)](https://anaconda.org/napari/menuinst) | [![Conda Downloads](https://img.shields.io/conda/dn/napari/menuinst.svg)](https://anaconda.org/napari/menuinst) | [![Conda Version](https://img.shields.io/conda/vn/napari/menuinst.svg)](https://anaconda.org/napari/menuinst) | [![Conda Platforms](https://img.shields.io/conda/pn/napari/menuinst.svg)](https://anaconda.org/napari/menuinst) |

Installing menuinst
===================

Installing `menuinst` from the `napari` channel can be achieved by adding `napari` to your channels with:

```
conda config --add channels napari
conda config --set channel_priority strict
```

Once the `napari` channel has been enabled, `menuinst` can be installed with `conda`:

```
conda install menuinst
```

or with `mamba`:

```
mamba install menuinst
```

It is possible to list all of the versions of `menuinst` available on your platform with `conda`:

```
conda search menuinst --channel napari
```

or with `mamba`:

```
mamba search menuinst --channel napari
```

Alternatively, `mamba repoquery` may provide more information:

```
# Search all versions available on your platform:
mamba repoquery search menuinst --channel napari

# List packages depending on `menuinst`:
mamba repoquery whoneeds menuinst --channel napari

# List dependencies of `menuinst`:
mamba repoquery depends menuinst --channel napari
```




Updating menuinst-feedstock
===========================

If you would like to improve the menuinst recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`napari` channel, whereupon the built conda packages will be available for
everybody to install and use from the `napari` channel.
Note that all branches in the conda-forge/menuinst-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](https://docs.conda.io/projects/conda-build/en/latest/resources/define-metadata.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](https://docs.conda.io/projects/conda-build/en/latest/resources/define-metadata.html#build-number-and-string)
   back to 0.

Feedstock Maintainers
=====================

* [@carlodri](https://github.com/carlodri/)
* [@goanpeca](https://github.com/goanpeca/)
* [@jaimergp](https://github.com/jaimergp/)
* [@jakirkham](https://github.com/jakirkham/)

