# 百度问答 100 万数据集

```py
In [1]: import pandas as pd

In [2]: df = pd.read_excel(r'baidu_qa_100w_part1.xlsx')

In [3]: df
Out[3]:
                                                question                                             answer
0                                      人站在地球上为什么没有头朝下的感觉             地球上重力作用一直是指向球心的，因此\n只要头远离球心，人们就回感到头朝上。
1        我的小baby-辛巴。温顺可爱的，两个月大的小家伙，第一次养狗，该注意什么呢？求指教～[爱你]                                       勤洗澡，养成好的卫生习惯
2      小车和摩托车发生事故，在无红绿灯的十字路口，小停车看看左右，在觉得安全的情况下刹车慢慢以时速...  通过没有信号控制的十字路口，应该减速慢性，让右边的车先行，按你说的，摩托车好像在汽车的左边，...
3                                    松本面板可以配什么品牌的超五类模块??                                     AMP的试试吧，还有普 天的。
4                                                  有什么方法  先用清水冲一下,在用食盐反复的搓揉,直到肠的黏液全去掉为止,在用清水反复冲洗干净,最好把肠上...
...                                                  ...                                                ...
99995  我很喜欢吃冰的东西，一到夏天更是。一口气喝一瓶冰！冰淇淋也吃很多。\n最近得了炎症，一直没好...        不要紧，但任何东西都不能吃得太多，要适可而止，有句俗话说得好：少吃多滋味、多吃坏肚皮。
99996                              今天大盘指数很高，是不是危险也同样增加了？  今天我买的4支股票出现拐点~本来还赚5%，可惜早上忙工 作没顾上，不然就抛了，现在被套住了，我...
99997  BeihaiParkneofthemostbeautifulparks______ atwe...  这是一道有关定语从句关系代词的考查题，确定关系代词that或which，要注意that的特殊...
99998                          为什么我一到晚上就会看不清黑板上的字呢？有哪些原因  没有什么大的问题。有可能是色差辨别差一点。或少 许有夜盲的现象。只要事内光线足就不会出现象你这...
99999                  当甘油溶液中溶质的质量分数为80%时护肤效果最佳.欲配制50克8?                      甘油：50克*80%=40克\n水：50克-40克=10克

[100000 rows x 2 columns]
```