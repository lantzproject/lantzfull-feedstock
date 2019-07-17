About lantzfull
===============

Home: https://github.com/lantzproject/lantz

Package license: BSD

Feedstock license: BSD 3-Clause

Summary: Instrumentation framework

Lantz is an automation and instrumentation toolkit with a clean, well-designed and consistent interface.
It provides a core of commonly used functionalities for building applications that communicate with
scientific instruments allowing rapid application prototyping, development and testing.


Current build status
====================


<table>
  <tr>
    <td>Linux</td>
    <td>
      <img src="https://img.shields.io/badge/linux-disabled-lightgrey.svg" alt="linux disabled">
    </td>
  </tr>
  <tr>
    <td>OSX</td>
    <td>
      <img src="https://img.shields.io/badge/OSX-disabled-lightgrey.svg" alt="OSX disabled">
    </td>
  </tr>
  <tr>
    <td>Windows</td>
    <td>
      <img src="https://img.shields.io/badge/Windows-disabled-lightgrey.svg" alt="Windows disabled">
    </td>
  </tr>
![ppc64le disabled](https://img.shields.io/badge/ppc64le-disabled-lightgrey.svg)
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-lantzfull-green.svg)](https://anaconda.org/hgrecco/lantzfull) | [![Conda Downloads](https://img.shields.io/conda/dn/hgrecco/lantzfull.svg)](https://anaconda.org/hgrecco/lantzfull) | [![Conda Version](https://img.shields.io/conda/vn/hgrecco/lantzfull.svg)](https://anaconda.org/hgrecco/lantzfull) | [![Conda Platforms](https://img.shields.io/conda/pn/hgrecco/lantzfull.svg)](https://anaconda.org/hgrecco/lantzfull) |

Installing lantzfull
====================

Installing `lantzfull` from the `hgrecco` channel can be achieved by adding `hgrecco` to your channels with:

```
conda config --add channels hgrecco
```

Once the `hgrecco` channel has been enabled, `lantzfull` can be installed with:

```
conda install lantzfull
```

It is possible to list all of the versions of `lantzfull` available on your platform with:

```
conda search lantzfull --channel hgrecco
```




Updating lantzfull-feedstock
============================

If you would like to improve the lantzfull recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`hgrecco` channel, whereupon the built conda packages will be available for
everybody to install and use from the `hgrecco` channel.
Note that all branches in the lantzproject/lantzfull-feedstock are
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


