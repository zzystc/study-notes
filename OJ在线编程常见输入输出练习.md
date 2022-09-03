# OJ在线编程常见输入输出练习

https://www.nowcoder.com/test/27976983/summary



https://ac.nowcoder.com/acm/contest/5657#question



https://labfiles.acmcoder.com/ojhtml/index.html#/?id=jsv8

## 1/11

[编程题]A+B(1)

时间限制：C/C++ 1秒，其他语言2秒

空间限制：C/C++ 256M，其他语言512M

计算a+b

打开以下链接可以查看正确的代码

```
https:``//ac.nowcoder.com/acm/contest/5657#question
```

数据范围： 数据组数 ![img](https://www.nowcoder.com/equation?tex=1%20%5Cle%20t%20%5Cle%20100%20%5C) , 数据大小满足 ![img](https://www.nowcoder.com/equation?tex=1%20%5Cle%20n%20%5Cle%201000%20%5C)



##### **输入描述:**

```
输入包括两个正整数a,b(1 <= a, b <= 1000),输入数据包括多组。
```



##### **输出描述:**

```
输出a+b的结果
```



##### **输入例子1:**

```
1 5
10 20
```



##### **输出例子1:**

```
6
30
```

```
let line;
while (line = readline()) {
    let lines = line.split(' ');
    let a = parseInt(lines[0]);
    let b = parseInt(lines[1]);
    print(a + b);
}
```

javascript:void(0);)

## 2/11

[编程题]A+B(2)

时间限制：C/C++ 1秒，其他语言2秒

空间限制：C/C++ 256M，其他语言512M

计算a+b

打开以下链接可以查看正确的代码

```
https:``//ac.nowcoder.com/acm/contest/5657#question
```



数据范围：数据组数满足 ![img](https://www.nowcoder.com/equation?tex=1%20%5Cle%20t%20%5Cle%20100%20%5C) ，数据大小满足 ![img](https://www.nowcoder.com/equation?tex=1%20%5Cle%20a%2Cb%20%5Cle%201000%20%5C)



##### **输入描述:**

```
输入第一行包括一个数据组数t(1 <= t <= 100)
接下来每行包括两个正整数a,b(1 <= a, b <= 1000)
```



##### **输出描述:**

```
输出a+b的结果
```



##### **输入例子1:**

```
2
1 5
10 20
```



##### **输出例子1:**

```
6
30
```

```
let n = parseInt(readline());
while (n --) {
    line = readline().split(' ');
    let a = parseInt(line[0]);
    let b = parseInt(line[1]);
    print(a + b);
}
```



## 3/11

[编程题]A+B(3)

时间限制：C/C++ 1秒，其他语言2秒

空间限制：C/C++ 256M，其他语言512M

计算a+b

打开以下链接可以查看正确的代码

```
https:``//ac.nowcoder.com/acm/contest/5657#question
```



数据范围：数据组数满足 ![img](https://www.nowcoder.com/equation?tex=1%20%5Cle%20t%20%5Cle%20100%20%5C) ， 数据大小满足 ![img](https://www.nowcoder.com/equation?tex=1%20%5Cle%20n%20%5Cle%20100%20%5C)



##### **输入描述:**

```
输入包括两个正整数a,b(1 <= a, b <= 10^9),输入数据有多组, 如果输入为0 0则结束输入
```



##### **输出描述:**

```
输出a+b的结果
```



##### **输入例子1:**

```
1 5
10 20
0 0
```



##### **输出例子1:**

```
6
30
```

```
let line;
while (line = readline()) {
    if (line == '0 0') {
        break;
    }
    let lines = line.split(' ');
    let a = parseInt(lines[0]);
    let b = parseInt(lines[1]);
    print(a + b);
}
```



## 4/11

[编程题]A+B(4)

时间限制：C/C++ 1秒，其他语言2秒

空间限制：C/C++ 256M，其他语言512M

计算一系列数的和

打开以下链接可以查看正确的代码

```
https:``//ac.nowcoder.com/acm/contest/5657#question
```



数据范围：数据组数满足 ![img](https://www.nowcoder.com/equation?tex=1%20%5Cle%20t%20%5Cle%20100%20%5C) ，每组数据中整数个数满足 ![img](https://www.nowcoder.com/equation?tex=1%20%5Cle%20n%20%5Cle%20100%20%5C) ，每组数据中的值满足 ![img](https://www.nowcoder.com/equation?tex=1%20%5Cle%20val%20%5Cle%20100%20%5C)



##### **输入描述:**

```
输入数据包括多组。
每组数据一行,每行的第一个整数为整数的个数n(1 <= n <= 100), n为0的时候结束输入。
接下来n个正整数,即需要求和的每个正整数。
```



##### **输出描述:**

```
每组数据输出求和的结果
```



##### **输入例子1:**

```
4 1 2 3 4
5 1 2 3 4 5
0
```



##### **输出例子1:**

```
10
15
```

```
let line;
while (line = readline()) {
    const lines = line.split(' ');
    if (lines[0] == 0) {
        break;
    } else {
        let sum = 0;
        for (let i = 1; i < lines.length; i++) {
            sum += parseInt(lines[i]);
        }
        print(sum);
    }
}
```



## 5/11

[编程题]A+B(5)

时间限制：C/C++ 1秒，其他语言2秒

空间限制：C/C++ 32M，其他语言64M

计算一系列数的和

打开以下链接可以查看正确的代码

```
https:``//ac.nowcoder.com/acm/contest/5657#question
```



数据范围：数据组数满足 ![img](https://www.nowcoder.com/equation?tex=1%20%5Cle%20t%20%5Cle%20100%20%5C) ，每组数据中的整数个数满足 ![img](https://www.nowcoder.com/equation?tex=1%20%5Cle%20n%20%5Cle%20100%20%5C) ，每个数据大小满足 ![img](https://www.nowcoder.com/equation?tex=1%20%5Cle%20val%20%5Cle%20100%20%5C)



##### **输入描述:**

```
输入的第一行包括一个正整数t(1 <= t <= 100), 表示数据组数。
接下来t行, 每行一组数据。
每行的第一个整数为整数的个数n(1 <= n <= 100)。
接下来n个正整数, 即需要求和的每个正整数。
```



##### **输出描述:**

```
每组数据输出求和的结果
```



##### **输入例子1:**

```
2
4 1 2 3 4
5 1 2 3 4 5
```



##### **输出例子1:**

```
10
15
```

```
let n = parseInt(readline());
while (n --) {
    let line = readline().split(' ');
    let sum = 0;
    for (let i = 1; i <= parseInt(line[0]); i++) {
        sum += parseInt(line[i]);
    }
    print(sum);
}
```

## 6/11

[编程题]A+B(6)

时间限制：C/C++ 1秒，其他语言2秒

空间限制：C/C++ 256M，其他语言512M

计算一系列数的和

打开以下链接可以查看正确的代码

```
https:``//ac.nowcoder.com/acm/contest/5657#question
```



数据范围： ![img](https://www.nowcoder.com/equation?tex=1%20%5Cle%20n%20%5Cle%201000%20%5C) ， 所有数都满足 ![img](https://www.nowcoder.com/equation?tex=1%20%5Cle%20val%20%5Cle%201000%20%5C)



##### **输入描述:**

```
输入数据有多组, 每行表示一组输入数据。
每行的第一个整数为整数的个数n(1 <= n <= 100)。
接下来n个正整数, 即需要求和的每个正整数。
```



##### **输出描述:**

```
每组数据输出求和的结果
```



##### **输入例子1:**

```
4 1 2 3 4
5 1 2 3 4 5
```



##### **输出例子1:**

```
10
15
```

```
let line;
while (line = readline()) {
    let lines = line.split(' ');
    let sum = 0;
    for (let i = 1; i <= parseInt(lines[0]); i ++) {
        sum += parseInt(lines[i]);
    }
    print(sum);
}
```

## 7/11

[编程题]A+B(7)

时间限制：C/C++ 1秒，其他语言2秒

空间限制：C/C++ 256M，其他语言512M

计算一系列数的和

打开以下链接可以查看正确的代码

```
https:``//ac.nowcoder.com/acm/contest/5657#question
```







##### **输入描述:**

```
输入数据有多组, 每行表示一组输入数据。

每行不定有n个整数，空格隔开。(1 <= n <= 100)。
```



##### **输出描述:**

```
每组数据输出求和的结果
```



##### **输入例子1:**

```
1 2 3
4 5
0 0 0 0 0
```



##### **输出例子1:**

```
6
9
0
```

```
let line;
while (line = readline()) {
    let lines = line.split(' ');
    let sum = 0;
    for (let i = 0; i < lines.length; i ++) {
        sum += parseInt(lines[i]);
    }
    print(sum);
}
```

## 8/11

[编程题]字符串排序(1)

时间限制：C/C++ 1秒，其他语言2秒

空间限制：C/C++ 256M，其他语言512M

对输入的字符串进行排序后输出

打开以下链接可以查看正确的代码

```
https:``//ac.nowcoder.com/acm/contest/5657#question
```







##### **输入描述:**

```
输入有两行，第一行n

第二行是n个字符串，字符串之间用空格隔开
```



##### **输出描述:**

```
输出一行排序后的字符串，空格隔开，无结尾空格
```



##### **输入例子1:**

```
5
c d a bb e
```



##### **输出例子1:**

```
a bb c d e
```

```
let n = parseInt(readline());
let strArr = readline().split(' ');
strArr.sort();
print(strArr.join(' '));
```

## 9/11

[编程题]字符串排序(2)

时间限制：C/C++ 1秒，其他语言2秒

空间限制：C/C++ 256M，其他语言512M

对输入的字符串进行排序后输出

打开以下链接可以查看正确的代码

```
https:``//ac.nowcoder.com/acm/contest/5657#question
```







##### **输入描述:**

```
多个测试用例，每个测试用例一行。

每行通过空格隔开，有n个字符，n＜100
```



##### **输出描述:**

```
对于每组测试用例，输出一行排序过的字符串，每个字符串通过空格隔开
```



##### **输入例子1:**

```
a c bb
f dddd
nowcoder
```



##### **输出例子1:**

```
a bb c
dddd f
nowcoder
```

```
let line;
while (line = readline()) {
    let strArr = line.split(' ').sort().join(' ');
    print(strArr);
}
```

## 10/11

[编程题]字符串排序(3)

时间限制：C/C++ 1秒，其他语言2秒

空间限制：C/C++ 256M，其他语言512M

对输入的字符串进行排序后输出

打开以下链接可以查看正确的代码

```
https:``//ac.nowcoder.com/acm/contest/5657#question
```





##### **输入描述:**

```
多个测试用例，每个测试用例一行。
每行通过,隔开，有n个字符，n＜100
```



##### **输出描述:**

```
对于每组用例输出一行排序后的字符串，用','隔开，无结尾空格
```



##### **输入例子1:**

```
a,c,bb
f,dddd
nowcoder
```



##### **输出例子1:**

```
a,bb,c
dddd,f
nowcoder
```

```
let line;
while (line = readline()) {
    let strArr = line.split(',').sort().join(',');
    print(strArr);
}
```

## 11/11

[编程题]自测本地通过提交为0

时间限制：C/C++ 1秒，其他语言2秒

空间限制：C/C++ 256M，其他语言512M

每年前几场在线笔试编程题的时候，总有同学询问为什么我本地测试通过，自测也通过，提交代码系统却返回通过率0。

打开以下链接可以查看正确的代码

```
https:``//ac.nowcoder.com/acm/contest/5657#question
```

这不是系统的错，可能是因为

1.你对题目理解错了，你的代码只过了样例或你自己的数据

2.你的代码逻辑有问题，你的代码只过了样例或你自己的数据

总之就是你的代码只是过了样例和自测数据，后台的测试数据你根本不可见，要多自己思考。

这个题目如果你提交后通过率为0，又觉得自己代码是正确的，可以 [点击查看](https://ac.nowcoder.com/acm/contest/view-submission?submissionId=41103233) 通过的代码

谨记：

当你笔试的时候怀疑系统或者题目数据有问题的时候请务必先怀疑自己的代码!

当你笔试的时候怀疑系统或者题目数据有问题的时候请务必先怀疑自己的代码!

请帮忙把这个练习专题发给你的朋友同学吧，感谢感谢

数据范围： ![img](https://www.nowcoder.com/equation?tex=0%20%3C%20a%2Cb%20%3C%202%20%5Ctimes%2010%5E%7B10%7D%20%5C)



##### **输入描述:**

```
输入有多组测试用例，每组空格隔开两个整数
```



##### **输出描述:**

```
对于每组数据输出一行两个整数的和
```



##### **输入例子1:**

```
1 1
```



##### **输出例子1:**

```
2
```

```
let line;
line = readline().split(' ');
print(parseInt(line[0]) + parseInt(line[1]));
```

