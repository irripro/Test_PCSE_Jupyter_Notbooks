[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/irripro/Test_PCSE_Jupyter_Notbooks/HEAD)


Comparison of crop modle LAI  under different natural, irrigation and fertilization conditions by PCSE

PCSE 灌溉、施肥条件下作物叶面指数对比

This Jupyter Notebook program will show how to run PCSE to realize the comparison of LAI index growth under different natural conditions, fertigation and crop.

本Jupyter Notebook 程序将展示如何运行 PCSE 实现灌溉施肥及自然条件下作物生长时的叶面指数对比。


For details of the original procedure, see: https://github.com/ajwdewit/pcse_notebooks, Allard de Wit, April 2018

For the example we will assume that data files are in the data directory within the directory where this notebook is located. This will be the case if you downloaded the notebooks from github.

例如，我们将假设数据文件位于该 Notebook 程序所在目录的 data 数据目录中。如果您从github下载笔记本，情况就会是这样。

	Prerequisites for running this notebook**

	运行此 Notebook 程序的环境条件* *

Several packages need to be installed for running PCSE/WOFOST:

运行PCSE/WOFOST需要安装几个软件包:

1.	PCSE and its dependencies. See the [PCSE user guide] for more information;
2. The `pandas` module for processing and storing WOFOST output;
3. The `matplotlib` module for plotting results
  
   1.` PCSE '及其依赖关系。有关更多信息，请参见 [PCSE user guide]《PCSE用户指南》；
   
   2.`pandas` 进程和储存 WOFOST 的输出；
   
   3.`matplotlib`用于生成图表。


Finally, you need a working internet connection.

最后，你需要一个有效的互联网连接。

*You will see that after using LINTUL3 model, the difference between irrigation and fertilization that tried to be displayed by Panda did not appear!  !  !

*你将会看到采用LINTUL3模型后，试图用 Panda 显示的灌溉、施肥的不同并没有出现！！！
