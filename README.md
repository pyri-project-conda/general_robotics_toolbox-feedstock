About general_robotics_toolbox
==============================

Home: https://github.com/rpiRobotics/rpi_general_robotics_toolbox_py

Package license: BSD

Feedstock license: [BSD-3-Clause](https://github.com/pyri-project/general_robotics_toolbox-feedstock/blob/master/LICENSE.txt)

Summary: Python robotics toolbox

Current build status
====================


<table><tr>
    <td>All platforms:</td>
    <td>
      <img src="https://img.shields.io/badge/noarch-disabled-lightgrey.svg" alt="noarch disabled">
    </td>
  </tr>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-general_robotics_toolbox-green.svg)](https://anaconda.org/pyri-project/general_robotics_toolbox) | [![Conda Downloads](https://img.shields.io/conda/dn/pyri-project/general_robotics_toolbox.svg)](https://anaconda.org/pyri-project/general_robotics_toolbox) | [![Conda Version](https://img.shields.io/conda/vn/pyri-project/general_robotics_toolbox.svg)](https://anaconda.org/pyri-project/general_robotics_toolbox) | [![Conda Platforms](https://img.shields.io/conda/pn/pyri-project/general_robotics_toolbox.svg)](https://anaconda.org/pyri-project/general_robotics_toolbox) |

Installing general_robotics_toolbox
===================================

Installing `general_robotics_toolbox` from the `pyri-project` channel can be achieved by adding `pyri-project` to your channels with:

```
conda config --add channels pyri-project
conda config --set channel_priority strict
```

Once the `pyri-project` channel has been enabled, `general_robotics_toolbox` can be installed with:

```
conda install general_robotics_toolbox
```

It is possible to list all of the versions of `general_robotics_toolbox` available on your platform with:

```
conda search general_robotics_toolbox --channel pyri-project
```




Updating general_robotics_toolbox-feedstock
===========================================

If you would like to improve the general_robotics_toolbox recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`pyri-project` channel, whereupon the built conda packages will be available for
everybody to install and use from the `pyri-project` channel.
Note that all branches in the pyri-project/general_robotics_toolbox-feedstock are
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


