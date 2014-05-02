# flake8 atom package

flake8 is an atom package that let you run flake8 on your current Python file.

![preview](https://raw.github.com/julozi/atom-flake8/master/preview.png)

## Installation

Use the Atom package manager, which can be found in the Settings view or
run `apm install flake8` from the command line.

The package uses the *flake8 binary* that must be installed manually on your system.

To install `flake8`, use the `pip` :

`pip install flake8`

or easy_install :

`easy_install flake8`

The flake8 package has been tested against flake8 version 2.1.0.

For more information about flake8 see [the official documentation page](http://flake8.readthedocs.org/en/2.0/)

## Settings

- Flake8 path : path of the flake8 binary (defaults to /usr/local/bin/flake8)
- Ignore errors : a comma separated list of ignored errors (this setting is passed to the --ignore flake8 command line option)
- Validate on save : trigger flake8 validation automatically when a Python file is saved

## Licence

[MIT](http://opensource.org/licenses/MIT)
