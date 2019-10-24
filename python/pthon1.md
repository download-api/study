#python

###注释
```
#单行注释
'''
三个单引号多行注释
'''
"""
三个双引号多行注释
"""
```
###变量
* 基本类型
        int float True False 
* tuple
        ( )
* list
        [ ]
* dict
        { }
<br>

###变量删除
del 变量名  

###常量
数值、字符串、元组

###运算符
* 逻辑运算符
        and or not 
* 成员运算符
        in  not
* 身份运算符
        is  is not

###类型转换
```python
int(1.9)
float(1)
int("123")
int("12.3")
int("-11111")
int("33333")

print(min(1,2))
print(max(1,2))
print(round(1.2233))
print(round(1.335,2))
print(abs(-300))
```
### 字符串拼接

```
number = 10
floatnumber = 9.12332
str = "name"
hello = "this is a test"
str = str + hello
print("%s %d %.9f" % (str,number,floatnumber))
```
    
###type
查看数据类型

###id
查看数据地址

###:使用

* 函数
```
def function():
    """
    文档注释
    """
    print("函数测试")
```

* 类
```
class Animal(基类):
    """ 
    文档类注释
    """ 
    __name = "私有成员变量用__2个下滑线开头"

    def __init__():
        print("构造函数")

    def __del__():
        print("析构函数")

    def function(self):
    """ 
    文档函数注释
    """ 
        print("类成员函数")
```
