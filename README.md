# File Browser

TODO:

- [x] 输入..自动到上一层目录
- [ ] 路径显示为相对路径，而非绝对路径
- [x] CTRL + W 退一个单词: 设置快捷键即可: CTRL + W 到上层目录
- [ ] 匹配字体红色高亮红色
- [x] 不显示 Open as a new file(Array 模糊匹配问题)
- [x] 修复 tab 键匹配时，如果为文件夹时，填充两次文件夹的问题

An integrated, keyboard driven file selector for VS Code, inspired by Emacs's
[Helm](https://emacs-helm.github.io/helm/) file selector.

![screenshot](images/file-browser.gif)

## Features

This is what this extension gives you:

- A fully keyboard driven file open dialog: bind `file-browser.open` to `Ctrl+O` (or `C-x C-f` if
  you're an Emacs expat) and enjoy the lack of OS file dialog clutter.
- Start typing a file name to quickly find it in the current folder. Use `Tab` to autocomplete.
- Automatically create files and folders just by typing their names and selecting the option that
  appears.
- Easy navigation in and out of folders by using the left and right arrow keys.
- Navigate to your home folder by typing `~/` into the search box, or step up to the parent folder
  by typing `../`.
- Perform file operations like rename and delete by stepping into a file with the right arrow key,
  or by hitting `Ctrl+A` on any file or folder.

## Licence

Copyright 2020 Bodil Stokke

This program is free software: you can redistribute it and/or modify it under the terms of the GNU
Lesser General Public License as published by the Free Software Foundation, either version 3 of the
License, or (at your option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without
even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU
General Public License for more details.

You should have received a copy of the GNU Lesser General Public License along with this program. If
not, see <https://www.gnu.org/licenses/>.

## Code of Conduct

Please note that this project is released with a [Contributor Code of Conduct][coc]. By
participating in this project you agree to abide by its terms.

[coc]: https://github.com/bodil/vscode-file-browser/blob/master/CODE_OF_CONDUCT.md
