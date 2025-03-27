About piconnect-feedstock
=========================

Feedstock license: [BSD-3-Clause](https://github.com/conda-forge/piconnect-feedstock/blob/main/LICENSE.txt)

Home: https://github.com/Hugovdberg/PIconnect

Package license: MIT

Summary: PIconnect - Connector to the OSISoft PI and PI-AF databases.

Documentation: https://piconnect.readthedocs.io/en/stable/

#########
PIconnect
#########

A python connector to the OSISoft PI and PI-AF databases
========================================================

This connector allows access to the OSISoft PI System through their
proprietary SDK. It provides a number of classes, mostly mirroring the AF SDK
structure, but at the same time implementing the cool stuff we use Python for.
Connections to the database are therefore implemented as context managers, to
allow opening a connection using a with statement.

.. image:: https://img.shields.io/pypi/v/PIconnect.svg
    :target: https://pypi.python.org/pypi/PIconnect
    :alt: PIconnect on PyPI

.. image:: https://img.shields.io/conda/vn/conda-forge/piconnect
    :target: https://anaconda.org/conda-forge/piconnect
    :alt: PIconnect on conda-forge

.. image:: https://github.com/Hugovdberg/PIconnect/actions/workflows/ci.yml/badge.svg?branch=develop
    :target: https://github.com/Hugovdberg/PIconnect/actions/workflows/ci.yml
    :alt: Continuous Integration status

.. image:: https://readthedocs.org/projects/piconnect/badge/?version=develop
    :target: https://piconnect.readthedocs.io/en/latest/?badge=develop
    :alt: Documentation Status

.. image:: https://pyup.io/repos/github/Hugovdberg/PIconnect/shield.svg
    :target: https://pyup.io/repos/github/Hugovdberg/PIconnect/
    :alt: Security Updates

.. image:: https://api.codacy.com/project/badge/Grade/568734c85e07467c99e0e791d8eb17b6
    :target: https://www.codacy.com/app/Hugovdberg/PIconnect?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=Hugovdberg/PIconnect&amp;utm_campaign=Badge_Grade
    :alt: Automated code review

.. image:: https://img.shields.io/badge/code%20style-black-000000.svg
    :target: https://github.com/psf/black
    :alt: Code style: black

Python connector to OSIsoft PI SDK


* Free software: MIT license
* Documentation: https://piconnect.readthedocs.io.


Features
--------
Features below are for both: PI Server and PIAF Database:

* Extract recorded values
* Extract interpolated values
* Update a value
* Summarize data before extraction with help of OSIsoft PI SDK
* Filter data before extraction with help of OSIsoft PI SDK

Copyright notice
================
OSIsoft, the OSIsoft logo and logotype, Managed PI, OSIsoft Advanced Services,
OSIsoft Cloud Services, OSIsoft Connected Services, PI ACE, PI Advanced
Computing Engine, PI AF SDK, PI API, PI Asset Framework, PI Audit Viewer, PI
Builder, PI Cloud Connect, PI Connectors, PI Data Archive, PI DataLink, PI
DataLink Server, PI Developer's Club, PI Integrator for Business Analytics, PI
Interfaces, PI JDBC driver, PI Manual Logger, PI Notifications, PI ODBC, PI
OLEDB Enterprise, PI OLEDB Provider, PI OPC HDA Server, PI ProcessBook, PI
SDK, PI Server, PI Square, PI System, PI System Access, PI Vision, PI
Visualization Suite, PI Web API, PI WebParts, PI Web Services, RLINK and
RtReports are all trademarks of OSIsoft, LLC.

Credits
---------

This package was created with Cookiecutter_ and the
`audreyr/cookiecutter-pypackage`_ project template.

.. _Cookiecutter: https://github.com/audreyr/cookiecutter
.. _`audreyr/cookiecutter-pypackage`: https://github.com/audreyr/cookiecutter-pypackage

Current build status
====================


<table>
    
  <tr>
    <td>Azure</td>
    <td>
      <details>
        <summary>
          <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=13636&branchName=main">
            <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/piconnect-feedstock?branchName=main">
          </a>
        </summary>
        <table>
          <thead><tr><th>Variant</th><th>Status</th></tr></thead>
          <tbody><tr>
              <td>win_64_python3.11.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=13636&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/piconnect-feedstock?branchName=main&jobName=win&configuration=win%20win_64_python3.11.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>win_64_python3.12.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=13636&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/piconnect-feedstock?branchName=main&jobName=win&configuration=win%20win_64_python3.12.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>win_64_python3.13.____cp313</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=13636&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/piconnect-feedstock?branchName=main&jobName=win&configuration=win%20win_64_python3.13.____cp313" alt="variant">
                </a>
              </td>
            </tr>
          </tbody>
        </table>
      </details>
    </td>
  </tr>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-piconnect-green.svg)](https://anaconda.org/conda-forge/piconnect) | [![Conda Downloads](https://img.shields.io/conda/dn/conda-forge/piconnect.svg)](https://anaconda.org/conda-forge/piconnect) | [![Conda Version](https://img.shields.io/conda/vn/conda-forge/piconnect.svg)](https://anaconda.org/conda-forge/piconnect) | [![Conda Platforms](https://img.shields.io/conda/pn/conda-forge/piconnect.svg)](https://anaconda.org/conda-forge/piconnect) |

Installing piconnect
====================

Installing `piconnect` from the `conda-forge` channel can be achieved by adding `conda-forge` to your channels with:

```
conda config --add channels conda-forge
conda config --set channel_priority strict
```

Once the `conda-forge` channel has been enabled, `piconnect` can be installed with `conda`:

```
conda install piconnect
```

or with `mamba`:

```
mamba install piconnect
```

It is possible to list all of the versions of `piconnect` available on your platform with `conda`:

```
conda search piconnect --channel conda-forge
```

or with `mamba`:

```
mamba search piconnect --channel conda-forge
```

Alternatively, `mamba repoquery` may provide more information:

```
# Search all versions available on your platform:
mamba repoquery search piconnect --channel conda-forge

# List packages depending on `piconnect`:
mamba repoquery whoneeds piconnect --channel conda-forge

# List dependencies of `piconnect`:
mamba repoquery depends piconnect --channel conda-forge
```


About conda-forge
=================

[![Powered by
NumFOCUS](https://img.shields.io/badge/powered%20by-NumFOCUS-orange.svg?style=flat&colorA=E1523D&colorB=007D8A)](https://numfocus.org)

conda-forge is a community-led conda channel of installable packages.
In order to provide high-quality builds, the process has been automated into the
conda-forge GitHub organization. The conda-forge organization contains one repository
for each of the installable packages. Such a repository is known as a *feedstock*.

A feedstock is made up of a conda recipe (the instructions on what and how to build
the package) and the necessary configurations for automatic building using freely
available continuous integration services. Thanks to the awesome service provided by
[Azure](https://azure.microsoft.com/en-us/services/devops/), [GitHub](https://github.com/),
[CircleCI](https://circleci.com/), [AppVeyor](https://www.appveyor.com/),
[Drone](https://cloud.drone.io/welcome), and [TravisCI](https://travis-ci.com/)
it is possible to build and upload installable packages to the
[conda-forge](https://anaconda.org/conda-forge) [anaconda.org](https://anaconda.org/)
channel for Linux, Windows and OSX respectively.

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


Updating piconnect-feedstock
============================

If you would like to improve the piconnect recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`conda-forge` channel, whereupon the built conda packages will be available for
everybody to install and use from the `conda-forge` channel.
Note that all branches in the conda-forge/piconnect-feedstock are
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

* [@Hugovdberg](https://github.com/Hugovdberg/)

