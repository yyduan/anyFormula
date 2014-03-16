anyFormula
==========

a 100% java formula parser

anyFormula是纯Java实现的公式解析器，具备下列特性：

1. 支持加,减,乘,除,模等算术操作符
2. 支持大于,小于,等于等逻辑操作符
3. 支持下列内置函数
    1) choice
    2) nvl
    3) to_date
    4) to_char
    5) to_string
    6) to_long
    7) to_double
    8) substr
    9) instr
    10) strlen
    11) match
4. 通过FunctionHelper机制支持自定义函数插件
5. 通过DataProvider机制支持自定义变量
