目标：
  在vscode安装vim插件

在vscode安装了vim插件

  [安装 Vim](vscode:extension/vscodevim.vim)

- 学到了vim中的 `normal`模式和`insert`模式的区别及操作
    normal模式下移动光标：h:右；j：下；k：上；l：左；
    进入normal模式：按键：esc 或者 control+'['组合

- 退出normal模式：
    按键`i`：退出`normal`模式进入`insert`模式，且光标留在当前字母的后面 ；
    按键`a`：退出`normal`模式进入`insert`模式，且光标留在当前字母的前面 ；

- 练习了在终端操作vim：操作步骤
    `vim 01vim.md` 即可打开或者创建一个`01vim.md`文件，并且进入`normal`模式
    按`a`或者`i`进入`insert`模式，然后编辑文件
    进入`normal`模式，输入`:wq`退出编辑并保持，`:!q`：不保存并强制退出

- `nomal`模式下 hjkl按键移动光标移动速度配置
    默认情况下，长按 `hjkl` 光标不会持续移动，只会移动一次，我们可以通过一下配置来实现长按快速移动
    [VSCodeVim/Vim: Vim for Visual Studio Code](https://github.com/VSCodeVim/Vim#mac)
    在终端中输入以下命令：

  ```
    $ defaults write com.microsoft.VSCode ApplePressAndHoldEnabled -bool false              # For VS Code
    $ defaults write com.microsoft.VSCodeInsiders ApplePressAndHoldEnabled -bool false      # For VS Code Insider
    $ defaults write com.visualstudio.code.oss ApplePressAndHoldEnabled -bool false         # For VS Codium
    $ defaults write com.microsoft.VSCodeExploration ApplePressAndHoldEnabled -bool false   # For VS Codium Exploration users
    $ defaults delete -g ApplePressAndHoldEnabled                                           # If necessary, reset global default
  ```
  `mac` 系统设置-键盘，将 `按键重复` 调到最快，将 `重复前延迟` 调到最短

  重启 `vscode` 即可




- 改键

- 练习

> 训练h、j、k、l移动方向

```js
const a = 1;
const b = 2;
const c = 3;
// 修改成 然后在改回来，反复训练多次, 训练h、j、k、l移动方向
const d = 4;
const e = 5;
const f = 6;
```
