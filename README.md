What is it?
-----------

This module provides ESLint, Istanbul, Mocha, and Nodemon as well as NPM scripts for linting, validation modules, validation dependencies, coverage reports for multiprocess applications, and coverage badges. A Git precommit-hook is used to run linting, module valiation, and depedency checks before a Git commit is made.

> ### NOTE: This module is a wrapper around [git-validate](https://github.com/nlf/git-validate)

> ### WARNING: If you already have a `.git/hooks/pre-commit` file, this package will overwrite it.

Usage
-----

When this module is installed base `.depcheckrc`, `.eslintignore` and `.eslintrc` files will be created if they do not already exist. These files are safe to edit once they have been created and will not be overwritten. If you have your ESLint configuration in your `package.json`, then the `.eslintrc` file will not be created.
