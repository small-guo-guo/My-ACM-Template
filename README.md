# My-ACM-Template
A generator for acm/icpc template manaual with Latex.

# Latex
Latex的安装和配置就不说了，网上有很多资料。

# 文件/目录结构

* 所有文件和目录的格式都按照`**_**`以及`**_**.cpp`的形式

```
.
├── 01_Section1
├── 02_Section2
|   ├── 01_Section2-Charpter1
|   └── 02_Section2-Charpter2
├── 03_Section3
|   └── 00_Section3-Charpter1(Hide)
├── 04_Section4
└── 05_Section5
```

* 生成tex文件时，按照命令行中'ls'的顺序生成各个章节

* 开头为`00_`时，不生成子标题，具体可见repo内的格式和pdf

* 代码开头两个```//  ---```中包含的内容，会去除注释符号后显示在代码前的正文部分，可以写数学公式等

# 编译pdf

* 使用xelatex编译

# 命令
```bash
$ python Manual.py
```

# Update
- 2018.9.22 赛季开始前的准备
    - 新增了常见的积性函数线性筛
    - 新增了扩展大步小步算法求离散对数
    - 新增了单纯形模板
    - 新增了一些常用的公式
    - 新增了回文树模板
    - 新增了字符串哈希的模板
    - 新增了最小树形图模板
    - 新增了刘汝佳的计算几何模板备用
    - 修改了KM算法
    - 删除了没有用的线段树，最小生成树模板
    - 模板中使用宏定义，统一代码风格
- 2018.7.20 简单修改部分不优雅的地方，新增几个公式
- 2018.6.11 简单修改部分不优雅的地方
- 2018.5.11 新增Berlekamp-Massey 算法模板
- 2018.5.10 更正LCA模板中的错误
- 2018.4.11 新增轻重链剖分与Link-Cut Tree模板
- 2018.3.7 模板简单修改
