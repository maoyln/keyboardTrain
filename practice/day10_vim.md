## 目标：
  认识数字&点的威力
## 任务点：

1. 数字

  语法：
    数字 + operation + 动作（范围）
    operation + 数字 + 动作（范围）

  例：删除三个单词：`3dw` 或者 `d3w`
    优点：保持了连贯的撤销历史记录
    痛点：需要有思考的时间

1. 点
  功能：重复上一次的修改【增、删、改】

    例：使用`.`记忆删除单词的最优方式（记住核心tips）:
      bde: 先移动到单词开头，再删除到单词结尾【`de`是一次修改，顾被`.`记忆，`b`仅仅做了移动，不会被记忆，`.`无法删除单词】
      dbx: 先删除到单词结尾（除最后一个字符），再删除最后一个字符【`.`只会重复`x`命令（修改命令），`.`无法删除单词】
      diw: 利用文本对象内部（i）选中单词，删除 【这就是一次修改的命令，所以 `.` 是可以删除单词的】
    tips： 1. `.`在normal 模式只记录最后一次的修改；
          2. `.`会记忆离开 insert 模式之前的所有按键操作都记录

  核心：一键移动，一键操作
    例1: 给每行尾加分号
      less well
        先执行 `La;`: 移动到行尾改成编辑模式，输入`;` 
        后面在每一行尾添加`;`,就是使用`j/k`(移动) + `.`（操作）
        存在问题： `.` 重复的是 `a;` 【因为`.`只会记忆最后的修改操作`a;`】;
      
      well
        使用 `A;`，就解决了上述问题

    例2: 手动多次查找替换
      使用 `/` 全局搜索要替换的字符，使用 `cw + 替换的字符` 完成替换操作
      后面替换操作就是：使用`n` 查找字符，再使用`.`执行替换操作【一键移动一键操作】

  tips：重复操作用`.`进行操作，不实用数字【规避了上述使用数字的痛点】


- 练习

```js
/**
 * 添加
 */
const insertvwComp = (name, age) => {
fdasdddd
afdasdddd
diiidddasdddd
}
function testFor (name, age) {
  console.log(name)
}
function aTest (_a) {
  const b = _a 
}
 

obg['12']

const a = <d></d>
/**
 * 添加
 */
const insertvwComp = (name, age) => {
fdasdddd
afdasdddd
ddddasdddd
}
function testFor (name, age) {
  console.log(name)
}
function aTest (_a) {
  const b = _a 
}
 

obg['12']

const a = <d></d>
/**
 * 添加
 */
const insertvwComp = (name, age) => {
fdasdddd
afdasdddd
ddddasdddd
}
function testFor (name, age) {
  console.log(name)
}
function aTest (_a) {
  const b = _a 
}
 

obg['12']

const a = <d></d>
/**
 * 添加
 */
const insertvwComp = (name, age) => {
fdasdddd
afdasdddd
ddddasdddd
}
function testFor (name, age) {
  console.log(name)
}
function aTest (_a) {
  const b = _a 
}
 

obg['12']

const a = <d></d>
/**
 * 添加
 */
const insertvwComp = (name, age) => {
fdasdddd
afdasdddd
ddddasdddd
}
function testFor (name, age) {
  console.log(name)
}
function aTest (_a) {
  const b = _a 
}
 

obg['12']

const a = <d></d>
/**
 * 添加
 */
const insertvwComp = (name, age) => {
fdasdddd
afdasdddd
ddddasdddd
}
function testFor (name, age) {
  console.log(name)
}
function aTest (_a) {
  const b = _a 
}
 

obg['12']

const a = <d></d>
/**
 * 添加
 */
const insertvwComp = (name, age) => {
fdasdddd
afdasdddd
ddddasdddd
}
function testFor (name, age) {
  console.log(name)
}
function aTest (_a) {
  const b = _a 
}
 

obg['12']

const a = <d></d>
/**
 * 添加
 */
const insertvwComp = (name, age) => {
fdasdddd
afdasdddd
ddddasdddd
}
function testFor (name, age) {
  console.log(name)
}
function aTest (_a) {
  const b = _a 
}
 

obg['12']

const a = <d></d>
/**
 * 添加
 */
const insertvwComp = (name, age) => {
fdasdddd
afdasdddd
ddddasdddd
}
function testFor (name, age) {
  console.log(name)
}
function aTest (_a) {
  const b = _a 
}
 

obg['12']

const a = <d></d>
/**
 * 添加
 */
const insertvwComp = (name, age) => {
fdasdddd
afdasdddd
ddddasdddd
}
function testFor (name, age) {
  console.log(name)
}
function aTest (_a) {
  const b = _a 
}
 

obg['12']

const a = <d></d>
/**
 * 添加
 */
const insertvwComp = (name, age) => {
fdasdddd
afdasdddd
ddddasdddd
}
function testFor (name, age) {
  console.log(name)
}
function aTest (_a) {
  const b = _a 
}
 

obg['12']

const a = <d></d>
/**
 * 添加
 */
const insertvwComp = (name, age) => {
fdasdddd
afdasdddd
ddddasdddd
}
function testFor (name, age) {
  console.log(name)
}
function aTest (_a) {
  const b = _a 
}
 

obg['12']

const a = <d></d>
/**
 * 添加
 */
const insertvwComp = (name, age) => {
fdasdddd
afdasdddd
ddddasdddd
}
function testFor (name, age) {
  console.log(name)
}
function aTest (_a) {
  const b = _a 
}
 

obg['12']

const a = <d></d>

```