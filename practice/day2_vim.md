
目标
  掌握相关命令

- 行首
     0:跳至行首
    ^：到本行第一个不是black行首的位置(改键为：H)
- 行尾 
  $：到行尾
  g_：到本行第一个不是black的行尾位置(改键为：L)

- 插入
  行首：I
  行尾：A
  行前：O
  行后：o


- 复制
    复制当前行：yy
- 粘贴
    粘贴：p
- 删除
    删除当前行：dd


- 改键
  normal模式快速进入行首和行未
  "vim.normalModeKeyBindings": [
      { // 行首
          "before": ["H"],
          "after": ["^"]
      },
      { // 行未 
          "before": ["L"],
          "after": ["g", "_"]
      }
  ]




- 练习
> 训练H移动到行首、L移动到行尾
> 训练yy复制、p粘贴、dd删除
> 训练i光标前面插入、I行首插入、a光标后面插入、A行尾插入

```js
const a = 1;
const b = 2;
const b = 2;
const c = 3;
const d = 4;
```