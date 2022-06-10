

vim 语法
  操作符（operation）+ 动作（区域范围）


操作
  删除 d
  删除并进入insert模式  c
  复制 y

注意：d和c 删除后的内容也会放在寄存器里，也可用p进行粘贴


基于单词/字符串的移动
  e-移动单词的结尾
  b-移动到上个单词的开头
  w-移动到单词的开头
  ge-移动到上一个单词的结尾
  
组合
  ea-在当前单词的结尾处添加
  bi-在当前单词的开始出添加
  
  de-删除当前光标到单词结尾
  dl-删除右边一个字符
  dL-删除右边所有字符 （需要配置）
  dh-删除左边一个字符
  dH-删除左边所有字符
  dj-删除当前行和下一行
  dk-删除当前行和上一行

把上述d换成c操作一样，操作之后进入insert模式
  ce-删除当前光标到单词结尾-并进入insert模式
  cw-删除当前单词(删除光标及之后的单词)
  cl-删除右边一个字符,并进入insert模式
  cL-删除右边所有字符 .并进入insert模式（需要配置）
  ch-删除左边一个字符,并进入insert模式
  cH-删除左边所有字符,并进入insert模式
  cj-删除当前行和下一行,并进入insert模式
  ck-删除当前行和上一行,并进入insert模式

把上述d换成c操作一样，操作之后进入insert模式
  ye-复制当前光标到单词结尾
  yw-复制当前单词(删除光标及之后的单词)
  yl-复制右边一个字符
  yL-复制右边所有字符
  yh-复制左边一个字符
  yH-复制左边所有字符
  yj-复制当前行和下一行
  yk-复制当前行和上一行



- 改键


- 练习

```js
/**
 * 添加
 */
const insertvwComp = (name, age) => {
   fdasdni   
}asd
sd
fdasd fasdfasd
dasd asdcfdasd fasdfasd
de 
denihapdasd asdfl allcsdf asdfce 

12c231c23 -12
123123 -12a
123123 -b

you‘re good man
```