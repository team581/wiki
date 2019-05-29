title: Python
description: Python is a programming language used by some of software we use.

# [Python](https://www.python.org/)

[Python](https://www.python.org/) is a programming language used by some of software we use.

## Installation

!!! info
    Requires administrator privileges.

You can install [Python](https://www.python.org/) with [Chocolatey](/tools/chocolatey) or using their online installer.
Make sure to download the version that is 64 bit (32 bit is for very old CPUs).
Look for something labeled `x86-64`.

### Chocolatey

Run the following in an elevated (administrator) command prompt.

```bash
choco install python
```

### Installer

![A screenshot of the [Python](https://www.python.org/) installer](/images/tools/python/installation.png)

1. Download the latest version for your system from the [Python downloads page](https://www.python.org/downloads/).
2. Run the file.
3. If prompted, select the checkbox prompting you to add [Python](https://www.python.org/) to the system PATH.
4. Click the `Install now` button.
5. If prompted, select `Yes` when asked if you want to run the file as an administrator.

After installation, you may want to [refresh the environment variables](/guides/windows/refreshing-environment-variables) to use [Python](https://www.python.org/).

## [Pipenv](https://pipenv.readthedocs.io/en/latest/)

[Pipenv](https://pipenv.readthedocs.io/en/latest/) is a package manager you can use for your [Python](https://www.python.org/) projects.

### [Pipenv](https://pipenv.readthedocs.io/en/latest/) Installation

Run the following in a command prompt to install [Pipenv](https://pipenv.readthedocs.io/en/latest/).

```bash
pip install pipenv
```
