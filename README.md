===============================================
在使用示例代码之前请务必阅读
===============================================

●关于示例代码
　示例代码是用Jupyter Notebook的形式准备的，为本书第2~22章正文中介绍过的示例文件。

●本书示例代码的测试环境
　本书示例代码在以下环境中运行。

OS：Windows 10
Python：3.6.1
Anaconda：5.2.0
浏览器：Google Chrome

●软件库的安装
　按本书0.1.1节中的方法安装了Anaconda Navigator之后，参照0.1.2节，启动Anaconda Navigator附带的命令提示符，按照0.1.3节的方法在虚拟环境中执行以下命令。

-------------------------------
conda install jupyter
conda install matplotlib==2.2.2
pip install scikit-learn==0.19.1
pip install tensorflow==1.5.0
pip install keras==2.2.0
-------------------------------

　其他需要的库如表0.1所示，请用以下命令安装（参照0.1.3节）。

-------------------------------
conda install <库名>==<版本名>
-------------------------------

库名	版本名
-------------------------------
opencv	3.4.2
pandas	0.22.0
pydot	1.2.4
requests	2.19.1
▲表 0.1：库名和版本名

●Anaconda的版本
　在编写本书时（截至2018 年 9 月），使用的是“Anaconda3-5.2.0-Windows-x86_64.exe”。图0.1中提供的版本可能会根据下载时间的不同而有所不同，但是使用最新版本的程序学习本书，基本上也没有问题。如果想使用与本书相同的环境，请从以下网站指定版本下载（参照本书P.7页的说明）。

・Anaconda installer archive
 URL https://repo.continuum.io/archive/

●示例数据列表
　示例数据的文件夹配置如下。

ShinsouGakushu_sample
    +-- Chapter2_sample.ipynb【第2章的数据】
    +-- Chapter3_sample.ipynb【第3章的数据】
    +-- Chapter4_sample.ipynb【第4章的数据】
    +-- Chapter5_sample.ipynb【第5章的数据】
    +-- Chapter6_sample.ipynb【第6章的数据】
    +-- Chapter7_sample.ipynb【第7章的数据】
    +-- Chapter8_sample.ipynb【第8章的数据】
    +-- Chapter9_sample.ipynb【第9章的数据】
    +-- Chapter10_sample.ipynb【第10章的数据】
    +-- Chapter11_sample.ipynb【第11章的数据】
    +-- Chapter12_sample.ipynb【第12章的数据】
    +-- Chapter13_sample.ipynb【第13章的数据】
    +-- Chapter14_sample.ipynb【第14章的数据】
    +-- Chapter15_sample.ipynb【第15章的数据】
    +-- Chapter16_sample.ipynb【第16章的数据】
    +-- Chapter17_sample.ipynb【第17章的数据】
    +-- Chapter18_sample.ipynb【第18章的数据】
    +-- Chapter19_sample.ipynb【第19章的数据】
    +-- Chapter20_sample.ipynb【第20章的数据】
    +-- Chapter21_sample.ipynb【第21章的数据】
    +-- Chapter22_sample.ipynb【第22章的数据】
    +--cleansing_data【第15章中使用的图像文件】
    +-- README.doc【本文件】

