<!-- PROJECT BADGES -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->
[![Github Link][github badge]][github link]
[![CI Status][ci badge]][ci link]

<!-- PROJECT LOGO -->
<p align="center">
  <img src="pikuseru.png">
</p>

<!-- ABOUT THE PROJECT -->
# Pikuseru Console 

[![LICENSE](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/PikuseruConsole/pikuseru-editor/blob/master/LICENSE.md)

 
## Examples


## Build

Cargo feature:
  * cpython: enable python support
  * rlua: enable lua support

You can build the editor directly the main UI to play games:
```
cd pikuseru-editor
cargo build --release --features=pikuseru/cpython,pikuseru/rlua,pikuseru/image
```

[github badge]: https://img.shields.io/badge/github-pikuseruconsole/pikuserueditor-8da0cb?style=for-the-badge&logo=github
[github link]: https://github.com/PikuseruConsole/pikuseru-editor
[ci link]: https://github.com/PikuseruConsole/pikuseru-editor/actions
[ci badge]: https://img.shields.io/github/actions/workflow/status/PikuseruConsole/pikuseru-editor/rust.yml?branch=main&style=for-the-badge&logo=github-actions&logoColor=white
