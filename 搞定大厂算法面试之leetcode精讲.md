## 搞定大厂算法面试之leetcode精讲1.开篇介绍

### 视频教程（高效学习）:[点击学习](https://xiaochen1024.com/series/6196129fc1553b002e57bef5/6196208ec1553b002e57bef6)

#### 为什么要学习数据结构和算法

1.  **面试需要**： 大家都知道，国内外的一二线互联网公司都需要面试算法，像google、fb或者像阿里、字节这样的公司，都喜欢在面试的最后环节让候选人手写一段代码解决某个问题，甚至是需要白板编程，没有任何编辑器的提示，这就需要候选者有扎实的数据结构和算法的功力，而且对编码习惯、代码风格、设计模式都有较高的要求。不管是前端、后端、不管用什么语言，这些编程思想和解决问题的方式都是一致的。 那么为什么这么多公司都喜欢考察数据结构和算法呢？这是因为啊，面试短短的1、2个小时，面试官很难判断候选人的能力，就算是考察项目经验和以往的开发经验，由于面试官没有参与过你开发过项目或者研发方向，也很难理解候选人面临的问题和挑战。而考察数据结构和算法，既是对编程基础的考察，又能很好的考量解决问题的能力、思考问题的方式和路径，以及编码的习惯和风格。

     不知道大家有没有这样的感觉，就是面试了很多公司，一到面试算法的部分总是掉链子，刷了很多题，但是依然写不好，总是挂在手写题上，或者明明有能力但面试的时候却说不出来，究其原因就是缺少正确的刷题方式和方法、以及刻意的练习。

2.  **核心能力的提升**：

     数据结构和算法是程序员最核心的能力，不管负责什么业务，是前端还是后端还是人工智能领域的工程师、这项能力都是一个必备的最基础的能力。为什么数据结构和算法这么重要呢。

     我们日常开发用到的大量的框架、库，都是以数据结构和算法为基础设计出来的，举个例子，`react`源码中就用到了大量的链表，还有小顶堆这些数据结构，作为使用了`react`多年的工程师，如果对日常使用的框架的底层原理和运行逻辑没有一个大概的认识，怎么能设计好技术方案，做好选型以及项目优化改进呢。数据结构和算法就好比武侠小说里的内力，而大家学的框架、库都是招式，框架经常会变，而数据结构和算法却是最基础也是最核心的能力，招式用的好不好，打出来的效果怎样，都需要强大的内功来支撑。

     千万不要说这些数据结构和算法我平时工作用不到啊，其实恰恰相反，如果想深挖技术，想要用算法提升程序运行的效率，或者提高自己的编码能力，学习数据结构和算法是一个非常好的方式，这也是我们的核心竞争力之一

3.  **提升职业生涯的高度**：

     不知道大家有没有遇见过一些技术很厉害的程序员，不管在哪家公司，他们总能找到自己的位置，随着时间的推移，独立lead一个项目或者带团队都是迟早的事，为什么这些人职业生涯会走的更远呢？引用乔布斯的一句话，“Stay hungry，Stay foolish”。

     要想职业生涯走的更高更远就需要不断精进自己的技术和能力，比如程序员最核心的数据结构和算法的能力，当然，如果走向了技术管理层，还需要技术的前瞻性和管理能力，这些都是需要方法和刻意练习。时刻保持危机感，不要只停留在某个技术的使用层面，只有这样能选择机会才会更多。

     这里我分享一些个人的经验，不要相信所谓的35岁危机，本质就是到了相应的年龄就需更高的能力，不要做无效的内卷，但是基础的数据结构和算法却是必须的。底层能力才能决定我们走多远。

#### 怎样学习数据结构和算法

1.  **了解基础的数据结构**：比如链表、栈、队列、树等等，可以借助博客，书籍，课程进行学习，书籍比如「javascript数据结构与算法」，以及其他语言的数据结构和算法的书籍，不推荐「算法导论」，因为推理和证明性的内容很多。
2.  **按照类别刻意练习**：按照`leetcode`上的分类进行刷题，比如按照动态规划、分治、回溯等分类练习，`leetcode`题目虽然多，但如果按类别来刷，其实也没多少，很多题目都是类似的套路和延伸，掌握其中面试热门的一百多道就足够应付面试了。

#### 如何刷题:

1.  切碎知识点

    ：对每个类型的题目形成一套解题思路和模版，比如解动态规划的步骤有

    -   根据重叠子问题定义状态
    -   寻找最优子结构推导状态转移方程
    -   确定`dp`初始状态
    -   确定输出值

2.  **刻意练习**：要练习缺陷的、弱的地方，那些写起来不舒服、不爽、枯燥的题目就是薄弱点，不要只练习熟悉类型的题

3.  **反馈**：在`leetcode`上寻找别人的解题思路，包括评论区的讨论，还有程序的运行时间和占用内存的数据，顺便提一句，`leetcode`的运行时间和占用内存情况的数据不准确，就当个参考就好，不要太在意运行时间的排名。

4.  **多写**：反复练习，加强记忆，三分学，七分练。

5.  **总结规律**；将刷题的套路总结成自己方法，比如拆解问题、找基本的子问题、问题的组装、数学归纳等等。最后这些方法落实到代码层面无非是`if else，for while`、递归等，总结了这些规律，才能在题目变化的时候还能找到正确的解题路径。题目做多了也会有相应的感觉，有时从题目要求中也能明显的感觉到该用什么算法，比如题中提到了用`O(logn)`的复杂度来解，那很有可能要用到二分法，提到了`O(nlogn)`，那可能是用归并或者快排的思想解题。

#### 面试时如何做一道题

-   **明确题意**：有不清楚的地方要和面试官明确题目的意思，包括程序的特殊数据输入，数据量，边界条件的处理等等。

-   **可能的解**：要尽可能的列出你知道的方法，对比他们的优劣势，选择你认为最好的方法进行编码。不要小看暴力解法，它往往是题目思考和优化的起点。

-   **写完之后进行复杂度分析**：包括时间和空间复杂度分析。

     面试官往往是考察思考和解决问题的方式，我们要尽量的让面试官看到我们思考的路径和过程，即使最后的运行结果不太正确，也不一定会影响最后的录用，可能也就是因为某个条件或者返回值出现了问题。

     在面试的过程中，如果完全没有思路，也可以向面试官寻求提示和帮助，人无完人，就算是在平时的工作中我们也会遇到困难，这不丢人，积极寻找帮助也是推进项目前进的方式，没有问题有时候才是最大的问题。如果确定这道题是你完全没有遇到过的，可以要求面试官更换一道题，与其浪费时间思考，不如直接换一道，也许换了之后就是熟悉的题目了，知识点和题目这么多，每个人都有自己的知识盲区。不要想着面试官是监考的老师，而是未来的同事，面试不是考试，大多数题都没有标准答案，有时候只要表现的比其他候选人更好一点就可以了。

#### 课程特色

-   **`leetcode`分类讲解**：对`leetcode`高频面试题进行分类讲解，讲到对应的题目时，会介绍对应的数据结构，它有什么特点，以及它的实现，比如堆的实现、字典树的实现等，然后会介绍这道题相应的算法，比如递归，回溯、贪心、动态规划等。
-   **思考路径和套路**：每道题都会列出尽可能多的解题方式，以及复杂度分析，然后讲解思考的路径，同类型的题总结相应的套路，比如二分法，双指针，动态规划，dfs，bfs等的模版。
-   **题目量和难度达到面试的要求**：目前课程包涵174道高频面试题，后续会不定时增加新的面试题，其他同类型的题目基本都是这些问题的变种和延伸，hard题22道，medium题83道，easy题69道，每道题都有详细的注释，后面还会更新更多大厂高频面试题
-   **节省时间**：难题理解困难，解法看不懂，花了大量时间刷题还是刷不会，这可能是大家最头疼的问题了，这门课程会讲解必要的前置知识，相应的解题套路，大量的图解配合视频讲解，不多废话，做到通俗易懂，节省大家的理解和刷题成本。在面试前几天快速进入做题的状态。
-   **解题语言**：这门课主要主要的用`JavaScript`来解题，也会附上`Java`的解题代码，数据结构和算法与相应的实现语言没有太大关系，不管用`python`还是`Go`，其实理解了逻辑和方法，只需要相应的改一下`if else，for while`，数组和对象的声明等等，就可以用对应的语言来解题了。

#### 适合人群

-   **应届校招生**：校招门槛水涨船高，对同学们的能力要求也越来越高，当然薪资肯定也是一年比一年高，做到提前准备，提前刷题，对于处于即将毕业的计算机学科的同学来说还是很必要的。
-   算法薄弱在职工程师：社招的同学如果是想进入bat、美团、字节这样的公司，算法的考察基本是必考的，就算是一些中型的公司，现在也越来越多的考察同学们的基础能力了，对算法的考察也是非常重要的一个环节。

#### 课程大纲和目录

![ds_202](https://xiaochen1024.com/20211118130743.png)

![ds_1](https://xiaochen1024.com/20211118130744.png)



## 搞定大厂算法面试之leetcode精讲2.时间空间复杂度

### 视频教程（高效学习）:[点击学习](https://xiaochen1024.com/series/6196129fc1553b002e57bef5/6196208ec1553b002e57bef6)

#### 什么时间复杂度

时间复杂度是一个函数，它定性描述该算法的运行时间，在软件开发中，时间复杂度就是用来方便开发者估算出程序运行时间，通常用算法的操作单元数量来代表程序消耗的时间，这里默认CPU的每个单元运行消耗的时间都是相同的。假设算法的问题规模为`n`，那么操作单元数量便用函数`f(n)`来表示，随着数据规模`n`的增大，算法执行时间的增长率和`f(n)`的增长率呈现一定的关系，这称作为算法的渐近时间复杂度，简称时间复杂度，记为 `O(f(n)`)，其中n指的是指令集的数目。

#### 什么是大O

**大O用来表示算法执行时间的上界**，也可以理解为最差情况下运行的时间，数据量和顺序等情况对算法的执行时间有非常大的影响，这里假设的是某个输入数据用该算法运行的时间，比其他数据的运算时间都要长。

插入排序的时间复杂度我们都说是`O(n^2)` ，但是插入排序的时间复杂度和输入数据有很大的关系，假如输入数据是完全有序的，则插入排序的时间复杂度是`O(n)`，假如输入的数据是完全倒序的，则时间复杂度是`O(n^2)`，所以最坏是`O(n^2)` 的时间复杂度，我们说插入排序的时间复杂度为`O(n^2)`。

快速排序是`O(nlogn)`，快速排序的在最差的情况下时间复杂度是`O(n^2)` ，一般情况下是`O(nlogn)`，**所以严格从大O的定义来讲，快速排序的时间复杂度应该是O(n^2)**，但是我们依然说快速排序的时间复杂度是`O(nlogn)`，这是业内默认的规定。

二分查找的时间复杂度是`O(logn)`，每次二分数据规模减半，直到数据规模减少为 1，最后相当于求2的多少次方等于n，相当于分割了`logn`次。

归并排序的时间复杂度是`O(nlogn)`，自顶而下的归并，从数据规模为n分割到1，时间复杂度是O(logn)，然后不断向上归并的时间复杂度是`O(n)`，总体时间复杂度是`O(nlogn)`。

树的遍历复杂度一般是`O(n)`，`n`是树的节点个数，选择排序时间复杂度是`O(n^2)`，我们会在对应的章节逐步分析各个数据结构和算法的复杂度。更多的时间复杂度分析和推导可参阅主定理。

![ds_118](https://xiaochen1024.com/20211118130803.png)

#### 分析复杂度的一些规则

-   多个时间复杂度相加，如果都是与n相关，则取取复杂度高的那一个，例如：O(nlogn + n) = O(nlogn)，O(nlogn + n^2) = O(n^2)。
-   多个时间复杂度相加，如果其中有些项的复杂度和n不相关则不能忽略任何项，例如：O(AlogA + B)，O(AlogA + B^2)
-   两个循环依次执行，则取复杂度高的那个，嵌套多个循环则需要累乘复杂度。

#### 常见时间复杂度：

-   O(1):常数复杂度

    ```js
    let n = 100;
    ```

-   O(logn):对数复杂度

    ```js
    //二分查找非递归
    var search = function (nums, target) {
      let left = 0,
        right = nums.length - 1;
      while (left <= right) {
        let mid = Math.floor((left + right) / 2);
        if (nums[mid] === target) {
          return mid;
        } else if (target < nums[mid]) {
          right = mid - 1;
        } else {
          left = mid + 1;
        }
      }
      return -1;
    };
    ```

-   O(n):线性时间复杂度

    ```js
    for (let i = 1; i <= n; i++) {
      console.log(i);
    }
    ```

-   O(n^2)：平方

    ```js
    for (let i = 1; i <= n; i++) {
      for (let j = 1; j <= n; j++) {
        console.log(i);
      }
    }
      
    for (let i = 1; i <= n; i++) {
      for (let j = 1; j <= 30; j++) { //嵌套的第二层如果和n无关则不是O(n^2)
        console.log(i);
      }
    }
    ```

-   O(2^n)：指数复杂度

    ```js
    for (let i = 1; i <= Math.pow(2, n); i++) {
      console.log(i);
    }
    ```

-   O(n!)：阶乘

    ```js
    for (let i = 1; i <= factorial(n); i++) {
      console.log(i);
    }
    ```

![ds_4](https://xiaochen1024.com/20211118130804.png)

#### 常见数据结构基础操作的时间复杂度

![ds_5](https://xiaochen1024.com/20211118130805.png)

![ds_6](https://xiaochen1024.com/20211118130806.png)

#### 递归的时间复杂度

递归的时间复杂度和递归的深度有关

```js
//递归了n层 时间复杂度O(n)
function sum2(n) {
  if (n === 0) {
    return 0;
  }
  return n + sum2(n - 1);
}
//二分查找 递归了logn层 O(logn)
var search = function (nums, target) {
    return search_interval(nums, target, 0, nums.length - 1)
};

function search_interval(nums, target, left, right) {
    if (left > right) {
        return -1
    }
    let mid = left + Math.floor((right - left) / 2);
    if (nums[mid] === target) {//判断目标值和中间元素的大小
        return mid
    } else if (nums[mid] < target) {//递归寻找目标元素
        return search_interval(nums, target, mid + 1, right)
    } else {
        return search_interval(nums, target, left, mid - 1)
    }
}
//斐波那契数：递归法求斐波那契数，总共递归了n层，二叉树的高度是n，由我们的基础知识可以知道，
//一个高度为n的二叉树最多可以有 2^n - 1 个节点，也就是递归过程函数调用的次数，所以时间复杂度为 O(2^n)。
//我们可以看到递归树中包涵非常多的重复计算。
//0, 1，1，2，3 ...
var fib = function (N) {
  if (N == 0) return 0;
  if (N == 1) return 1;
  return fib(N - 1) + fib(N - 2);
};
```

![ds_3](https://xiaochen1024.com/20211118130807.png)

![ds_203](https://xiaochen1024.com/20211118130808.png)

#### 时间复杂度优化

-   采用更好的算法：举例：1+2+3...n从`1～n`求和，直接循环法，for i->n: sum+=i ，我们也可以用求和公式: `n(n+1)/2`。在比如有些问题可以用二分查找等。
-   空间换时间，时间是宝贵的，我们计算一个非常耗时的任务，可能要等上很久，突然的断电，或者意外情况可能会导致非常大的损失，空间是廉价的，最多我们购买更大内存的服务器，花钱就可以解决，在后面的章节有非常多的这样的例子，比如用`set`或`map`加快查找的速度，用二叉搜索树或者字典树加快字符串的搜索。

#### 一个时间复杂度分析的例子

有一个字符串数组，将数组中的每个字符串按照字母排序，然后在将整个字符串数组按照字典顺序排序。求整个操作的时间复杂度。

假如我说时间复杂度是`O(n*nlogn + nlogn) = O(n^2logn)` 对吗，花时间思考一下。

我们来分析一下，假设最长字符串的长度是s，数组中有n个字符串，对每个字符串排序 `O(slogs)`，将数组中的每个字符串按照字母排序`O(n * slogs)`，将整个字符串数组按字典排序 `O(s * nlogn)`，所以最后的时间复杂度是`O(n * slogs) + O(s * nlogn) = O(nslogs + nslogn) = O(ns * (logs+logn))`

#### 空间复杂度

空间复杂度指的是算法在运行过程中所占存储空间的大小，空间复杂度(Space Complexity)记作`S(n)` ，依然使用大O来表示。利用程序的空间复杂度，可以对程序运行中需要多少内存有个预先估计。

#### 常见的空间复杂度

-   一维数组空间，如果存储了n个元素，空间复杂度`O(n)`
-   二维数组空间，总共有n个数组，每个数组存储了n个元素，空间复杂度`O(n^2)`
-   常数空间复杂度`O(1)`

#### 递归的空间复杂度

```js
//O(1)
function sum1(n) {
  let ret = 0;
  for (let i = 0; i <= n; i++) {
    ret += i;
  }
  return ret;
}

//O(n)，递归了n层，递归栈空间是O(n)的复杂度
function sum2(n) {
  if (n === 0) {
    return 0;
  }
  return n + sum2(n - 1);
}

//O(logn)，递归了logn层，递归栈空间是O(logn)的复杂度
var search = function (nums, target) {
    return search_interval(nums, target, 0, nums.length - 1)
};

function search_interval(nums, target, left, right) {
    if (left > right) {
        return -1
    }
    let mid = left + Math.floor((right - left) / 2);
    if (nums[mid] === target) {//判断目标值和中间元素的大小
        return mid
    } else if (nums[mid] < target) {//递归寻找目标元素
        return search_interval(nums, target, mid + 1, right)
    } else {
        return search_interval(nums, target, left, mid - 1)
    }
}
```



## 搞定大厂算法面试之leetcode精讲3.动态规划

### 视频教程（高效学习）:[点击学习](https://xiaochen1024.com/series/6196129fc1553b002e57bef5/6196208ec1553b002e57bef6)

#### 什么是动态规划

动态规划，英文：`Dynamic Programming`，简称`DP`，将问题分解为互**相重叠的子问题**，通过反复求解子问题来解决原问题就是动态规划，如果某一问题有很多重叠子问题，使用动态规划来解是比较有效的。

求解动态规划的核心问题是穷举，但是这类问题穷举有点特别，因为这类问题**存在「重叠子问题」**，如果暴力穷举的话效率会极其低下。动态规划问题一定会**具备「最优子结构」**，才能通过子问题的最值得到原问题的最值。另外，虽然动态规划的核心思想就是穷举求最值，但是问题可以千变万化，穷举所有可行解其实并不是一件容易的事，只有列出**正确的「状态转移方程」**才能正确地穷举。重叠子问题、最优子结构、状态转移方程就是动态规划三要素

#### 动态规划和其他算法的区别

1.  动态规划和分治的区别：动态规划和分治都有最优子结构 ，但是分治的子问题不重叠
2.  动态规划和贪心的区别：动态规划中每一个状态一定是由上一个状态推导出来的，**这一点就区分于贪心**，贪心没有状态推导，而是从局部直接选最优解，所以它永远是局部最优，但是全局的解不一定是最优的。
3.  动态规划和递归的区别：递归和回溯可能存在非常多的重复计算，动态规划可以用递归加记忆化的方式减少不必要的重复计算

#### 动态规划的解题方法

-   递归+记忆化(自顶向下)
-   动态规划（自底向上）

![ds_135](https://xiaochen1024.com/20211118130827.png)

#### 解动态规划题目的步骤

1.  根据重叠子问题定义状态
2.  寻找最优子结构推导状态转移方程
3.  确定dp初始状态
4.  确定输出值

#### 斐波那契的动态规划的解题思路

![ds_3](https://xiaochen1024.com/20211118130828.png)

[动画过大，点击查看](https://xiaochen1024.com/20211118134958.gif)

###### 暴力递归

```javascript
//暴力递归复杂度O(2^n)
var fib = function (N) {
    if (N == 0) return 0;
    if (N == 1) return 1;
    return fib(N - 1) + fib(N - 2);
};
```

###### 递归 + 记忆化

```javascript
var fib = function (n) {
    const memo = {}; // 对已算出的结果进行缓存

    const helper = (x) => {
        if (memo[x]) return memo[x];
        if (x == 0) return 0;
        if (x == 1) return 1;
        memo[x] = helper(x - 1) + helper(x - 2);
        return memo[x];
    };

    return helper(n);
};
```

###### 动态规划

```javascript
const fib = (n) => {
    if (n <= 1) return n;
    const dp = [0, 1];
    for (let i = 2; i <= n; i++) {
        //自底向上计算每个状态
        dp[i] = dp[i - 1] + dp[i - 2];
    }
    return dp[n];
};
```

###### 滚动数组优化

```javascript
const fib = (n) => {
    if (n <= 1) return n;
    //滚动数组 dp[i]只和dp[i-1]、dp[i-2]相关，只维护长度为2的滚动数组，不断替换数组元素
    const dp = [0, 1];
    let sum = null;
    for (let i = 2; i <= n; i++) {
        sum = dp[0] + dp[1];
        dp[0] = dp[1];
        dp[1] = sum;
    }
    return sum;
};
```

###### 动态规划 + 降维，（降维能减少空间复杂度，但不利于程序的扩展）

```javascript
var fib = function (N) {
    if (N <= 1) {
        return N;
    }
    let prev2 = 0;
    let prev1 = 1;
    let result = 0;
    for (let i = 2; i <= N; i++) {
        result = prev1 + prev2; //直接用两个变量就行
        prev2 = prev1;
        prev1 = result;
    }
    return result;
};
```

#### [509. 斐波那契数](https://leetcode-cn.com/problems/fibonacci-number/)（easy）

##### 方法1.动态规划

-   思路：自底而上的动态规划
-   复杂度分析：时间复杂度`O(n)`，空间复杂度`O(1)`

Js:

```javascript
var fib = function (N) {
    if (N <= 1) {
        return N;
    }
    let prev2 = 0;
    let prev1 = 1;
    let result = 0;
    for (let i = 2; i <= N; i++) {
        result = prev1 + prev2;
        prev2 = prev1;
        prev1 = result;
    }
    return result;
};
```

Java:

```java
class Solution {
    public int fib(int n) {
        if (n <= 1) {
            return n;
        }
        int prev2 = 0, prev1 = 1, result = 0;
        for (int i = 2; i <= n; i++) {
            result = prev2 + prev1;
            prev2 = prev1; 
            prev1 = result; 
        }
        return result;
    }
}
```

#### [62. 不同路径](https://leetcode-cn.com/problems/unique-paths/) （medium）

##### 方法1.动态规划

[动画过大，点击查看](https://xiaochen1024.com/20211118135215.gif)

-   思路:由于在每个位置只能向下或者向右， 所以每个坐标的路径和等于上一行相同位置和上一列相同位置不同路径的总和，状态转移方程：`f[i][j] = f[i - 1][j] + f[i][j - 1]`;
-   复杂度:时间复杂度`O(mn)`。空间复杂度`O(mn)`，优化后`O(n)`

js:

```javascript
var uniquePaths = function (m, n) {
    const f = new Array(m).fill(0).map(() => new Array(n).fill(0)); //初始dp数组
    for (let i = 0; i < m; i++) {
        //初始化列
        f[i][0] = 1;
    }
    for (let j = 0; j < n; j++) {
        //初始化行
        f[0][j] = 1;
    }
    for (let i = 1; i < m; i++) {
        for (let j = 1; j < n; j++) {
            f[i][j] = f[i - 1][j] + f[i][j - 1];
        }
    }
    return f[m - 1][n - 1];
};

//状态压缩
var uniquePaths = function (m, n) {
    let cur = new Array(n).fill(1);
    for (let i = 1; i < m; i++) {
        for (let r = 1; r < n; r++) {
            cur[r] = cur[r - 1] + cur[r];
        }
    }
    return cur[n - 1];
};
```

Java:

```java
class Solution {
    public int uniquePaths(int m, int n) {
        int[][] f = new int[m][n];
        for (int i = 0; i < m; ++i) {
            f[i][0] = 1;
        }
        for (int j = 0; j < n; ++j) {
            f[0][j] = 1;
        }
        for (int i = 1; i < m; ++i) {
            for (int j = 1; j < n; ++j) {
                f[i][j] = f[i - 1][j] + f[i][j - 1];
            }
        }
        return f[m - 1][n - 1];
    }
}

//状态压缩
class Solution {
    public int uniquePaths(int m, int n) {
        int[] cur = new int[n];
        Arrays.fill(cur,1);
        for (int i = 1; i < m;i++){
            for (int j = 1; j < n; j++){
                cur[j] += cur[j-1] ;
            }
        }
        return cur[n-1];
    }
}
```

#### [63. 不同路径 II](https://leetcode-cn.com/problems/unique-paths-ii/)（medium）

##### 方法1.动态规划

-   思路：和62题一样，区别就是遇到障碍直接返回0
-   复杂度：时间复杂度`O(mn)`，空间复杂度`O(mn)`，状态压缩之后是o(n)

Js:

```javascript
var uniquePathsWithObstacles = function (obstacleGrid) {
    const m = obstacleGrid.length;
    const n = obstacleGrid[0].length;
    const dp = Array(m)
        .fill()
        .map((item) => Array(n).fill(0)); //初始dp数组

    for (let i = 0; i < m && obstacleGrid[i][0] === 0; ++i) {
        //初始列
        dp[i][0] = 1;
    }

    for (let i = 0; i < n && obstacleGrid[0][i] === 0; ++i) {
        //初始行
        dp[0][i] = 1;
    }

    for (let i = 1; i < m; ++i) {
        for (let j = 1; j < n; ++j) {
            //遇到障碍直接返回0
            dp[i][j] = obstacleGrid[i][j] === 1 ? 0 : dp[i - 1][j] + dp[i][j - 1];
        }
    }

    return dp[m - 1][n - 1];
};

//状态压缩
var uniquePathsWithObstacles = function (obstacleGrid) {
    let m = obstacleGrid.length;
    let n = obstacleGrid[0].length;
    let dp = Array(n).fill(0); //用0填充，因为现在有障碍物，当前dp数组元素的值还和obstacleGrid[i][j]有关
    dp[0] = 1; //第一列 暂时用1填充
    for (let i = 0; i < m; i++) {
        for (let j = 0; j < n; j++) {
            if (obstacleGrid[i][j] == 1) {
                //注意条件，遇到障碍物dp[j]就变成0，这里包含了第一列的情况
                dp[j] = 0;
            } else if (j > 0) {
                //只有当j>0 不是第一列了才能取到j - 1
                dp[j] += dp[j - 1];
            }
        }
    }
    return dp[n - 1];
};
```

Java:

```java
class Solution {
    public int uniquePathsWithObstacles(int[][] obstacleGrid) {
        int n = obstacleGrid.length, m = obstacleGrid[0].length;
        int[] dp = new int[m];

        dp[0] = obstacleGrid[0][0] == 0 ? 1 : 0;
        for (int i = 0; i < n; ++i) {
            for (int j = 0; j < m; ++j) {
                if (obstacleGrid[i][j] == 1) {
                    dp[j] = 0;
                    continue;
                }
                if (j - 1 >= 0 && obstacleGrid[i][j - 1] == 0) {
                    dp[j] += dp[j - 1];
                }
            }
        }
        
        return dp[m - 1];
    }
}
```

#### [70. 爬楼梯](https://leetcode-cn.com/problems/climbing-stairs/) （medium）

##### 方法1.动态规划

![ds_71](https://xiaochen1024.com/20211118130831.png)

-   思路：因为每次可以爬 1 或 2 个台阶，所以到第n阶台阶可以从第n-2或n-1上来，其实就是斐波那契的dp方程
-   复杂度分析：时间复杂度`O(n)`，空间复杂度`O(1)`

Js:

```javascript
var climbStairs = function (n) {
    const memo = [];
    memo[1] = 1;
    memo[2] = 2;
    for (let i = 3; i <= n; i++) {
        memo[i] = memo[i - 2] + memo[i - 1];//所以到第n阶台阶可以从第n-2或n-1上来
    }
    return memo[n];
};

//状态压缩
var climbStairs = (n) => {
    let prev = 1;
    let cur = 1;
    for (let i = 2; i < n + 1; i++) {
        [prev, cur] = [cur, prev + cur]
        // const temp = cur;   // 暂存上一次的cur
        // cur = prev + cur;   // 当前的cur = 上上次cur + 上一次cur
        // prev = temp;        // prev 更新为 上一次的cur
    }
    return cur;
}
```

Java:

```java
class Solution {
    public int climbStairs(int n) {
        int prev = 1, cur = 1;
        for (int i = 2; i < n + 1; i++) {
        int temp = cur;
        cur = prev + cur;  
        prev = temp; 
        }
        return cur;
    }
}
```

#### [279. 完全平方数](https://leetcode-cn.com/problems/perfect-squares/) (medium)

![ds_204](https://xiaochen1024.com/20211118130832.png)

##### 方法1:动态规划

-   思路：`dp[i]` 表示`i`的完全平方和的最少数量，`dp[i - j * j] + 1`表示减去一个完全平方数`j`的完全平方之后的数量加1就等于`dp[i]`，只要在`dp[i]`, `dp[i - j * j] + 1`中寻找一个较少的就是最后`dp[i]`的值。

-   ###### 复杂度：时间复杂度`O(n* sqrt(n))`，n是输入的整数，需要循环n次，每次计算dp方程的复杂度`sqrt(n)`，空间复杂度O(n)

js：

```js
var numSquares = function (n) {
    const dp = [...Array(n)].map((_) => 0); //初始化dp数组 当n为0的时候
    for (let i = 1; i <= n; i++) {
        dp[i] = i; // 最坏的情况就是每次+1 比如: dp[3]=1+1+1
        for (let j = 1; i - j * j >= 0; j++) {//枚举前一个状态
            dp[i] = Math.min(dp[i], dp[i - j * j] + 1); // 动态转移方程
        }
    }
    return dp[n];
};
```

java：

```java
class Solution {
    public int numSquares(int n) {
        int[] dp = new int[n + 1];
        for (int i = 1; i <= n; i++) {
            dp[i] = i;
            for (int j = 1; i - j * j >= 0; j++) { 
                dp[i] = Math.min(dp[i], dp[i - j * j] + 1);
            }
        }
        return dp[n];
    }
}
```

#### [120. 三角形最小路径和](https://leetcode-cn.com/problems/triangle/)（medium）

##### 方法1.动态规划

![ds_72](https://xiaochen1024.com/20211118130833.png)

-   思路：从三角形最后一层开始向上遍历，每个数字的最小路径和是它下面两个数字中的较小者加上它本身
-   复杂度分析：时间复杂度`O(n^2)`，空间复杂`O(n)`

Js:

```js
const minimumTotal = (triangle) => {
    const h = triangle.length;
    // 初始化dp数组
    const dp = new Array(h);
    for (let i = 0; i < h; i++) {
        dp[i] = new Array(triangle[i].length);
    }

    for (let i = h - 1; i >= 0; i--) { //自底而上遍历
        for (let j = 0; j < triangle[i].length; j++) { //同一层的
            if (i == h - 1) {  // base case 最底层
                dp[i][j] = triangle[i][j];
            } else { // 状态转移方程，上一层由它下面一层计算出
                dp[i][j] = Math.min(dp[i + 1][j], dp[i + 1][j + 1]) + triangle[i][j];
            }
        }
    }
    return dp[0][0];
};


//状态压缩
const minimumTotal = (triangle) => {
    const bottom = triangle[triangle.length - 1];
    const dp = new Array(bottom.length);
    // base case 是最后一行
    for (let i = 0; i < dp.length; i++) {
        dp[i] = bottom[i];
    }
    // 从倒数第二列开始迭代
    for (let i = dp.length - 2; i >= 0; i--) {
        for (let j = 0; j < triangle[i].length; j++) {
            dp[j] = Math.min(dp[j], dp[j + 1]) + triangle[i][j];
        }
    }
    return dp[0];
};
```

Java:

```java
class Solution {
    public int minimumTotal(List<List<Integer>> triangle) {
        int n = triangle.size();
        int [] dp = new int [n];
        for(int i = 0 ; i < n ; i++){
            dp[i] = triangle.get(n-1).get(i);
        }
        for(int i = n-2 ; i >= 0 ; i--){
            for(int j = 0 ; j <= i ; j++){
                dp[j] = triangle.get(i).get(j) + Math.min(dp[j] , dp[j+1]);//迭代
            }
        }
        return dp[0];
    }
}
```

#### [152. 乘积最大子数组](https://leetcode-cn.com/problems/maximum-product-subarray/) （medium）

##### 方法1.动态规划

![ds_73](https://xiaochen1024.com/20211118130834.png)

-   思路：
    1.  状态定义：`dp[i][0]`表示从第 0 项到第 i 项范围内的子数组的最小乘积，`dp[i][1]`表示从第 0 项到第 i 项范围内的子数组的最大乘积
    2.  初始状态：`dp[0][0]=nums[0], dp[0][1]=nums[0]`
    3.  分情况讨论:
        -   不和别人乘，就 `nums[i]`自己
        -   `num[i]` 是负数，希望乘上前面的最大积
        -   `num[i]` 是正数，希望乘上前面的最小积
    4.  状态转移方程：
        -   **dp[i] [0]=min(dp[i−1] [0]∗num[i] , dp[i−1] [1] ∗ num[i], num[i])**
        -   **dp[i] [1]=max(dp[i−1] [0]∗num[i] , dp[i−1] [1] ∗ num[i], num[i])**
    5.  状态压缩：`dp[i][x]`只与`dp[i][x]-1`，所以只需定义两个变量，`prevMin = nums[0]`，`prevMax = nums[0]`
    6.  状态压缩之后的方程：
        -   **prevMin = Math.min(prevMin \* num[i], prevMax \* num[i], nums[i])**
        -   **prevMax = Math.max(prevMin \* num[i], prevMax \* num[i], nums[i])**
-   复杂度：时间复杂度`O(n)`，空间复杂度`O(1)`

js:

```javascript
var maxProduct = (nums) => {
    let res = nums[0]
    let prevMin = nums[0]
    let prevMax = nums[0]
    let temp1 = 0, temp2 = 0
    for (let i = 1; i < nums.length; i++) {
        temp1 = prevMin * nums[i]
        temp2 = prevMax * nums[i]
        prevMin = Math.min(temp1, temp2, nums[i])
        prevMax = Math.max(temp1, temp2, nums[i])
        res = Math.max(prevMax, res)
    }
    return res
}
```

Java:

```java
class Solution {
    public int maxProduct(int[] nums) {
        int res = nums[0], prevMin = nums[0], prevMax = nums[0];
        int temp1 = 0, temp2 = 0;
        for (int i = 1; i < nums.length; i++) {
            temp1 = prevMin * nums[i];
            temp2 = prevMax * nums[i];
            prevMin = Math.min(Math.min(temp1, temp2), nums[i]);
            prevMax = Math.max(Math.max(temp1, temp2), nums[i]);
            res = Math.max(prevMax, res);
        }
        return res;
    }
}
```

#### 买卖股票问题

![ds_74](https://xiaochen1024.com/20211118130835.png)

#### [121. 买卖股票的最佳时机](https://leetcode-cn.com/problems/best-time-to-buy-and-sell-stock/)（easy）限定交易次数 k=1

#### [122. 买卖股票的最佳时机 II](https://leetcode-cn.com/problems/best-time-to-buy-and-sell-stock-ii/)（medium）交易次数无限制 k = +infinity

#### [123. 买卖股票的最佳时机 III](https://leetcode-cn.com/problems/best-time-to-buy-and-sell-stock-iii/) (hrad) 限定交易次数 k=2

#### [188. 买卖股票的最佳时机 IV](https://leetcode-cn.com/problems/best-time-to-buy-and-sell-stock-iv/) (hard) 限定交易次数 最多次数为 k

#### [309. 最佳买卖股票时机含冷冻期](https://leetcode-cn.com/problems/best-time-to-buy-and-sell-stock-with-cooldown/)(medium) 含有交易冷冻期

#### [714. 买卖股票的最佳时机含手续费](https://leetcode-cn.com/problems/best-time-to-buy-and-sell-stock-with-transaction-fee/) (medium) 每次交易含手续费

第5，6道题相当于在第2道题的基础上加了冷冻期和手续费的条件。

###### 限制条件

-   先买入才能卖出
-   不能同时参加多笔交易，再次买入时，需要先卖出
-   `k >= 0`才能进行交易，否则没有交易次数

###### **定义操作**

-   买入
-   卖出
-   不操作

###### 定义状态

-   `i`: 天数
-   `k`: 交易次数，每次交易包含买入和卖出，这里我们只在买入的时候需要将 `k - 1`
-   `0`: 不持有股票
-   `1`: 持有股票

###### **举例**

```js
  dp[i][k][0]//第i天 还可以交易k次 手中没有股票
  dp[i][k][1]//第i天 还可以交易k次 手中有股票
```

最终的最大收益是`dp[n - 1][k][0]`而不是`dp[n - 1][k][1]`，因为最后一天卖出肯定比持有收益更高

###### **状态转移方程**

```js
// 今天没有持有股票，分为两种情况：
// 1. dp[i - 1][k][0]，昨天没有持有，今天不操作。 
// 2. dp[i - 1][k][1] + prices[i] 昨天持有，今天卖出，今天手中就没有股票了。
dp[i][k][0] = Math.max(dp[i - 1][k][0], dp[i - 1][k][1] + prices[i])


// 今天持有股票，分为两种情况：
// 1.dp[i - 1][k][1] 昨天持有，今天不操作
// 2.dp[i - 1][k - 1][0] - prices[i] 昨天没有持有，今天买入。
dp[i][k][1] = Math.max(dp[i - 1][k][1], dp[i - 1][k - 1][0] - prices[i])

//最大利润就是这俩种情况的最大值
```

#### [121. 买卖股票的最佳时机](https://leetcode-cn.com/problems/best-time-to-buy-and-sell-stock/)（easy）限定交易次数 k=1

状态转移方程

```js
//第i天不持有 由 第i-1天不持有然后不操作 和 第i-1天持有然后卖出 两种情况的最大值转移过来
dp[i][1][0] = Math.max(dp[i - 1][1][0], dp[i - 1][1][1] + prices[i])
//第i天持有 由 第i-1天持有然后不操作 和 第i-1天不持有然后买入 两种情况的最大值转移过来
dp[i][1][1] = Math.max(dp[i - 1][1][1], dp[i - 1][0][0] - prices[i])
            = Math.max(dp[i - 1][1][1], -prices[i]) // k=0时 没有交易次数，dp[i - 1][0][0] = 0
```

`k`是固定值1，不影响结果，所以可以不用管，简化之后如下

```javascript
dp[i][0] = Math.max(dp[i - 1][0], dp[i - 1][1] + prices[i])
dp[i][1] = Math.max(dp[i - 1][1], -prices[i])
```

完整代码

```javascript
//时间复杂度O(n) 空间复杂度O(n)，dp数组第二维是常数
const maxProfit = function (prices) {
    let n = prices.length;
    let dp = Array.from(new Array(n), () => new Array(2));
    dp[0][0] = 0; //第0天不持有
    dp[0][1] = -prices[0]; //第0天持有
    for (let i = 1; i < n; i++) {
        dp[i][0] = Math.max(dp[i - 1][0], dp[i - 1][1] + prices[i]);
        dp[i][1] = Math.max(dp[i - 1][1], -prices[i]);
    }
    return dp[n - 1][0];
};
```

状态压缩，`dp[i]` 只和 `dp[i - 1]` 有关，去掉一维

```js
//时间复杂度O(n) 空间复杂度O(1)
const maxProfit = function (prices) {
    let n = prices.length;
    let dp = Array.from(new Array(n), () => new Array(2));
    dp[0] = 0;
    dp[1] = -prices[0];
    for (let i = 1; i < n; i++) {
        dp[0] = Math.max(dp[0], dp[1] + prices[i]);
        dp[1] = Math.max(dp[1], -prices[i]);
    }
    return dp[0];
};

//语意化
const maxProfit = function (prices) {
    let n = prices.length;
    let sell = 0;
    let buy = -prices[0];
    for (let i = 1; i < n; i++) {
        sell = Math.max(sell, buy + prices[i]);
        buy = Math.max(buy, -prices[i]);
    }
    return sell;
};
```

#### [122. 买卖股票的最佳时机 II](https://leetcode-cn.com/problems/best-time-to-buy-and-sell-stock-ii/)（medium）交易次数无限制 k = +infinity

状态转移方程

```js
//第i天不持有 由 第i-1天不持有然后不操作 和 第i-1天持有然后卖出 两种情况的最大值转移过来
dp[i][k][0] = Math.max(dp[i - 1][k][0], dp[i - 1][k][1] + prices[i])
//第i天持有 由 第i-1天持有然后不操作 和 第i-1天不持有然后买入 两种情况的最大值转移过来
dp[i][k][1] = Math.max(dp[i - 1][k][1], dp[i - 1][k - 1][0] - prices[i])
```

k同样不影响结果，简化之后如下

```js
dp[i][0] = Math.max(dp[i - 1][0], dp[i - 1][1] + prices[i])
dp[i][1] = Math.max(dp[i - 1][1], dp[i - 1][0] - prices[i])
```

完整代码

```js
const maxProfit = function (prices) {
    let n = prices.length;
    let dp = Array.from(new Array(n), () => new Array(2));
    dp[0][0] = 0; //第0天不持有
    dp[0][1] = -prices[0]; //第0天买入 花了prices[0]
    for (let i = 1; i < n; i++) {
        dp[i][0] = Math.max(dp[i - 1][0], dp[i - 1][1] + prices[i]);
        dp[i][1] = Math.max(dp[i - 1][1], dp[i - 1][0] - prices[i]);
    }
    return dp[n - 1][0];
};
```

状态压缩，同样`dp[i]` 只和 dp[i - 1] 有关，去掉一维

```js
const maxProfit = function (prices) {
    let n = prices.length;
    let dp = Array.from(new Array(n), () => new Array(2));
    dp[0] = 0;
    dp[1] = -prices[0];
    for (let i = 1; i < n; i++) {
        dp[0] = Math.max(dp[0], dp[1] + prices[i]);
        dp[1] = Math.max(dp[1], dp[0] - prices[i]);
    }
    return dp[0];
};

//语意化
const maxProfit = function (prices) {
    let n = prices.length;
    let sell = 0;
    let buy = -prices[0];
    for (let i = 1; i < n; i++) {
        sell = Math.max(sell, buy + prices[i]);
        buy = Math.max(buy, sell - prices[i]);
    }
    return sell;
};
```

#### [123. 买卖股票的最佳时机 III](https://leetcode-cn.com/problems/best-time-to-buy-and-sell-stock-iii/) (hrad) 限定交易次数 k=2

状态转移方程

```js
dp[i][k][0] = Math.max(dp[i - 1][k][0], dp[i - 1][k][1] + prices[i])
dp[i][k][1] = Math.max(dp[i - 1][k][1], dp[i - 1][k - 1][0] - prices[i])
```

k对结果有影响 不能舍去，只能对k进行循环

```js
for (let i = 0; i < n; i++) {
  for (let k = maxK; k >= 1; k--) {
    dp[i][k][0] = Math.max(dp[i - 1][k][0], dp[i - 1][k][1] + prices[i]);
    dp[i][k][1] = Math.max(dp[i - 1][k][1], dp[i - 1][k - 1][0] - prices[i]);
  }
}


//k=2，直接写出循环的结果
dp[i][2][0] = Math.max(dp[i - 1][2][0], dp[i - 1][2][1] + prices[i])
dp[i][2][1] = Math.max(dp[i - 1][2][1], dp[i - 1][1][0] - prices[i])

dp[i][1][0] = Math.max(dp[i - 1][1][0], dp[i - 1][1][1] + prices[i])
dp[i][1][1] = Math.max(dp[i - 1][1][1], dp[i - 1][0][0] - prices[i])
            = Math.max(dp[i - 1][1][1], -prices[i])// k=0时 没有交易次数，dp[i - 1][0][0] = 0

//去掉i这一维度
dp[2][0] = Math.max(dp[2][0], dp[2][1] + prices[i])
dp[2][1] = Math.max(dp[2][1], dp[1][0] - prices[i])

dp[1][0] = Math.max(dp[1][0], dp[1][1] + prices[i])
dp[1][1] = Math.max(dp[1][1], dp[0][0] - prices[i])
            = Math.max(dp[1][1], -prices[i])// k=0时 没有交易次数，dp[i - 1][0][0] = 0
```

完整代码

```js
//和前面一样 我们直接降维
const maxProfit = function (prices) {
    let buy_1 = -prices[0], sell_1 = 0
    let buy_2 = -prices[0], sell_2 = 0
    let n = prices.length
    for (let i = 1; i < n; i++) {
        sell_2 = Math.max(sell_2, buy_2 + prices[i])
        buy_2 = Math.max(buy_2, sell_1 - prices[i])
        sell_1 = Math.max(sell_1, buy_1 + prices[i])
        buy_1 = Math.max(buy_1, -prices[i])
    }
    return sell_2
}
```

#### [188. 买卖股票的最佳时机 IV](https://leetcode-cn.com/problems/best-time-to-buy-and-sell-stock-iv/) (hard) 限定交易次数 最多次数为 k

```js
const maxProfit = function (k, prices) {
    let n = prices.length;
    let profit = new Array(k);//和123题一样 求出所有k的状态
    // 初始化k次交易买入卖出的利润
    for (let j = 0; j <= k; j++) {
        profit[j] = {
            buy: -prices[0],//表示有股票
            sell: 0,//表示没有股票
        };
    }
    for (let i = 0; i < n; i++) {
        for (let j = 1; j <= k; j++) {
            //122题可以交易无数次，188交易k次，所以直接在加一层k循环就可以
          	//122最后的递推方程：
          	//sell = Math.max(sell, buy + prices[i]);
        		//buy = Math.max(buy, -prices[i]);
            profit[j] = {
                sell: Math.max(profit[j].sell, profit[j].buy + prices[i]),
                buy: Math.max(profit[j].buy, profit[j - 1].sell - prices[i]),
            };
        }
    }
    return profit[k].sell; //返回第k次清空手中的股票之后的最大利润
};
```

#### [309. 最佳买卖股票时机含冷冻期](https://leetcode-cn.com/problems/best-time-to-buy-and-sell-stock-with-cooldown/)(medium) 含有交易冷冻期

状态转移方程

```js
dp[i][k][0] = Math.max(dp[i - 1][k][0], dp[i - 1][k][1] + prices[i])
//冷却时间1天，所以要从 i - 2 天转移状态
//买入，卖出 ---- 冷冻期 ----  买入，卖出
dp[i][k][1] = Math.max(dp[i - 1][k][1], dp[i - 2][k - 1][0] - prices[i])
```

题目不限制k的大小，可以舍去

```js
dp[i][0] = Math.max(dp[i - 1][0], dp[i - 1][1] + prices[i])
dp[i][1] = Math.max(dp[i - 1][1], dp[i - 2][0] - prices[i])

//降维i
dp[0] = Math.max(dp[0], dp[1] + prices[i])
dp[1] = Math.max(dp[1], profit_freeze - prices[i])
```

完整代码

```js
const maxProfit = function (prices) {
    let n = prices.length;
    let buy = -prices[0];//手中有股票
    let sell = 0;//没有股票
    let profit_freeze = 0;
    for (let i = 1; i < n; i++) {
        let temp = sell;
        sell = Math.max(sell, buy + prices[i]);
        buy = Math.max(buy, profit_freeze - prices[i]);
        profit_freeze = temp;
    }
    return sell;
};
```

#### [714. 买卖股票的最佳时机含手续费](https://leetcode-cn.com/problems/best-time-to-buy-and-sell-stock-with-transaction-fee/) (medium) 每次交易含手续费

状态转移方程

```js
//每次交易要支付手续费 我们定义在卖出的时候扣手续费
dp[i][0] = max(dp[i - 1][0], dp[i - 1][1] + prices[i] - fee)
dp[i][1] = max(dp[i - 1][1], dp[i - 1][0] - prices[i])
```

完整代码

```js
const maxProfit = function (prices, fee) {
    let sell = 0;//卖出
    let buy = -prices[0];//买入
    for (let i = 1; i < prices.length; i++) {
        sell = Math.max(sell, buy + prices[i] - fee);
        buy = Math.max(buy, sell - prices[i]);
    }
    return sell;
};
```

#### [322. 零钱兑换](https://leetcode-cn.com/problems/coin-change/) (medium)

![ds_75](https://xiaochen1024.com/20211118130836.png)

不能用贪心做，反例，`coins=[1, 3, 5, 6, 7]`，`amount=30`，用贪心先用最大的面额7，在用2个1，`4 * 7 + 2 * 1 = 30`，但是我们用5个6，`5 * 6 = 30` 就能用最少的硬币兑换完成

方法1.动态规划

-   思路：`dp[i]`表示兑换面额`i`所需要的最少硬币，因为硬币无限，所以可以自底向上计算`dp[i]`，对于`dp[0~i]`的每个状态，循环`coins`数组，寻找可以兑换的组合，用`i`面额减去当前硬币价值，`dp[i-coin]`在加上一个硬币数就是`dp[i]`,最后取最小值就是答案，状态转移方程就是`dp[i] = Math.min(dp[i], dp[i - coin] + 1)`;
-   复杂度分析：时间复杂度是*O*(sn)，s是兑换金额，n是硬币数组长度，一共需要计算s个状态，每个状态需要遍历n个面额来转移状态。空间复杂度是`O(s)`，也就是dp数组的长度

Js:

```javascript
var coinChange = function (coins, amount) {
    let dp = new Array(amount + 1).fill(Infinity);//初始化dp数组
    dp[0] = 0;//面额0只需要0个硬币兑换

    for (let i = 1; i <= amount; i++) {//循环面额
        for (let coin of coins) {//循环硬币数组
            if (i - coin >= 0) {//当面额大于硬币价值时
                //dp[i - coin]： 当前面额i减当前硬币价值所需要的最少硬币
                //dp[i] 可由 dp[i - coin] + 1 转换而来
                dp[i] = Math.min(dp[i], dp[i - coin] + 1);
            }
        }
    }

    return dp[amount] === Infinity ? -1 : dp[amount];//如果dp[amount] === Infinity，则无法兑换
};
```

Java:

```java
public class Solution {
    public int coinChange(int[] coins, int amount) {
        int max = amount + 1;
        int[] dp = new int[amount + 1];
        Arrays.fill(dp, max);
        dp[0] = 0;
        for (int i = 1; i <= amount; i++) {
            for (int j = 0; j < coins.length; j++) {
                if (coins[j] <= i) {
                    dp[i] = Math.min(dp[i], dp[i - coins[j]] + 1);
                }
            }
        }
        return dp[amount] > amount ? -1 : dp[amount];
    }
}
```

#### [72. 编辑距离](https://leetcode-cn.com/problems/edit-distance/) （hard）

##### 方法1.动态规划

![ds_76](https://xiaochen1024.com/20211118130837.png)

![ds_77](https://xiaochen1024.com/20211118130838.png)

-   思路：

    ```
    dp[i][j]
    ```

     

    表示word1前i个字符和word2前j个字符的最少编辑距离。

    1.  如果`word1[i-1] === word2[j-1]`,说明最后一个字符不用操作，此时`dp[i][j] = dp[i-1][j-1]`，即此时的最小操作数和word1和word2都减少一个字符的最小编辑数相同

    2.  如果

        ```
        word1[i-1] !== word2[j-1]
        ```

        ，则分为三种情况

        1.  word1删除最后一个字符，状态转移成`dp[i-1][j]`，即`dp[i][j] = dp[i-1][j] + 1`，+1指删除操作
        2.  word1在最后加上一个字符，状态转移成`dp[i][j-1]`，即`dp[i][j] = dp[i][j-1] + 1`，+1指增加操作
        3.  word1替换最后一个字符，状态转移成`dp[i-1][j-1]`，即dp[i] [j] = dp[i-1] [j-1] + 1，+1指替换操作

-   复杂度：时间复杂度是`O(mn)` ，m是word1的长度，n是word2的长度。空间复杂度是`O(mn)` ，需要用m * n大小的二维数字存储状态。

Js:

```javascript
const minDistance = (word1, word2) => {
    let dp = Array.from(Array(word1.length + 1), () => Array(word2.length + 1).fill(0));

    //初始化数组，word1前i个字符最少需要i次操作，比如i次删除变成word2
    for (let i = 1; i <= word1.length; i++) {
        dp[i][0] = i;
    }

    //初始化数组，word2前i个字符最少需要i次操作，比如j次插入变成word1
    for (let j = 1; j <= word2.length; j++) {
        dp[0][j] = j;
    }

    for (let i = 1; i <= word1.length; i++) {
        //循环word1和word2
        for (let j = 1; j <= word2.length; j++) {
            if (word1[i - 1] === word2[j - 1]) {
                //如果word1[i-1] === word2[j-1],说明最后一个字符不用操作。
                dp[i][j] = dp[i - 1][j - 1];
            } else {
                //dp[i-1][j] + 1：对应删除
                //dp[i][j-1] + 1：对应新增
                // dp[i-1][j-1] + 1：对应替换操作
                dp[i][j] = Math.min(dp[i - 1][j] + 1, dp[i][j - 1] + 1, dp[i - 1][j - 1] + 1);
            }
        }
    }

    return dp[word1.length][word2.length];
};
```

Java:

```java
public int minDistance(String word1, String word2) {
    int m = word1.length();
    int n = word2.length();
    int[][] dp = new int[m + 1][n + 1];

    for (int i = 1; i <= m; i++) {
        dp[i][0] =  i;
    }
    for (int j = 1; j <= n; j++) {
        dp[0][j] = j;
    }
    for (int i = 1; i <= m; i++) {
        for (int j = 1; j <= n; j++) {
            if (word1.charAt(i - 1) == word2.charAt(j - 1)) {
                dp[i][j] = dp[i - 1][j - 1];
            } else {
                dp[i][j] = Math.min(Math.min(dp[i - 1][j - 1], dp[i][j - 1]), dp[i - 1][j]) + 1;
            }
        }
    }
    return dp[m][n];
}
```

#### [10. 正则表达式匹配](https://leetcode-cn.com/problems/regular-expression-matching/)(hard)

##### 方法1.动态规划

![ds_78](https://xiaochen1024.com/20211118130839.png)

![ds_79](https://xiaochen1024.com/20211118130840.png)

-   思路：`dp[i][j]` 表示 s 的前 i 个字符能否和p的前j个字符匹配，分为四种情况，看图
-   复杂度：时间复杂度`O(mn)`，m,n分别是字符串s和p的长度，需要嵌套循环s和p。空间复杂度`O(mn)`，dp数组所占的空间

js:

```js
//dp[i][j]表示s的前i个字符能否和p的前j个字符匹配
const isMatch = (s, p) => {
    if (s == null || p == null) return false;//极端情况 s和p都是空 返回false

    const sLen = s.length, pLen = p.length;

    const dp = new Array(sLen + 1);//因为位置是从0开始的，第0个位置是空字符串 所以初始化长度是sLen + 1
    for (let i = 0; i < dp.length; i++) {//初始化dp数组
        dp[i] = new Array(pLen + 1).fill(false); // 将项默认为false
    }
    // base case s和p第0个位置是匹配的
    dp[0][0] = true;
    for (let j = 1; j < pLen + 1; j++) {//初始化dp的第一列，此时s的位置是0
        //情况1:如果p的第j-1个位置是*，则j的状态等于j-2的状态
        //例如：s='' p='a*' 相当于p向前看2个位置如果匹配，则*相当于重复0个字符
        if (p[j - 1] == "*") dp[0][j] = dp[0][j - 2];
    }
    // 迭代
    for (let i = 1; i < sLen + 1; i++) {
        for (let j = 1; j < pLen + 1; j++) {

            //情况2:如果s和p当前字符是相等的 或者p当前位置是. 则当前的dp[i][j] 可由dp[i - 1][j - 1]转移过来
            //当前位置相匹配，则s和p都向前看一位 如果前面所有字符相匹配 则当前位置前面的所有字符也匹配
            //例如：s='XXXa' p='XXX.' 或者 s='XXXa' p='XXXa'
            if (s[i - 1] == p[j - 1] || p[j - 1] == ".") {
                dp[i][j] = dp[i - 1][j - 1];
            } else if (p[j - 1] == "*") {//情况3:进入当前字符不匹配的分支 如果当前p是* 则有可能会匹配
                //s当前位置和p前一个位置相同 或者p前一个位置等于. 则有三种可能
                //其中一种情况能匹配 则当前位置的状态也能匹配
                //dp[i][j - 2]：p向前看2个位置，相当于*重复了0次，
                //dp[i][j - 1]：p向前看1个位置，相当于*重复了1次
                //dp[i - 1][j]：s向前看一个位置，相当于*重复了n次
                //例如 s='XXXa' p='XXXa*'
                if (s[i - 1] == p[j - 2] || p[j - 2] == ".") {
                    dp[i][j] = dp[i][j - 2] || dp[i][j - 1] || dp[i - 1][j];
                } else {
                    //情况4:s当前位置和p前2个位置不匹配，则相当于*重复了0次
                    //例如 s='XXXb' p='XXXa*' 当前位置的状态和p向前看2个位置的状态相同
                    dp[i][j] = dp[i][j - 2];
                }
            }
        }
    }
    return dp[sLen][pLen]; // 长为sLen的s串 是否匹配 长为pLen的p串
};
```

Java:

```java
class Solution {
    public boolean isMatch(String s, String p) {
        if (p==null){
            if (s==null){
                return true;
            }else{
                return false;
            }
        }

        if (s==null && p.length()==1){
            return false;
        }

        int m = s.length()+1;
        int n = p.length()+1;

        boolean[][]dp = new boolean[m][n];

        dp[0][0] = true;

        for (int j=2;j<n;j++){
            if (p.charAt(j-1)=='*'){
                dp[0][j] = dp[0][j-2];
            }
        }

        for (int r=1;r<m;r++){
            int i = r-1;
            for (int c=1;c<n;c++){
                int j = c-1;
                if (s.charAt(i)==p.charAt(j) || p.charAt(j)=='.'){
                    dp[r][c] = dp[r-1][c-1];
                }else if (p.charAt(j)=='*'){
                    if (p.charAt(j-1)==s.charAt(i) || p.charAt(j-1)=='.'){
                        dp[r][c] = dp[r-1][c] || dp[r][c-2];
                    }else{
                        dp[r][c] = dp[r][c-2];
                    }
                }else{
                    dp[r][c] = false;
                }

            }
        }
        return dp[m-1][n-1];
    }
}
```

#### [312. 戳气球](https://leetcode-cn.com/problems/burst-balloons/) (hard)

##### 方法1:动态规划

![ds_112](https://xiaochen1024.com/20211118130841.png)

-   思路：`dp[i][j]` 表示开区间 `(i,j)` 能拿到的的金币，k是这个区间 *最后一个* 被戳爆的气球，枚举`i`和`j`，遍历所有区间，`i-j`能获得的最大数量的金币等于 戳破当前的气球获得的金钱加上之前`i-k`、`k-j`区间中已经获得的金币
-   复杂度：时间复杂度`O(n^3)`，n是气球的数量，三层遍历。空间复杂度`O(n^2)`，dp数组的空间。

js：

```js
var maxCoins = function (nums) {
    const n = nums.length;
    let points = [1, ...nums, 1]; //两边添加虚拟气球
    const dp = Array.from(Array(n + 2), () => Array(n + 2).fill(0)); //dp数组初始化
    //自底向上转移状态
    for (let i = n; i >= 0; i--) {
        //i不断减小
        for (let j = i + 1; j < n + 2; j++) {
            //j不断扩大
            for (let k = i + 1; k < j; k++) {
                //枚举k在i和j中的所有可能
                //i-j能获得的最大数量的金币等于 戳破当前的气球获得的金钱加上之前i-k,k-j区间中已经获得的金币
                dp[i][j] = Math.max(
                    //挑战最大值
                    dp[i][j],
                    dp[i][k] + dp[k][j] + points[j] * points[k] * points[i]
                );
            }
        }
    }
    return dp[0][n + 1];
};
```

java：

```java
class Solution {
    public int maxCoins(int[] nums) {
        int n = nums.length;
        int[][] dp = new int[n + 2][n + 2];
        int[] val = new int[n + 2];
        val[0] = val[n + 1] = 1;
        for (int i = 1; i <= n; i++) {
            val[i] = nums[i - 1];
        }
        for (int i = n - 1; i >= 0; i--) {
            for (int j = i + 2; j <= n + 1; j++) {
                for (int k = i + 1; k < j; k++) {
                    int sum = val[i] * val[k] * val[j];
                    sum += dp[i][k] + dp[k][j];
                    dp[i][j] = Math.max(dp[i][j], sum);
                }
            }
        }
        return dp[0][n + 1];
    }
}
```

#### [343. 整数拆分](https://leetcode-cn.com/problems/integer-break/) (medium)

![ds_136](https://xiaochen1024.com/20211118130842.png)

-   思路：`dp[i]`为正整数i拆分之后的最大乘积，循环数字n，对每个数字进行拆分，取最大的乘积，状态转移方程：`dp[i] = Math.max(dp[i], dp[i - j] * j, (i - j) * j)`，`j*(i-j)`表示把i拆分为`j`和i-j两个数相乘，`j * dp[i-j]`表示把`i`拆分成`j`和继续把`(i-j)`这个数拆分，取`(i-j)`拆分结果中的最大乘积与j相乘
-   复杂度：时间复杂度`O(n^2)`，两层循环。空间复杂度`O(n)`，`dp`数组的空间

js：

```js
var integerBreak = function (n) {
    //dp[i]为正整数i拆分之后的最大乘积
    let dp = new Array(n + 1).fill(0);
    dp[2] = 1;

    for (let i = 3; i <= n; i++) {
        for (let j = 1; j < i; j++) {
            //j*(i-j)表示把i拆分为j和i-j两个数相乘
            //j*dp[i-j]表示把i拆分成j和继续把(i-j)这个数拆分，取(i-j)拆分结果中的最大乘积与j相乘
            dp[i] = Math.max(dp[i], dp[i - j] * j, (i - j) * j);
        }
    }
    return dp[n];
};
```

java：

```js
class Solution {
    public int integerBreak(int n) {
        int[] dp = new int[n+1]; 
        dp[2] = 1;//初始状态
        for (int i = 3; i <= n; ++i) {
            for (int j = 1; j < i - 1; ++j) {
                dp[i] = Math.max(dp[i], Math.max(j * (i - j), j * dp[i - j]));
            }
        }
        return dp[n];
    }
}
```

#### 0-1背包问题

0-1背包问题指的是有`n`个物品和容量为`j`的背包，`weight`数组中记录了`n`个物品的重量，位置`i`的物品重量是weight[i]，`value`数组中记录了`n`个物品的价值，位置i的物品价值是`vales[i]`，每个物品只能放一次到背包中，问将那些物品装入背包，使背包的价值最大。

举例：

![ds_214](https://xiaochen1024.com/20211118193828.png)

我们用动态规划的方式来做

-   状态定义：`dp[i][j]` 表示从前i个物品里任意取，放进容量为j的背包，价值总和最大是多少

-   状态转移方程： `dp[i][j] = max(dp[i - 1][j]`, `dp[i - 1][j - weight[i]] + value[i])`; 每个物品有放入背包和不放入背包两种情况

    1.  当`j - weight[i]<0`：表示装不下`i`号元素了，不放入背包，此时`dp[i][j] = dp[i - 1][j]`，dp[i] [j]取决于前`i-1`中的物品装入容量为`j`的背包中的最大价值
    2.  当`j - weight[i]>=0`：可以选择放入或者不放入背包。 放入背包则：`dp[i][j] = dp[i - 1][j - weight[i]] + value[i]`， `dp[i - 1][j - weight[i]]` 表示`i-1`中的物品装入容量为`j-weight[i]`的背包中的最大价值，然后在加上放入的物品的价值`value[i]`就可以将状态转移到`dp[i][j]`。 不放入背包则：`dp[i][j] = dp[i - 1] [j]`，在这两种情况中取较大者。

-   初始化dp数组：`dp[i][0]`表示背包的容积为0，则背包的价值一定是0，`dp[0][j]`表示第0号物品放入背包之后背包的价值

    ![ds_137](https://xiaochen1024.com/20211118130843.png)

-   最终需要返回值：就是dp数组的最后一行的最后一列

循环完成之后的dp数组如下图

![ds_138](https://xiaochen1024.com/20211118130844.png)

js：

```js
function testWeightBagProblem(wight, value, size) {
    const len = wight.length,
        dp = Array.from({ length: len + 1 }).map(//初始化dp数组
            () => Array(size + 1).fill(0)
        );
    //注意我们让i从1开始，因为我们有时会用到i - 1，为了防止数组越界
    //所以dp数组在初始化的时候，长度是wight.length+1
    for (let i = 1; i <= len; i++) {
        for (let j = 0; j <= size; j++) {
            //因为weight的长度是wight.length+1，并且物品下标从1开始，所以这里i要减1
            if (wight[i - 1] <= j) {
                dp[i][j] = Math.max(
                    dp[i - 1][j],
                    value[i - 1] + dp[i - 1][j - wight[i - 1]]
                )
            } else {
                dp[i][j] = dp[i - 1][j];
            }
        }
    }

    return dp[len][size];
}

function test() {
    console.log(testWeightBagProblem([1, 3, 4], [15, 20, 30], 4));
}

test();
```

#### 状态压缩

根据状态转移方程`dp[i][j] = max(dp[i - 1][j], dp[i - 1][j - weight[i]] + value[i])`，第i行只与第i-1行状态相关，所以我们可以用滚动数组进行状态压缩，其次我们注意到，j只与j前面的状态相关，所以只用一个数组从后向前计算状态就可以了。

[动画过大，点击查看](https://xiaochen1024.com/20211118135529.gif)

```js
function testWeightBagProblem2(wight, value, size) {
    const len = wight.length,
        dp = Array(size + 1).fill(0);
    for (let i = 1; i <= len; i++) {
        //从后向前计算，如果从前向后的话，最新的值会覆盖老的值，导致计算结果不正确
      	//dp[i][j] = Math.max(dp[i - 1][j], dp[i - 1][j - wight[i - 1]] + value[i - 1])
        for (let j = size; j >= wight[i - 1]; j--) {
            dp[j] = Math.max(dp[j], dp[j - wight[i - 1]] + value[i - 1] );
        }
    }
    return dp[size];
}
```

#### [416. 分割等和子集](https://leetcode-cn.com/problems/partition-equal-subset-sum/) （medium）

![ds_140](https://xiaochen1024.com/20211118130846.png)

-   思路：本题可以看成是0-1背包问题，给一个可装载重量为 `sum / 2` 的背包和 N 个物品，每个物品的重量记录在 nums 数组中，问是否在一种装法，能够恰好将背包装满？`dp[i][j]`表示前i个物品是否能装满容积为j的背包，当`dp[i][j]`为true时表示恰好可以装满。每个数都有放入背包和不放入两种情况，分析方法和0-1背包问题一样。
-   复杂度：时间复杂度`O(n*sum)`，n是nums数组长度，sum是nums数组元素的和。空间复杂度`O(n * sum)`，状态压缩之后是`O(sum)`

js：

```js
//可以看成是0-1背包问题，给一个可装载重量为 sum / 2 的背包和 N 个物品，
//每个物品的重量记录在 nums 数组中，问是否在一种装法，能够恰好将背包装满？
var canPartition = function (nums) {
    let sum = 0
    let n = nums.length
    for (let i = 0; i < n; i++) {
        sum += nums[i]
    }
    if (sum % 2 !== 0) {//如果是奇数，那么分割不了，直接返回false
        return false
    }
    sum = sum / 2
    //dp[i][j]表示前i个物品是否能装满容积为j的背包，当dp[i][j]为true时表示恰好可以装满
    //最后求的是 dp[n][sum] 表示前n个物品能否把容量为sum的背包恰好装满
    //dp数组长度是n+1，而且是二维数组，第一维表示物品的索引，第二个维度表示背包大小
    let dp = new Array(n + 1).fill(0).map(() => new Array(sum + 1).fill(false))
    //dp数组初始化，dp[..][0] = true表示背包容量为0，这时候就已经装满了，
    //dp[0][..] = false 表示没有物品，肯定装不满
    for (let i = 0; i <= n; i++) {
        dp[i][0] = true
    }
    for (let i = 1; i <= n; i++) {//i从1开始遍历防止取dp[i - 1][j]的时候数组越界
        let num = nums[i - 1]
        //j从1开始，j为0的情况已经在dp数组初始化的时候完成了
        for (let j = 1; j <= sum; j++) {
            if (j - num < 0) {//背包容量不足 不能放入背包
                dp[i][j] = dp[i - 1][j];//dp[i][j]取决于前i-1个物品是否能前好装满j的容量
            } else {
                //dp[i - 1][j]表示不装入第i个物品
                //dp[i - 1][j-num]表示装入第i个，此时需要向前看前i - 1是否能装满j-num
                //和背包的区别，这里只是返回true和false 表示能否装满，不用计算价值
                dp[i][j] = dp[i - 1][j] || dp[i - 1][j - num];
            }
        }
    }
    return dp[n][sum]
};

//状态转移方程 F[i, target] = F[i - 1, target] || F[i - 1, target - nums[i]]
//第 n 行的状态只依赖于第 n-1 行的状态
//状态压缩
var canPartition = function (nums) {
    let sum = nums.reduce((acc, num) => acc + num, 0);
    if (sum % 2) {
        return false;
    }
    sum = sum / 2;
    const dp = Array.from({ length: sum + 1 }).fill(false);
    dp[0] = true;

    for (let i = 1; i <= nums.length; i++) {
        //从后向前计算，如果从前向后的话，最新的值会覆盖老的值，导致计算结果不正确
        for (let j = sum; j > 0; j--) {
            dp[j] = dp[j] || (j - nums[i] >= 0 && dp[j - nums[i]]);
        }
    }

    return dp[sum];
};
```

java：

```java
public class Solution {

    public boolean canPartition(int[] nums) {
        int len = nums.length;
        int sum = 0;
        for (int num : nums) {
            sum += num;
        }
        if ((sum & 1) == 1) {
            return false;
        }

        int target = sum / 2;
        boolean[][] dp = new boolean[len][target + 1];
        
        dp[0][0] = true;

        if (nums[0] <= target) {
            dp[0][nums[0]] = true;
        }
        for (int i = 1; i < len; i++) {
            for (int j = 0; j <= target; j++) {
                dp[i][j] = dp[i - 1][j];
                if (nums[i] <= j) {
                    dp[i][j] = dp[i - 1][j] || dp[i - 1][j - nums[i]];
                }
            }

            if (dp[i][target]) {
                return true;
            }
        }
        return dp[len - 1][target];
    }
}

//状态压缩
public class Solution {

    public boolean canPartition(int[] nums) {
        int len = nums.length;
        int sum = 0;
        for (int num : nums) {
            sum += num;
        }
        if ((sum & 1) == 1) {
            return false;
        }

        int target = sum / 2;
        boolean[] dp = new boolean[target + 1];
        dp[0] = true;

        if (nums[0] <= target) {
            dp[nums[0]] = true;
        }
        for (int i = 1; i < len; i++) {
            for (int j = target; nums[i] <= j; j--) {
                if (dp[target]) {
                    return true;
                }
                dp[j] = dp[j] || dp[j - nums[i]];
            }
        }
        return dp[target];
    }
}
```

#### [198. 打家劫舍](https://leetcode-cn.com/problems/house-robber/) （medium）

![ds_148](https://xiaochen1024.com/20211118130847.png)

-   思路：

    ```
    dp[i]
    ```

    表示0-i能偷的最大金额，

    ```
    dp[i]
    ```

    由两种情况中的最大值转移过来

    1.  `dp[i - 2] + nums[i]` 表示偷当前位置，那么i-1的位置不能偷，而且需要加上`dp[i-2]`,也就是前i-2个房间的金钱
    2.  `dp[i - 1]`表示偷当前位置，只偷i-1的房间

-   复杂度：时间复杂度`O(n)`，遍历一次数组，空间复杂度`O(1)`，状态压缩之后是`O(1)`，没有状态压缩是`O(n)`

js：

```js
//dp[i]表示0-i能偷的最大金额
const rob = (nums) => {
    const len = nums.length;
    const dp = [nums[0], Math.max(nums[0], nums[1])]; //初始化dp数组的前两项
    for (let i = 2; i < len; i++) {
        //从第三个位置开始遍历
        //dp[i - 2] + nums[i] 表示偷当前位置，那么i-1的位置不能偷，
      	//而且需要加上dp[i-2],也就是前i-2个房间的金钱
        //dp[i - 1]表示偷当前位置，只偷i-1的房间
        dp[i] = Math.max(dp[i - 2] + nums[i], dp[i - 1]);
    }
    return dp[len - 1]; //返回最后最大的项
};

//状态压缩
var rob = function (nums) {
    if(nums.length === 1) return nums[0]
    let len = nums.length;
    let dp_0 = nums[0],
        dp_1 = Math.max(nums[0], nums[1]);
    let dp_max = dp_1;
    for (let i = 2; i < len; i++) {
        dp_max = Math.max(
            dp_1, //不抢当前家
            dp_0 + nums[i] //抢当前家
        );
        dp_0 = dp_1; //滚动交换变量
        dp_1 = dp_max;
    }
    return dp_max;
};
```

java:

```java
class Solution {
    public int rob(int[] nums) {
        if (nums == null || nums.length == 0) {
            return 0;
        }
        int length = nums.length;
        if (length == 1) {
            return nums[0];
        }
        int[] dp = new int[length];
        dp[0] = nums[0];
        dp[1] = Math.max(nums[0], nums[1]);
        for (int i = 2; i < length; i++) {
            dp[i] = Math.max(dp[i - 2] + nums[i], dp[i - 1]);
        }
        return dp[length - 1];
    }
}

//状态压缩
class Solution {
    public int rob(int[] nums) {
        if (nums == null || nums.length == 0) {
            return 0;
        }
        int len = nums.length;
        int dp_0 = 0,
            dp_1 = nums[0];
        int dp_max = nums[0];
        for (int i = 2; i <= len; i++) {
            dp_max = Math.max(
                dp_1, //不抢当前家
                dp_0 + nums[i - 1] //抢当前家
            );
            dp_0 = dp_1; //滚动交换变量
            dp_1 = dp_max;
        }
        return dp_max;
    }
}
```

#### [64. 最小路径和](https://leetcode-cn.com/problems/minimum-path-sum/) (medium)

![ds_205](https://xiaochen1024.com/20211118130848.png)

-   思路：`dp[i][j]`表示从矩阵左上角到`（i，j）`这个网格对应的最小路径和，只要从上到下，从左到右遍历网格，当前最小路径和就是当前的数值加上上面和左边左小的。
-   复杂度：时间复杂度`O(mn)`，m、n分别是矩阵的长和宽。空间复杂度如果原地修改是`O(1)`，如果新建dp数组就是`O(mn)`

js：

```js
var minPathSum = function(dp) {
    let row = dp.length, col = dp[0].length

    for(let i = 1; i < row; i++)//初始化第一列
        dp[i][0] += dp[i - 1][0]

    for(let j = 1; j < col; j++)//初始化第一行
        dp[0][j] += dp[0][j - 1]

    for(let i = 1; i < row; i++)
        for(let j = 1; j < col; j++)
            dp[i][j] += Math.min(dp[i - 1][j], dp[i][j - 1])//取上面和左边最小的
    
    return dp[row - 1][col - 1]
};
```

java：

```java
class Solution {
    public int minPathSum(int[][] grid) {
        if (grid == null || grid.length == 0 || grid[0].length == 0) {
            return 0;
        }
        int rows = grid.length, columns = grid[0].length;
        int[][] dp = new int[rows][columns];
        dp[0][0] = grid[0][0];
        for (int i = 1; i < rows; i++) {
            dp[i][0] = dp[i - 1][0] + grid[i][0];
        }
        for (int j = 1; j < columns; j++) {
            dp[0][j] = dp[0][j - 1] + grid[0][j];
        }
        for (int i = 1; i < rows; i++) {
            for (int j = 1; j < columns; j++) {
                dp[i][j] = Math.min(dp[i - 1][j], dp[i][j - 1]) + grid[i][j];
            }
        }
        return dp[rows - 1][columns - 1];
    }
}
```

上一节下一节