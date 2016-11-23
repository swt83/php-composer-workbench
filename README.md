# Workbench

A testing ground for developing Composer packages.

## Usage

Clone to your hard drive:

```bash
$ git clone git@github.com:swt83/php-composer-workbench.git workbench
```

Clone your package into the packages directory:

```bash
$ cd workbench
$ git clone <YOURREPOADDRESS> packages/<YOURREPONAME>
```

Amend the ``composer.json`` file to include your new package and update:

```json
"require": {
    "travis/dump": "dev-master"
    "your/repo": "dev-master"
},
```

```bash
$ composer update
```

Use the existing ``index.php`` file to test your package(s). Use ``xx($response)`` to dump variables for debugging.