anyFormula
==========

a 100% java formula parser which supports customized functions and variables.

anyFormula是纯Java实现的公式解析器，具备下列特性：

1. 支持加,减,乘,除,模等算术操作符
2. 支持大于,小于,等于等逻辑操作符
3. 支持下列内置函数
    - choice
    - nvl
    - to_date
    - to_char
    - to_string
    - to_long
    - to_double
    - substr
    - instr
    - strlen
    - match
4. 通过FunctionHelper机制支持自定义函数插件
5. 通过DataProvider机制支持自定义变量
