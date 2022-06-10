

1. 目标：
  掌握文本对象

2. 任务点：
  认识文本对象(范围)
    内部：i
    外部：a
3. 语法
  operator + (内部[i]/外部[a]) + 文本对象
  可视化模式 + （内部[i]/外部[a]) + 文本对象

4. 对象对应关系
    `w`:         一个单词
    `(`或`)`:    一对()
    `b`:         一对()
    `[`或`]`:    一对[]
    `{`或`}`:    一对{}
    `B`:         一对{}
    `<`或`>`:    一对<>
    `t`:         XML标签
    `'`:         一对'
    `"`:         一对"
    `:           一对``
    `s`:        一个句子（不常用）
    `p`:        一个段落（不常用）     

5. vim-textobj-arguments
    `ia`:       不包含分隔符
    `aa`:       包含分隔符
  tips：技巧 
    1. 删除一个参数：daa
    2. 修改一个参数：cia
6. vim-testobj-entire
  `ae`: 删除当前文本所有内容【dae】
  `ie`: 删除当前所有内容，但不包含前面或后面的空行【die】

tips总结:
 `diw`:删除当前单词
 `daw`:删除当前单词
 `ciw`:删除当前单词，并进入编辑状态
 `caw`:删除当前单词，并进入编辑状态
 
 `daa`:删除一个参数
 `cia`:修改一个参数
 `dae`: 删除当前文本所有内容【dae】
 `die`: 删除当前所有内容，但不包含前面或后面的空行【die】
 
 


本次内容很实用，多练习，应该会提升编码效率

- 练习

```HTML
<a></a>
```
```js
/**
 * 添加
 */
const insertvwComp = (name, age) => {
  const abc = [name,  age];
  const def = {
    name,
    age
  };
  const ghi = `my name is mao ya li`;
}
function testFor (name, age) {
  console.log(name, age)
}
function aTest (_a) {
  const b = _a 
}
 
my name is MaoYali;
obg['12']

const a = <d></d>
```
