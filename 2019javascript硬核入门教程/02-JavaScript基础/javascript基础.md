# 开发前的准备

## 前端开发工具

1. 编辑器

- Notepad++
- EditPlus
- UltraEdit
- Sublime Text
- **VSCode**

2. IDE（集成开发环境）
   DW
   HBuilder
   WebStorm

## VScode 插件

- open in browser
- view in browser
- **live server**

## Emmet 缩写

- `div.box*3`
- `div#box1>a[href="http://www.baidu.com"]{text}`
- `div{$}*10`

# JavaScript 的整体感知

1. 代码的存放位置

- 用`<script>`双标签包裹

  `<script>`的`type`属性可省略，默认值即为 javascript

  ```javascript
  <script type='javascript'> </script>
  ```

  ```javascript
  <script type='text/javascript'> </script>
  ```

- 一般放在`<title>`下面，如果有`<style>`块，则放在`<style>`下面
- 或放在`<body>`双标签的内部的最后面（结束标签之前）
- 理论上`<script>`可以放在程序的任意位置（注意：js 代码的执行顺序为自顶向下；代码阻塞）

2. 关于 JavaScript 代码的书写格式

   1. 适当的空行和缩进
   2. 适当的注释

      前端开源项目 [BootCDN](https://www.bootcdn.cn/)

   3. 有语义的变量函数名等（见名知意）
   4. 一行代码结束，在末尾添加分号

   > Vscode 文档编辑器区域，点击右键-->格式化文档`Alt+Shift+F`

3. JavaScript 对空格、换行、以及缩进不敏感
4. JavaScript 的执行孙旭
5. JavaScript 中的注释
   1. html
   ```html
   <!-- This is a comment -->
   ```
   2. css
   ```css
   /* ... */
   ```
   3. javascript
   ```javascript
   /*
   多行注释
   */
   ```
   ```javascript
   // 单行注释
   ```
   Vscode 的切换注释快捷键 `Ctrl+/`

# 4 条语句

1. 警告框 `alert("")`
2. 输出日志 `console.log("")`
3. 确认框 `confirm("")`
4. 输入框 `prompt("")`

# 直接量

```javascript
   "hello" 'world'
   123 3.14
   true false
```

# 数据类型

一种弱类型的编程语言，定义变量时不区分数据类型。

1. 字符串： `string`
2. 数字： `number`

# 开发人员工具的使用

# 判断数据的类型

```javascript
typeof
```

# 变量

1.  什么是变量
2.  声明变量

```javascript
// 声明变量的关键字 var
// 变量名 a
var a
```

3.  给变量赋值
4.  变量名的注意点
    a. 变量名只能有英文字母、数字、下划线以及 `$` 组成，并且数字不能放在首字母
    b. 变量的命名不能使用 javascript 中的关键字和保留字
    关键字：已经被 javascript 内部使用过的。
    ```javascript
    break case catch continue default
    delete do else finally for
    function in instanceof new
    return switch throw try
    typeof var void while with
    ```
    保留字：还没有被 javascript 内部使用，但将来有可能会被用到
    ```javascript
    abstract boolean byte char class
    const debugger double enum export
    extends final float goto implements
    import int interface long native
    package private protected public short
    static super synchronized throws transient
    volatile
    ```
    c. 区分大小写
5.  变量的类型
    这个变量中存储的是什么样的数据，那么这个变量就是什么类型
6.  变量之间的相互赋值

# 了解其它的数据类型

1. string
   直接量： `""` `''`
   变量: 存储了一个 string 类型的值
2. number
   直接量（统一以浮点数方式进行存储）： 123 3.14 -5e10
3. boolean
4. undefined
5. null
6. object

# 运算符

1. 算术运算符

   1. 算术运算符的定义与用法

      1. \+

         a. 如果加号两边都是字符串，那么加号的作用是连接

         b. 如果加号两边都是数值，那么加号的作用是相加

         c. 如果加号一边是字符串，那么加号的作用是连接

      2. \-

         就是两个数值之间的相减运算

      3. \*

         就是两个数值之间的相乘运算

      4. /

         就是两个数值之间的相除运算

      5. %取余，取值
      6. ()

         改变运算符的优先级

   2. 运算的先后顺序
      先乘除，后加减。
   3. 复杂的运算

2. 关系运算符
3. 位运算符
4. 逻辑运算符
