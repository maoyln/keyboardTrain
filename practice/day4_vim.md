

目标：
 更有效的处理单字符串&undo/redo

normal模式操作
 x：删除光标所在字符
 X：删除光标前的字符
 s：删除当前光标的字符，并进入insert模式
 S：删除当前光标标所在行并进入insert模式
 r：替换一个字符
 R：替换多个字符

 undo/redo
   u:【undo】撤销 (跟insert中command+z类似)
   C-r:【ctrl+r】redo重做、恢复（跟insert模式中command+Z类似）

  可撤销块：进入插入模式开始，直到返回普通模式为止，在此期间输入或者删除的任何内容都被当一次修改

- 改键




- 练习

```js
/**
 * 添加
 */
const insertvwComp = () => {
abcdefghijklmnopqrstuvwxyz
abcdefghijklmnopqrstuvwxyz
abcdefghijklmnopqrstuvwxyz
abcdefghijklmnopqrstuvwxyz
abcdefghijklmnopqrstuvwxyz
abcdefghijklmnopqrstuvwxyz
abcdefghijklmnopqrstuvwxyz
abcdefghijklmnopqrstuvwxyz
abcdefghijklmnopqrstuvwxyz

abcdefghijklmnopqrstuvwxyz
abcdefghijklmnopqrstuvwxyz
}asr
sd
sd
sdSasedg
nighasd
dasd asdfssd fasdLfasd
12c231c23 -12
123123 -12a
123123 -b
function testFor () {
  fssd 
}
function a () {
  arwqrqefssd
}
```
