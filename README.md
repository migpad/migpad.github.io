# migpad.com

The site of [MigPad](https://github.com/migpad/migpad), a fast text editor for macOS, Linux and Windows: one page, in English (`index.html`) and Russian (`ru/index.html`), served by GitHub Pages at [migpad.com](https://migpad.com).

Plain HTML and CSS, nothing to build: no frameworks, fonts, counters or anything else loaded from other sites, as MigPad itself never goes online. The download links point to the files of the latest release of MigPad on GitHub, whose names do not change from version to version. The only script picks the Russian page for a browser in Russian.

To look at it, serve the folder: `python3 -m http.server`, then open http://localhost:8000.
