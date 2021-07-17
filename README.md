[![Chocolatey](https://img.shields.io/chocolatey/v/zoe.svg)](https://chocolatey.org/packages/zoe)
[![Chocolatey](https://img.shields.io/chocolatey/dt/zoe.svg)](https://chocolatey.org/packages/zoe)


# chocolatey-zoe

[Chocolatey](https://chocolatey.org) package source to install [zoe](https://adevinta.github.io/zoe/).

# Zoe install on Windows

Now, the install process on windows is as easy as :

```
sdk install java
choco install zoe
```

# Prerequisite

Have [chocolatey](https://chocolatey.org/) [properly installed](https://chocolatey.org/install) and web access.


# Install from choco repo

To install schemacrawler, simply run, with ```Administrator``` privileges :

```
choco install zoe
```

Uninstall package :

```
choco uninstall zoe
```




# Build and install commands

With ```Administrator privileges```, run a ```cmd``` shell.

Uninstall package :

```
choco uninstall zoe
```

Manually build and install the package from the source :

```
choco install -fdv zoe.nuspec
```

Push the package to central [package repository](https://chocolatey.org/packages) : check prepared `ant` tasks.

# For developers

For developers, take a look at the ```ant``` build tasks used to automate package compile and build.

Upgrade process:

1. Upgrade verion un properties file
2. `ant make`
3. Install locally `choco install -fdv zoe.nuspec`
4. Test command line `zoe --version`


