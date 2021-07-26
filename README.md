This repository contains debian packages I built using [Nfpm](https://github.com/goreleaser/nfpm) on an Ubuntu 20.04 machine.

Most often I simply repackaged the published tarballs ; some packages needed compilation.

This is intended for personal use, and meant to be temporary replacements for upstream/official packages.

## List of packages in this repository

**Third-party programs**

|  |  |
|--|--|
| [Alacritty](https://github.com/alacritty/alacritty) | A cross-platform, GPU-accelerated terminal emulator |
| [Amber](https://github.com/dalance/amber) | A code search / replace tool written in Rust |
| [Bottom](https://github.com/ClementTsang/bottom) | Yet another cross-platform graphical process/system monitor. Written in Rust |
| [Dasel](https://github.com/TomWright/dasel) | Query and update data structures from the command line. Comparable to jq/yq but supports JSON, TOML, YAML, XML and CSV with zero runtime dependencies. |
| [Dua](https://github.com/Byron/dua-cli) | View disk space usage and delete unwanted data, fast. Written in Rust. |
| [Enquirer](https://github.com/termapps/enquirer) | Command line utility for stylish interactive prompts. Written in Rust. |
| [Entangled](https://github.com/entangled/entangled) | Bi-directional tangle daemon for literate programming. |
| [Featmap](https://github.com/amborle/featmap) | The simple and open source user story mapping tool. |
| [Ferret](https://www.montferret.dev) | Declarative web scraping. |
| [Fzf](https://github.com/dalance/fzf) | A command-line fuzzy finder. |
| [Just](https://github.com/casey/just) | Just a command runner. Written in Rust. |
| [Miller](https://github.com/johnkerl/miller) | Miller is like awk, sed, cut, join, and sort for name-indexed data such as CSV, TSV, and tabular JSON. |
| []() | . |

## Other programs in my toolbox that are already packaged as deb

|  |  |  |
|--|--|--|
| [Fd](https://github.com/sharkdp/fd) | A simple, fast and user-friendly alternative to 'find', written in Rust. | [v8.2.1](https://github.com/sharkdp/fd/releases/download/v8.2.1/fd_8.2.1_amd64.deb) |


## TODO

- [ ] xh: add symlink to `xhs` ([rationale](https://github.com/ducaale/xh#shorthand-form-for-urls))
- [ ] Ferret: the original project has been split (see https://github.com/MontFerret/ferret/issues/266). A bit confusing for me.
