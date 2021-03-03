Commands V2 Hatchbot example with repl.it


### Notes
1. repl.it supports pyproject.toml files and uses poetry to manage dependencies. However, the version of poetry on repl uses pip <21, meaning that the manylinux wheels are not used. We use .replit as workaround.
2. repl.it uses upm to guess and automatically install packages that are imported in files. Due to the previous note, we have to opt out of this behavior for robotpy packages.

