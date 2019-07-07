> 开启刷面试题，都是根据视频进行刷面试题的


自增变量，只要记住两点

- i++ 是先赋值后计算
- ++i 是先计算后赋值

看下面的代码

```
        int i = 1;
        i = i++;
        int j = i++;
        int k = i + ++i * i++;
        System.out.println("i="+ i);
        System.out.println("j=" +j);
        System.out.println("k="+ k);
```

这里要注意两点
1. 自增变量的算法
2. 运算符的优先级

运行结果如下

```
i=4
j=1
k=11
```

**我只害怕一样，那就是配不上我所受的痛苦 ！**