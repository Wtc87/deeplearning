2019.06.18

代码均使用python语言。

在jupyter notebook中运行。

下面按照报告内容步骤运行程序：

1 爬虫爬取数据

首先运行spider.ipynb爬虫程序（请保证网络连接）,将会在代码所在文件夹得到csv格式的数据文件（数据文件在压缩包中已有，重新爬取也可以）。
爬虫程序有时运行一次可能爬取的数据不完全，可以多爬取几次。（特别的有时2019_06月份数据爬不到，要先去官网把6月份的地址打开再爬取就能爬到了。）

2 随机森林回归模型

运行RandomForest_code.ipynb程序。得到结果。（数据和程序放在同一文件夹）

3 多变量LSTM预测模型

运行LSTM_code.ipynb程序。得到结果。（数据和程序放在同一文件夹）



###文件中数据说明：###

苏州.csv文件即为spider.ipynb爬虫程序爬取的完整数据文件。
苏州-6.csv为RandomForest_code.ipynb程序所需要的文件，即为苏州.csv文件保留2019年6月份数据其余数据均删除。（手动操作）
forecast.csv文件为LSTM_code.ipynb程序中所需要的文件，即为苏州.csv文件保留2018年6月15-25日的数据其余数据均删除。（手动操作）
result_reg_city.txt为运行RandomForest_code.ipynb程序得到的结果文件，报告中有说明。






