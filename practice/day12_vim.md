## 目标：
  处理包裹字符的符号
## 任务点：
 vim-surround
   - 改变当前字符已经存在的符号(change existing surround desired)
      cs<existing><desired>
     existion:需要替换的字符, desired：替换成什么字符 
   
   - 添加（Add desired surround text defined by）
      ys<motion><desired>
      motion:范围, desired：目标
   
   - 删除（Delete existing surround）
      ds<existing>

   - 可视化模式修改
      S<desired>

- 练习

```js
例1: 修改
const insertvwComp = (name, age) => {
  const a = "b${name}";
}
逛遍在改行内，使用`cs"'`命令则可把`"`改成`'`;
const insertvwComp = (name, age) => {
  const a = 'b${name}';
}


例2: 添加
import test from './000 按键替换'

光在`test`上，使用 `ysaw{`命令则可以在test两侧加上{}

import { test } from './000 按键替换'


例3: 删除
import { test } from './000 按键替换'
光标在 {} 范围内， 执行命令`ds{` 修改成下面
import { test } from './000 按键替换'

const insertvwComp = (name, age) => {
  const a = "b${name}";
}
光标在`const a = "b${name}";`行内 ，输入`ds"`
const insertvwComp = (name, age) => {
  const a = b${name};
}

例4: 可视化模式操作
const insertvwComp = (name, age) => {
  const a = b${name};
}
可视化模式选中`b${name}`, 执行命令`S'`则可改为
const insertvwComp = (name, age) => {
  const a = 'b${name}';
}

```