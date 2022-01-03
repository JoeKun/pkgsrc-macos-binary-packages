# List of binary packages

These binary packages for `pkgsrc` were built for macOS, either with a patch that improves the already packaged tool, or as brand new packages not yet available in Joyent's `pkgsrc` binary repository.

| Package name | File name | Description |
| ---- | --------- | ----------- |
| `figlet` | `figlet-2.2.5nb2.tgz` | [Small improvement](https://github.com/JoeKun/macos-configuration/blob/master/patches/pkgsrc/figlet_pkgsrc_tweak-for-macOS-to-detect-terminal-width.patch) to enable the build option that allows figlet to detect the width of the Terminal window, thus allowing better centering behavior. |
| `vimpager` | `vimpager-2.06nb1.tgz` | [Modified package](https://github.com/JoeKun/macos-configuration/blob/master/patches/pkgsrc/vimpager_pkgsrc_upgrade-to-2.06-and-backport-from-unreleased-HEAD-fix-for-latest-vim-releases.patch) of the latest version of `vimpager`, with an important patch from the HEAD of the repository which has yet to be released with a new tag, that fixes a nasty bug with latest versions of `vim`. |
| `diff-so-fancy` | `diff-so-fancy-1.2.7nb1.tgz` | [New package](https://github.com/JoeKun/macos-configuration/blob/master/patches/pkgsrc/diff-so-fancy_pkgsrc.patch) of `diff-so-fancy` command line tool. |
| `py-mdv3` | `py39-mdv3-2.0.2.tgz` | [New package](https://github.com/JoeKun/macos-configuration/blob/master/patches/pkgsrc/py-mdv3_pkgsrc.patch) of Terminal Markdown Viewer, built for Python 3.9 interpreter. |
