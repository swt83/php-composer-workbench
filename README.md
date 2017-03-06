# Workbench

A standalone PHP app for developing Composer packages.

## Usage

Clone this repo to your hard drive:

```bash
$ git clone git@github.com:swt83/php-composer-workbench.git workbench
```

Clone your package into the packages directory and run ``composer update``:

```bash
$ cd workbench
$ git clone <YOURREPOADDRESS> packages/<YOURVENDORNAME>/<YOURREPONAME>
$ composer update
```

Use the existing ``index.php`` file to test your package(s). Use ``xx($response)`` to dump variables for debugging.