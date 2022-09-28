# List of binary packages

These binary packages for `pkgsrc` were built for macOS, either with a patch that improves the already packaged tool, or as brand new packages not yet available in Joyent's `pkgsrc` binary repository.

| Package name | File name | Description |
| ---- | --------- | ----------- |
| `figlet` | `figlet-2.2.5nb2.tgz` | [Small improvement](https://github.com/JoeKun/macos-configuration/blob/main/patches/pkgsrc/figlet_pkgsrc_tweak-for-macOS-to-detect-terminal-width.patch) to enable the build option that allows figlet to detect the width of the Terminal window, thus allowing better centering behavior. |
| `vimpager` | `vimpager-2.07-alpha-1.tgz` | [Unreleased version](https://github.com/JoeKun/macos-configuration/blob/main/patches/pkgsrc/vimpager_pkgsrc_upgrade-to-2.07-alpha-1.patch) of `vimpager`, with an important fixes for nasty bugs with latest versions of `vim`. |
| `diff-so-fancy` | `diff-so-fancy-1.2.7nb1.tgz` | [New package](https://github.com/JoeKun/macos-configuration/blob/main/patches/pkgsrc/diff-so-fancy_pkgsrc.patch) of `diff-so-fancy` command line tool. |
| `py-mdv3` | `py310-mdv3-2.0.2.tgz` | [New package](https://github.com/JoeKun/macos-configuration/blob/main/patches/pkgsrc/py-mdv3_pkgsrc.patch) of Terminal Markdown Viewer, built for Python 3.10 interpreter. |
