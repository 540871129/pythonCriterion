#python Criterion


###python规范

####命名：
变量名： 正确单词全称或简写，或多单词拼凑需分隔符“_”，
某变量名多用途：若用于models	
   简写是：字典
   全称是对象
   
函数名： 正确单词全称或简写，或多单词拼凑需分隔符“_”
保护函数： _函数名
私有函数： __函数名



####捕获异常：	兼容python3写法
try:
    ...
except Exception as xx:	
    ...

###PEP8风格规范

类（函数）与类（函数）之间换行：2行

类中方法与方法之间换行：2行
