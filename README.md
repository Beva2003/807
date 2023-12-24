### 零、2024考研心得

今年的807非常简单，可以说有手就行，我把真题放在仓库里了，见 [2024年考研807真题.ipynb](./2024年考研807真题.ipynb)，另外我总结几个值得注意的点：

1. 和2023年一样，2024年也引用改编了《模式分类》（Richard O. Duda等著）的课后习题，所以一定要重视这本书。但是这本书的课后习题非常的多，而且和考纲不完全重合，具体复习策略还需要自行把握。[点击跳转《模式分类》教材和书后题答案](https://github.com/kingloon/EBooks/tree/master/Pattern%20Classification)
2. 和考纲不一样，2024年没有填空题和名词解释题，可能是因为考这种题太low了所以没出。
3. 虽然考纲是第三版，但是第四版的教材也要看，有一些选择题会从第四版中出题。

### 一、项目介绍

这个项目是我学习《模式识别（第三版）》（张学工 清华大学出版社）的笔记。

这本书是 **清华大学深圳研究生院 0854电子信息-人工智能** 考研的专业课（**807**）的考纲截至2024年的唯一指定教材。

前二章不涉及代码，都是一些数学的推导和运算。

从第三章开始，教材开始介绍各种模型，我会争取把教材上涉及到的所有模型用代码实现一遍（书上一行代码都没有）。

每一章笔记的格式是：最前面是二轮的总结，后面是一轮的学习笔记和模型的代码实现。

### 二、特别说明

1. 教材上用到了很多本科没学过的数学知识，我总结在了 [第00章 补充的数学知识.ipynb](./第00章%20补充的数学知识.ipynb) 中，建议看教材之前先看一下。
2. 一定要先看一遍教材，彻底看懂了之后（最好把公式都自己推导一遍），再来看我写的笔记和代码。因为我写的笔记只有实现模型的核心，如果你没理解书上的内容就来看笔记，大概率看不懂。
3. 关于公式的显示问题：显示效果 VS Code > 浏览器上的Jupyter notebook > Pycharm。因为各个环境渲染markdown的引擎不一样，而且很多地方不兼容（特别是这种全是Latex公式的内容）。我已经调整过，让公式在所有地方显示都正常。
4. 如果用浏览器的Jupyter notebook，建议在看/写代码之前，先找个网上的教程给Jupyter notebook装插件，要不然代码显示丑，而且没有自动补全，用起来很难受。或者直接用IDE写代码。

### 三、运行说明

我的本机环境是

+ Python 3.10

Python版本影响不大，不要差太多就行

其他包的安装：

`pip install -r requirements.txt`

建议使用虚拟环境运行。

### 四、文件说明

`./data/`里面保存了一些测试数据

`./资料/`里面保存了一些笔记中引用的内容
