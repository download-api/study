# vim 使用
### 基本语法
* **动词**

      所谓动词指的是我们执行的动作，这些动作可以施加在名词之上。可以看看下面几个常见的动作：
      d: 删除
      c: 修改
      y: 拷贝
      v: 可视化选择 (V for line c-v  visual block)
      
* **介词**

      <!-- [>定语用在名词之前，表明以哪种方式来执行动作,几个例子。<] -->
      i: 内部
      a: 周围
      NUM: 数字 (e.g.: 1, 2, 10)
      
* **名词**

      在英语中,名词用来表示你所操作的对象,它们都是客体。在vim中也是这样,下面列出vim中的名词。
      w: 单词
      s: 句子
      ): 句子 (另一种操作方式)
      p: 段落
      }: 段落 (另一种操作方式)
      t: 标签 ( HTML/XML)
      b: 块 (编程语言)
      t: 查找到指定字符，并跳转到这个字符的前面
      f: 查找到指定字符，并跳转到字符所处的位置
      /: 查找字符串 (literal or regex)

      ys 包裹

      cs 修改包裹

      ds 删除包裹

      块模式 S 增加包裹      

  [数词] + 动词 + [数词]/[介词] + 名词  

### normal模式
* **添加**

      i光标前进入插入模式
      a光标后进入插入模式
      I行前进入插入模式
      A行尾进入插入模式
* **修改**

      r替换光标内字符
      R一直替换
      s删除当个字符进入插入模式
      S和cc相同删除当前行进入插入模式
      cc删除当前行进入插入模式
      c i w
      c i s
      c i p
      c i t
      c a w
      c a s
      c a p
      c a t
* **删除**
      
      D 清空当前行内容 不删除行
      dd删除当前行
      d i w
      d i s
      d i p
      d i t
      d a w
      d a s
      d a p
      d a t
      dd删除当前行保持正常模式
* **复制**
      
      "ayiw
      "ayaw
      yiw
      yis
      yip
      yit
      yaw
      yas
      yap
      yat

### insert模式
### visual模式
### visual line模式
### visual block模式
### (insert)临时进入normal模式
![](http://img3.imgtn.bdimg.com/it/u=384115025,2366469586&fm=26&gp=0.jpg)
# 这是我新加的
## 这是我新加的
### 这是我新加的
*这是我新加的*

**这是我新加的**

~~这是我新加的~~
    
        这是我新加的

```
for (int i = 10; i<100; i++)
{
    printf("hell olll")
}
```
[this is a test ](https://www.baidu.com)


