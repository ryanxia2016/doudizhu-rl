# 模型测试

DHCP是rule based model，用来训练网络的模型，且训练的都是地主。

每个模型进行了1000轮测试，胜率如下所示。

| 开始训练时utc时间 | 训练第n次结果 | 对抗random胜率 | 对抗DHCP胜率 |
| --- | --- | --- | --- |
|0802_1036|78500_44|85|37.9|
|0803_0159|8000|83|37.7|
|0803_0349|2900_48|93.2|53.7|
|0803_0349|5300_54（开始过估计）|91.7|49.6|
|0803_0349|8000|90.8|47.8|
|0803_0349|10000|89.2|42|