# Syntax Highlight Theme

[![marketplace-image]][marketplace-url] [![appveyor-image]][appveyor-url] [![GitHub-image]][github-url] [![license-image]][license-url]
[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Fpeaceshi%2FSyntax-Highlight-Theme.svg?type=shield)](https://app.fossa.com/projects/git%2Bgithub.com%2Fpeaceshi%2FSyntax-Highlight-Theme?ref=badge_shield)

[![Codacy Badge image]][codacy badge url] [![CodeFactor-image]][codefactor-url] [![GitHub Workflow Status]][github workflow url]

[marketplace-image]: https://img.shields.io/vscode-marketplace/v/peaceshi.syntax-highlight.svg?style=flat&logo=visual-studio-code&label=marketplace&color=007ACC
[marketplace-url]: https://marketplace.visualstudio.com/items?itemName=peaceshi.syntax-highlight
[appveyor-image]: https://img.shields.io/appveyor/ci/peaceshi/syntax-highlight-theme.svg?style=flat&logo=appveyor&logoColor=FFFFFF&label=main
[appveyor-url]: https://ci.appveyor.com/project/peaceshi/syntax-highlight-theme/
[github-image]: https://img.shields.io/badge/GitHub-issues-red.svg?logo=Github
[github-url]: https://github.com/peaceshi/Syntax-highlight-Theme/issues
[license-image]: https://img.shields.io/github/license/peaceshi/Syntax-highlight-Theme.svg
[license-url]: https://github.com/peaceshi/Syntax-highlight-Theme/blob/main/LICENSE
[codacy badge image]: https://img.shields.io/codacy/grade/62132740f27e405eb54e0ca6e2bf58f0?label=CodacyGrade&logo=Codacy
[codacy badge url]: https://www.codacy.com/manual/peaceshi/Syntax-Highlight-Theme?utm_source=github.com&utm_medium=referral&utm_content=peaceshi/Syntax-Highlight-Theme&utm_campaign=Badge_Grad
[codefactor-image]: https://img.shields.io/codefactor/grade/github/peaceshi/syntax-highlight-theme/main?label=CodeFactor&logo=CodeFactor&logoColor=FFFFFF
[codefactor-url]: https://www.codefactor.io/repository/github/peaceshi/syntax-highlight-theme/overview/main
[github workflow status]: https://img.shields.io/github/workflow/status/peaceshi/Syntax-Highlight-Theme/build?label=Act
[github workflow url]: https://github.com/peaceshi/Syntax-Highlight-Theme/actions
[hard]: https://img.shields.io/badge/-Hard-red.svg
[normal]: https://img.shields.io/badge/-Normal-blue.svg
[easy]: https://img.shields.io/badge/-Easy-green.svg
[high]: https://img.shields.io/badge/-High--Priority-important.svg
[medium]: https://img.shields.io/badge/-Medium--Priority-brightgreen.svg
[low]: https://img.shields.io/badge/-Low--Priority-inactive.svg

## About Syntax Highlight Theme

**2024-11-9: This theme is now working for a new version.**

**This readme maybe outdated, please refer to the [repository](https://github.com/peaceshi/Syntax-Highlight-Theme/tree/main) for more information.**

---

**For some reason(such as italic and font weights needed), I recommends using** [Iosevka](https://github.com/be5invis/Iosevka) **or** [Sarasa-Gothic(for CJK)](https://github.com/be5invis/Sarasa-Gothic) **font with this theme.**

**Now you can choose a beta test theme `Syntax Material Dark Level 1 (beta)`directly. It supports most languages that VSCode supports now.**

If you do not like italic or weights, just disable it in your settings easily.

This is theme highlight supports, **not** parsers now.

## Job schedules

|     Level      |    1    |     2     |    3    |
| :------------: | :-----: | :-------: | :-----: |
| **Difficulty** | ![easy] | ![normal] | ![hard] |
|  **Priority**  | ![Low]  | ![Medium] | ![High] |

[inlay hints]: https://www.jetbrains.com/help/resharper/Inline_Parameter_Name_Hints.html
[multiple selections]: https://code.visualstudio.com/docs/editor/codebasics#_multiple-selections-multicursor

- **TODO**
  - [ ] Modern code IntelliSense and editor enhancement.
    - [ ] ![hard] ![High] Reshaper [inlay hints].
    - [ ] ![normal] ![Medium] Hover help in the editor for editor keyboard shortcuts and [multiple selections].
  - [ ] ![normal] ![Low] Make a tool to change theme colors more easily.
  - [ ] ![easy] ![Low] Design a new extension icon.
  - [ ] ![hard] ![Medium] Write documents for this responsory.
- **Working**
  - [x] ![normal] ![High] Add more language supports. **Beta test now!**.
  - [ ] ![hard] ![Medium] Make sure behavioral consistency for supported languages.
- **Finished**
  - [x] The language scopes generate tool. See `/tools/`.
    - [x] ![easy] Make a general file to support most languages. See `/language_tags/`.

## Additional install

[better c++ syntax]: https://marketplace.visualstudio.com/items?itemName=jeff-hykin.better-cpp-syntax
[lua-language-server]: https://marketplace.visualstudio.com/items?itemName=sumneko.lua
[microsoft c/c++]: https://marketplace.visualstudio.com/items?itemName=ms-vscode.cpptools
[enhanced colorization]: https://code.visualstudio.com/docs/cpp/colorization-cpp

- [Better C++ Syntax] for full **cpp** and its supports.
- [lua-language-server] for more **lua** support.
- (Optional,buggy now) [Microsoft C/C++] , then set `"C_Cpp.enhancedColorization": "Enabled",` and `IntelliSense enabled` to use [Enhanced colorization].

Then use this theme, enjoy!

## What's new

See [CHANGELOG](https://github.com/peaceshi/Syntax-highlight-Theme/blob/main/CHANGELOG.md)

## Snapshot (New)

[markdown]: https://github.com/peaceshi/Syntax-highlight-Theme/blob/main/docs/markdown.md
[c++]: https://github.com/peaceshi/Syntax-highlight-Theme/blob/main/docs/cpp.cpp
[python]: https://github.com/peaceshi/Syntax-highlight-Theme/blob/main/docs/python.py

|         [Markdown]          |
| :-------------------------: |
| ![01.png](./img/md_01.png)  |
|            [C++]            |
| ![01.png](./img/cpp_01.png) |
|          [Python]           |
| ![01.png](./img/py_01.png)  |

## Snapshot (Old)

|         **C++**         |                         |
| :---------------------: | :---------------------: |
| ![01.png](./img/01.png) | ![02.png](./img/02.png) |
|          **C**          |      **Markdown**       |
| ![03.png](./img/03.png) | ![04.png](./img/04.png) |
|       **Python**        |                         |
| ![05.png](./img/05.png) | ![06.png](./img/06.png) |
|         **Lua**         |
| ![07.png](./img/07.png) |


## License
[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Fpeaceshi%2FSyntax-Highlight-Theme.svg?type=large)](https://app.fossa.com/projects/git%2Bgithub.com%2Fpeaceshi%2FSyntax-Highlight-Theme?ref=badge_large)