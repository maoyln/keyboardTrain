
目标
  插入

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
     aAasdfsafasadf  sda     O  
asdfasdfasdf
行前
asdfsdafasdz[““]a   
行后yy
aaaa[]z[{}]
aaaa[]z[{}]
aaa   a[] .  z[{}]
aaaa[]z[{}]
aaa   a[] .  z[{}]
  a_sdf   adsad    `[[[[[[]]]]]]`       
aaa[]z[{}]
kaaaa[]z[{}]
aaaa[]z[{}]
bsdnqweeeasdf909123123
dasdasdj
dasdasdj
jdasdfasddd