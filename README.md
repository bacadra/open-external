# open-external

<p align="center">
  <a href="https://github.com/bacadra/atom-open-external/tags">
  <img src="https://img.shields.io/github/v/tag/bacadra/atom-open-external?style=for-the-badge&label=Latest&color=blue" alt="Latest">
  </a>
  <a href="https://github.com/bacadra/atom-open-external/issues">
  <img src="https://img.shields.io/github/issues-raw/bacadra/atom-open-external?style=for-the-badge&color=blue" alt="OpenIssues">
  </a>
  <a href="https://github.com/bacadra/atom-open-external/blob/master/package.json">
  <img src="https://img.shields.io/github/languages/top/bacadra/atom-open-external?style=for-the-badge&color=blue" alt="Language">
  </a>
  <a href="https://github.com/bacadra/atom-open-external/blob/master/LICENSE">
  <img src="https://img.shields.io/github/license/bacadra/atom-open-external?style=for-the-badge&color=blue" alt="Licence">
  </a>
</p>

![open-external](https://github.com/bacadra/atom-open-external/raw/master/assets/open-external.png)

![tree-view-external](https://github.com/bacadra/atom-open-external/raw/master/assets/tree-view-external.png)

Many files cannot be displayed in human-readable form and the corresponding Atom editor plugins do not exist. In this case, the most convenient way of exploring it is to open it in an external program.

## Installation

### Atom Text Editor

The official Atom packages store has been disabled. To get latest version run the shell command

    apm install bacadra/atom-open-external

and obtain the package directly from Github repository.

### Pulsar Text Editor

The package has compability with [Pulsar](https://pulsar-edit.dev/) and can be install

    pulsar -p install bacadra/atom-open-external

or directly [open-external](https://web.pulsar-edit.dev/packages/open-external) from Pulsar package store.

## Usage

In `atom-workspace` space there are available commands:

* `open-external:toggle-unsupported-flag`: (default `Alt-U`) quick switch of external opener state

In `atom-text-editor` and `.image-view` spaces there are available commands:

* `open-external:open-external`: (default `Alt-F12`) open active file external
* `open-external:show-in-folder`: (defualt `Ctrl-F12`) show active file in system default file manager

In `.platform-win32 .image-view` space there are available commands:

* `open-external:edit-in-paint`: open image in paint editor

In `.tree-view` space there are available commands:

* `open-external:open-external`: (default `Alt-F12`) open active item external
* `open-external:show-in-folder`: (default `Ctrl-F12`) show active item in system default file manager

In `atom-text-editor[data-grammar~="latex"]` space there are available commands:

* `open-external:open-TeX-PDF-internal`: open `.pdf` file associated with`.tex` file
* `open-external:open-TeX-PDF-external`: open `.pdf` file associated with`.tex` file external

# Contributing

If you have ideas on how to improve the package, see bugs or want to support new features - feel free to share it via GitHub.

See my other packages for Atom & Pulsar Text Editors:
<p align="center">
<a href="https://github.com/bacadra/atom-autocomplete-sofistik"><img src="https://img.shields.io/github/v/tag/bacadra/atom-autocomplete-sofistik?style=for-the-badge&label=autocomplete-sofistik&color=blue" alt="autocomplete-sofistik">
<a href="https://github.com/bacadra/atom-bib-finder"><img src="https://img.shields.io/github/v/tag/bacadra/atom-bib-finder?style=for-the-badge&label=bib-finder&color=blue" alt="bib-finder">
<a href="https://github.com/bacadra/atom-hydrogen-run"><img src="https://img.shields.io/github/v/tag/bacadra/atom-hydrogen-run?style=for-the-badge&label=hydrogen-run&color=blue" alt="hydrogen-run">
<a href="https://github.com/bacadra/atom-image-paste"><img src="https://img.shields.io/github/v/tag/bacadra/atom-image-paste?style=for-the-badge&label=image-paste&color=blue" alt="image-paste">
<a href="https://github.com/bacadra/atom-language-sofistik"><img src="https://img.shields.io/github/v/tag/bacadra/atom-language-sofistik?style=for-the-badge&label=language-sofistik&color=blue" alt="language-sofistik">
<a href="https://github.com/bacadra/atom-linter-ruff"><img src="https://img.shields.io/github/v/tag/bacadra/atom-linter-ruff?style=for-the-badge&label=linter-ruff&color=blue" alt="linter-ruff">
<a href="https://github.com/bacadra/atom-navigation-panel"><img src="https://img.shields.io/github/v/tag/bacadra/atom-navigation-panel?style=for-the-badge&label=navigation-panel&color=blue" alt="navigation-panel">
<a href="https://github.com/bacadra/atom-open-external"><img src="https://img.shields.io/github/v/tag/bacadra/atom-open-external?style=for-the-badge&label=open-external&color=blue" alt="open-external">
<a href="https://github.com/bacadra/atom-pdf-viewer"><img src="https://img.shields.io/github/v/tag/bacadra/atom-pdf-viewer?style=for-the-badge&label=pdf-viewer&color=blue" alt="pdf-viewer">
<a href="https://github.com/bacadra/atom-project-files"><img src="https://img.shields.io/github/v/tag/bacadra/atom-project-files?style=for-the-badge&label=project-files&color=blue" alt="project-files">
<a href="https://github.com/bacadra/atom-regex-aligner"><img src="https://img.shields.io/github/v/tag/bacadra/atom-regex-aligner?style=for-the-badge&label=regex-aligner&color=blue" alt="regex-aligner">
<a href="https://github.com/bacadra/atom-sofistik-tools"><img src="https://img.shields.io/github/v/tag/bacadra/atom-sofistik-tools?style=for-the-badge&label=sofistik-tools&color=blue" alt="sofistik-tools">
<a href="https://github.com/bacadra/atom-super-select"><img src="https://img.shields.io/github/v/tag/bacadra/atom-super-select?style=for-the-badge&label=super-select&color=blue" alt="super-select">
<a href="https://github.com/bacadra/atom-word-map"><img src="https://img.shields.io/github/v/tag/bacadra/atom-word-map?style=for-the-badge&label=word-map&color=blue" alt="word-map">
</p>
