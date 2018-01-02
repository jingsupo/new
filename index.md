---
layout: default
title: python及前端学习日志
navbar: false
---

# {{ page.title }}

Python中的科学计算建立在一个小型的软件包核心上：

Python，一种通用编程语言。它被解释和动态输入，非常适合于交互式工作和快速原型设计，同时功能足够强大，能够编写大型应用程序。
NumPy，数值计算的基础包。它定义了数值数组和矩阵类型以及它们的基本操作。
SciPy library，数值算法和特定领域的工具箱，包括信号处理，优化，统计和更多的集合。
Matplotlib，一个成熟和流行的绘图软件包，提供出版质量的2D绘图以及基本的3D绘图
在此基础上，SciPy生态系统包括用于数据管理和计算的一般和专用工具，生产性实验和高性能计算。下面我们概述一些重要的软件包，虽然还有更多的相关软件包。

数据和计算：

pandas，提供高性能，易于使用的数据结构。
SymPy，用于符号数学和计算机代数。
scikit-image是图像处理算法的集合。
scikit-learn是机器学习算法和工具的集合。
h5py和PyTables都可以访问以HDF5格式存储的数据。

生产力和高性能计算：

IPython是一个丰富的交互式界面，让您快速处理数据和测试想法。
Jupyter笔记本提供了Web浏览器IPython的功能多，让您在轻松重现的形式记录您的计算。
Cython扩展了Python语法，以便您可以方便地构建C扩展，以加速关键代码或与C / C ++库集成。
Dask，Joblib或IPyParallel进行分布式处理，重点处理数字数据。

质量保证：

nose，一个测试Python代码的框架，正逐渐被pytest所淘汰。
numpydoc是一个用于记录科学Python库的标准和库。

你可以使用下面的命令安装各个包:

`python -m pip install --user numpy scipy matplotlib ipython jupyter pandas sympy nose`

python数据挖掘 数据分析 机器学习
<https://github.com/jingsupo/pydata/blob/master/demo.ipynb>
