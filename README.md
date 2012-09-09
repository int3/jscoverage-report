JSCoverage Report
=================

This HTML report was extracted from the [JSCoverage][jscov] project. It will
display a nice HTML report when fed it a JSON file of the form:

    {
        "path/to/file.js":
            "coverage": [
                null,
                0,
                ...
            ],
            "source": [
                "function foo() {",
                "   var a = 1;",
                    ...
            ]
    }

The numbers in the `coverage` array indicate how many times the corresponding
`source` line has been executed. `null` values represent lines that do not
contain executable statements.

Usage
-----
Clone this repo, then copy or symlink a file in the above format to
`jscoverage.json` in the project directory.

License
-------
GPL v2

[jscov]: http://siliconforks.com/jscoverage/
