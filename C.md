# C语言

* printf（“”）中`%%` 输出表示一个 `%` 字符 故

printf("%d==%%====d===%d\n",a,b,e)      输出     a%d=b（%%输出一个% 第二个d输出为字符d 第三个d继承b的值）

printf("%d%%%d=%d\n",a,b,e)   输出    a%b=e

* int 整形（整数）———float 浮点数（小数）