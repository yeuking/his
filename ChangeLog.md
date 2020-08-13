# Changelog

## 2020.6.88468 (16 June 2020)

### Enhancements

1. Removed `python.jediEnabled` setting in favor of `python.languageServer`. Instead of `"python.jediEnabled": true` please use `"python.languageServer": "Jedi"`.
   ([#7010](https://github.com/Microsoft/vscode-python/issues/7010))
1. Added a start page for the extension. It opens to new users or when there is a new release. It can be disabled with the setting 'Python: Show Start Page'.
   ([#11057](https://github.com/Microsoft/vscode-python/issues/11057))
1. Preliminary support using other languages for the kernel.
   ([#11919](https://github.com/Microsoft/vscode-python/issues/11919))
1. Enable the use of the custom editor for native notebooks.
   ([#10744](https://github.com/Microsoft/vscode-python/issues/10744))

### Fixes

1. Ensure sorting imports in a modified file picks up the proper configuration.
   thanks [Peter Law](https://github.com/PeterJCLaw))
   ([#4891](https://github.com/Microsoft/vscode-python/issues/4891))
1. Made variable explorer (from IPython Notebook interface) resizable.
   ([#5382](https://github.com/Microsoft/vscode-python/issues/5382))
1. Add junit family to pytest runner args to remove pytest warning.
   ([#10673](https://github.com/Microsoft/vscode-python/issues/10673))


### Code Health

1. Use ts-loader as a tyepscript loader in webpack.
   ([#9061](https://github.com/Microsoft/vscode-python/issues/9061))
1. Fixed typo from unitest -> unittest.
   (thanks [Rameez Khan](https://github.com/Rxmeez)).
   ([#10919](https://github.com/Microsoft/vscode-python/issues/10919))
1. Make functional tests more deterministic.
   ([#11058](https://github.com/Microsoft/vscode-python/issues/11058))

### Thanks

Thanks to the following projects which we fully rely on to provide some of
our features:

-   [debugpy](https://pypi.org/project/debugpy/)
-   [isort](https://pypi.org/project/isort/)
-   [jedi](https://pypi.org/project/jedi/)
    and [parso](https://pypi.org/project/parso/)

Also thanks to the various projects we provide integrations with which help
make this extension useful:

-   Debugging support:
    [Django](https://pypi.org/project/Django/),
    [Flask](https://pypi.org/project/Flask/),
    [gevent](https://pypi.org/project/gevent/)

And finally thanks to the [Python](https://www.python.org/) development team and community for creating a fantastic programming language and community to be a
part of!

## 2020.5.3 (10 June 2020)

1. Update `debugpy` to use `1.0.0b11` or greater.

### Thanks

Thanks to the following projects which we fully rely on to provide some of
our features:

-   [debugpy](https://pypi.org/project/debugpy/)
-   [isort](https://pypi.org/project/isort/)
-   [jedi](https://pypi.org/project/jedi/)


## Version 0.1.3

-   Fixed linting when using pylint

## Version 0.1.2

-   Fixed autoformatting of code (falling over when using yapf8)

## Version 0.1.1

-   Fixed linting of files on Mac
-   Added support for linting using pep8
-   Added configuration support for pep8 and pylint
-   Added support for configuring paths for pep8, pylint and autopep8
-   Added snippets
-   Added support for formatting using yapf
-   Added a number of configuration settings

## Version 0.0.4

-   Added support for linting using Pylint (configuring pylint is coming soon)
-   Added support for sorting Imports (Using the command "Pythong: Sort Imports")
-   Added support for code formatting using Autopep8 (configuring autopep8 is coming soon)
-   Added ability to view global variables, arguments, add and remove break points

## Version 0.0.3

-   Added support for debugging using PDB
