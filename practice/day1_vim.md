目标：
  在vscode安装vim插件

在vscode安装了vim插件

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
  ```
    $ defaults write com.microsoft.VSCode ApplePressAndHoldEnabled -bool false              # For VS Code
    $ defaults write com.microsoft.VSCodeInsiders ApplePressAndHoldEnabled -bool false      # For VS Code Insider
    $ defaults write com.visualstudio.code.oss ApplePressAndHoldEnabled -bool false         # For VS Codium
    $ defaults write com.microsoft.VSCodeExploration ApplePressAndHoldEnabled -bool false   # For VS Codium Exploration users
    $ defaults delete -g ApplePressAndHoldEnabled                                           # If necessary, reset global default
  ```




- 改键

- 练习
asdfsafasadf
asdfasdfsdfasdf
asdfsdafasdz[““]a   
```js
const aa = 1;
const b = 2;

```
aaaa[]z[{}]
aaaa[]z[{}]
aaaa[]z[{}]
  a_sdf   adsad    `[[[[[[]]]]]]`       
aaa[]z[{}]
aaaa[]z[{}]
aaaa[]z[{}]