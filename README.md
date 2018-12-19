Jupyter Notebook
====
The Jupyter Notebook is an open-source web application that allows you to create and share documents that contain live code, equations, visualizations and narrative text. Uses include: data cleaning and transformation, numerical simulation, statistical modeling, data visualization, machine learning, and much more.

其实他想说的是：我最牛逼，我最刁，全世界都在用

1、python3.x安装
--------------
官网下载即可 https://www.python.org/
苹果的Mac OS 自带了 python2.7.x ，需要另行安置python3.x 。 但是由于系统运行依赖于自带的 Python2.7.x，因此请务必不要删除系统自带版本 

记得勾选 Add Python to PATH，以便在系统环境中直接运行python。

2、Jupyter Notebook安装
--------------
输入：

    $ pip3 install jupyter

PS:windows需要以管理员身份运行命令提示符

输入：

    $ jupyter notebook

就可以启动 Jupyter Notebook


3、安装必须的库
--------------

Mac：

    $ sudo pip3 install numpy scipy matplotlib ipython pandas scikit-learn

Mac安装比较舒服只需要一个命令即可

Windows：

windows需要手动下载安装Numpy+MKL和Scipy

    https://www.lfd.uci.edu/~gohlke/pythonlibs/

搜索下载安装：Numpy+MKL is

找到适合自己的版本

本人使用的是：*numpy‑1.15.4+mkl‑cp37‑cp37m‑win_amd64.whl*

搜索下载安装：SciPy is

找到适合自己的版本

本人使用的是：*scipy‑1.2.0‑cp37‑cp37m‑win_amd64.whl*

管理员运行命令提示符  安装两个特殊的库

    pip install "numpy-1.15.4+mkl-cp37-cp37m-win_amd64.whl"
    pip install scipy-1.2.0-cp37-cp37m-win_amd64.whl

安装其他库

    pip install matplotlib ipython pandas scikit-learn


Numpy——基础科学计算库

Scipy——强大的科学计算工具集

pandas——数据分析的利器

matplotlib——画出优美的图形

scikit-learn——非常流行的python机器学习库
