# 尝试
自己尝试用Python做了次爬虫+数据可视化
对腾讯的全国疫情地图进行爬取，挑选了上海地区的疫情数据，然后使用pyecharts的map模块进行数据可视化.

腾讯会不断地变更URL信息，以及疫情的数据存储结构，所以不能保证代码始终有效

# 第一次优化
腾讯改动了上海区县的前后顺序，导致数据与区县不对应，现在根据规律对区县名称进行了处理，如浦东+新区，崇明+县，其余地区+区
