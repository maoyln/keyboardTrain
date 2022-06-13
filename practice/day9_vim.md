## 目标：
  更高效的移动-想去哪里就去哪里
## 任务点：
  1. vim-easymotion
    配置：
      ```json
        "vim.easymotion": true, // 开启easymotion（默认为false）
        "vim.leader": "<Space>", // 修改<leader>键为<Space>键
      ```
    基本命令
      `<Space> <Space> e`: 移动到单词结尾 (选择范围在光标下方) 
      `<Space> <Space> w`: 移动到单词开头 (选择范围在光标下方)  
      `<Space> <Space> b`: 移动到单词开头 (选择范围在光标上方) 
      `<Space> <Space> ge`: 移动到单词结尾 (选择范围在光标上方)
      `<Space> <Space> j`: 移动到行开头 (选择范围在光标下方)
      `<Space> <Space> k`: 移动到行开头 (选择范围在光标上方)
      `<Space> <Space> l`: 移动到单词的开头/结尾 (选择范围在光标下方)
      `<Space> <Space> h`: 移动到单词的开头/结尾 (选择范围在光标上方)
      `<Space> <Space> <Space> j`: 移动到单词的开头/结尾 (选择范围全部)
   
  2. vim.sneak
    开启sneak
    <!-- 开启sneak功能，全局搜索配置 -->
      ```json
      "vim.sneak": true, // 全局搜索配置
      ```
    用法：s + 两个字符
    改键：
      替换原生的f功能
       优势（区别）：f功能只能在当前行跳转（一个字符），sneak可以基于全局跳转（两个字符）

    利用映射来实现原生的s/S/z/Z
    <!--  normal 非递归模式配置 -->
      ```json
      "vim.normalModeKeyBindingsNonRecursive": [
          { // f按键替换sneak的s按键
              "before": ["f"],
              "after": ["s"]
          },
          { // F按键替换sneak的S按键
              "before": ["F"],
              "after": ["S"]
          },
          { // s按键替换cl组合键 删除当前字母并进入insert模式
            // 原来的s按键背sneak的s按键覆盖，顾用cl替换，此处改建为s
              "before": ["s"],
              "after": ["c", "l"]
          },
          { // S按键替换^C组合键 删除当前行并进入insert模式,
            // 原来的S按键背sneak的S按键覆盖，顾用^C替换，此处改建为S
              "before": ["S"],
              "after": ["^", "C"]
          }
      ],
      ``` 
      <!-- visual(可视化模式) 此处是不存在递归的，所以也可以配置在`"vim.visualModeKeyBindings"`中 -->
      ```json
      "vim.visualModeKeyBindingsNonRecursive": [
          { // f按键替换sneak的s按键
              "before": ["f"],
              "after": ["s"]
          },
          // 可视化模式下不支持sneak的S的快捷键，顾不需要配置【可删除】
          // { // F按键替换sneak的S按键
          //     "before": ["F"],
          //     "after": ["S"]
          // },
      ],
      ```

     <!--sneak (operatorPending模式)操作符配置,此处是不存在递归的，所以也可以配置在`"vim.operatorPendingModeKeyBindings`中 -->
      ```json
      "vim.operatorPendingModeKeyBindingsNonRecursive": [
          { // sneak向后操作至匹配向
            // （如：dfma: `ma是相邻两个字母`，删除光标向后到ma前的内容【不包含ma】，
            // yfma:`ma是相邻两个字母`，复制光标向后到ma前的内容【不包含ma】）
              "before": ["f"],
              "after": ["z"]
          },
          { // sneak向后操作至匹配向
            // （如：dfma: `ma是相邻两个字母`，删除光标向前到ma前的内容【包含ma】，
            // yfma:`ma是相邻两个字母`，复制光标向前到ma前的内容【包含ma】） 
              "before": ["F"],
              "after": ["Z"]
          } 
      ],
      ```


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