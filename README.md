# 淘宝用户行为分析

**项目简介**：本项目基于阿里巴巴开源的淘宝用户数据集，模拟电商平台的用户行为分析，目标是理解用户在电商平台的行为模式（浏览、点击、加购、购买），并提出优化用户转化和留存的可行性建议。

**数据来源**：[User Behavior Data from Taobao for Recommendation](https://tianchi.aliyun.com/dataset/649)

**数据描述**：

本数据集包含了2017年11月25日至2017年12月3日之间，有行为的约一百万随机用户的所有行为（行为包括点击、购买、加购、喜欢）。数据集的组织形式和MovieLens-20M类似，即数据集的每一行表示一条用户行为，由用户ID、商品ID、商品类目ID、行为类型和时间戳组成，并以逗号分隔。关于数据集中每一列的详细描述如下

**和鲸社区项目链接**：本项目已经被同步到了和鲸社区，本文附上和鲸社区的项目链接 - [【Python 实战】基于Pandas和Tableau的淘宝用户行为数据分析](https://www.heywhale.com/mw/project/68cfb1f9853e90cb3fbe1e7f)

**文件说明**：

1. [data_preprocessing.ipynb](./data_preprocessing.ipynb) - 最初探索阶段的数据预处理，抽样了10%的用户数据用于后面的分析。
2. [project_small_data.ipynb](./project_small_data.ipynb) - 使用抽样数据做的初步分析
3. [project_pyspark](./project_pyspark.ipynb) - 使用PySpark对全部数据进行数据分析，测试运行速度。
4. [final_notebook](./final_notebook.ipynb) - 最终的数据分析报告，使用了Pandas进行数据处理。

**使用方法**：

到数据来源（[User Behavior Data from Taobao for Recommendation](https://tianchi.aliyun.com/dataset/649)）下载淘宝用户行为数据，或者到和鲸社区项目链接中（[淘宝用户行为](https://www.heywhale.com/mw/dataset/68cf5bba17bbff346b6f7907/file)）下载数据，并将**UserBehavior.csv**文件保存在**data**目录下，即可执行代码文件。
