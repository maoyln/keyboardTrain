## 目标：
  掌握多文件之间的跳转
## 任务点：
### 定位
   - 标记
      单文件: m+小写字母，推荐mm;
      多文件：m+大写字母，推荐mM;
   - 跳转
      ' : 跳转到标记行;
      ` : 跳转到标记行和列(更精准，但是组合键不方便操作，使用比较少);
### jump to definition
   - gd:
      - 光标位于函数调用的地方，按`gd`光标会跳转至函数定义的地方;
      - 光标位于函数定义的地方;
         如果只有一处调用，按`gd`会跳转到调用的地方;
         如果有多处调用，按`gd`会弹出调用列表【文件列表和调用函数列表的树结构】;
            此时按键作用：;
              `j`：下移;
              `k`：上移；
              `h`：光标回到文件夹[一个文件中使用了多个该函数]、或收起展开状态;
              `l`: 展开文件夹、或进入该函数;
   - 变量、函数等有引用关系的都符合上面跳转规则;

### 跳转
   - 任何大于一个单词或超过当前行导航的移动都是一个跳转    
    如：
      '：  跳转到标记行;
      `：  跳转到标记位置（行和列）;
      gg： 跳转到首行;
      /：  向后搜索;
      ?：  向前搜索;
      n：  重复上一次搜索，相同方向;
      N：  重复上一次搜索，相反方向;
      gd： 搜索使用函数;
      {：  跳转到上一个段落;
      }：  跳转到下一个段落;

    不会记录的命令：
      C + b
      C + f
      C + d
      C + e
      J
      K
    vim-sneak: 查找并使用 ; 跳转多次后，C - o 只会回到初始位置

### 跳转命令：
  `C`(control) + `o`: 向前跳
  `C`(control) + `i`: 向后跳

  - 常用场景：
    查看代码，`gd` 到定义处查看详情，`C+o` 跳转回来；
    打开一个新文件，`C+o` 跳转回来，`C+i` 再跳转过去

> vim 保留了移动前位置的记录，使用 `:jumps` 查看历史跳转，不常用
  


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