# List of binary packages

These binary packages for `pkgsrc` were built for macOS, either with a patch that improves the already packaged tool, or as brand new packages not yet available in Joyent's `pkgsrc` binary repository.

 - `figlet-2.2.5nb2.tgz`: incremental improvement over `figlet-2.2.5nb1` that enables the build option to allow `figlet` to detect the width of the Terminal window, thus allowing better centering behavior.
 - `vimpager-2.06nb1.tgz`: package of the latest version of `vimpager`, with an important patch from the HEAD of the repository which has yet to be released with a new tag, that fixes a nasty bug with latest versions of `vim`.
 - `diff-so-fancy-1.2.5.tgz`: package of `diff-so-fancy` command line tool.
 - `py27-mdv-1.6.3.tgz`: package of `mdv` Markdown viewer built for Python 2.7 interpreter.
 - `py27-pygments-2.3.1.tgz`: package of required dependency of `py27-mdv-1.6.3.tgz` that is not yet present with that version number in Joyent's `pkgsrc` binary repository.