# Python
创建列表
1.可修改链表
  classmates = ['Michael', 'Bob', 'Tracy']//使用中括号建立
  添加新名词在已有链表
   classmates.append('Adam')
   元素插入到指定的位置，比如索引号为1的位置：
    classmates.insert(1, 'Jack')
    删除链表中的元素
    classmates.pop()'Adam'
    直接替换元素
       classmates[1] = 'Sarah'
       链表长度获取
     len(classmates)
  链表元素也可不同
  L = ['Apple', 123, True]
2.不可修改元组
  建立元组
    classmates = ('Michael', 'Bob', 'Tracy')
  元组里面只有一个元素时
  t = (1,)
  需要加，否组会被定义为t的整型变量
3.条件语句
    if
if <条件判断1>:
    <执行1>
elif <条件判断2>:
    <执行2>
elif <条件判断3>:
    <执行3>
else:
    <执行4>
for语句
names = ['Michael', 'Bob', 'Tracy']
for name in names:
    print(name)
    输出为
  Michael
  Bob
  Tracy
while循环
如
sum = 0
n = 99
while n > 0:
    sum = sum + n
    n = n - 2
print(sum)
目的计算100以内奇数之和
4.数据类型转换
>>> int('123')
123
>>> int(12.34)
12
>>> float('12.34')#转换为浮点数
12.34
>>> str(1.23)
'1.23'
>>> str(100)#转换为字符类型
'100'
>>> bool(1)#转换为布尔值
True
>>> bool('')
False
5.定义语句
定义一个函数要使用def语句，依次写出函数名、括号、括号中的参数和冒号:，然后，在缩进块中编写函数体，函数的返回值用return语句返回。
def power(x)
  return x*x
对于power(x)函数，参数x就是一个位置参数。
当我们调用power函数时，必须传入有且仅有的一个参数x：
6.切片

7.对象
Python是面向对象编程的，比如一个LED灯
from pyb import LED
red_led = LED(1)
red_led.on()
LED是一个类，red_led就是一个对象，可以对这个对象进行操作，比如点亮on，关掉off，查看value。


8.引用模块
import pyb就是引入pyb这个模块。通过import语句，就可以引入模块。
还有from xxx import ooo 的语句，意思是通过xxx模块引入ooo类，或者通过xxx模块引入ooo函数。

如
import byd
red_led = byd.led(1)
可以写成
from byd import led
red_led = led(1)

