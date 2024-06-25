# Intogo
Intogo自动注射车


## 主要包括数据：

| 总耗时	| 注射人数 | 注射剂量 | 注射间隔 |实际总药量 | 预测总药量	|  
| 206.55| 26	  |  266.73  |  8.26   | 15189.39 | 14331.31    |

<img width="983" alt="image" src="https://github.com/wang-zixia/Intogo/assets/153195196/72cac08a-ab51-471a-a8e0-bcd1a17f6fa6">

>此处实际总药量及预测总药量均为从第一个病人打针时开始的总剂量并减去残留药量，既为最真实最理想的用药量。

详细见附表1；

## 进度条数据：

<img width="993" alt="image" src="https://github.com/wang-zixia/Intogo/assets/153195196/cc49e783-2fc8-4fd1-8a61-f9eb36de4249">

>此处进度0%为实际工作中最开始的剂量，并非从第一个病人开始的总剂量。
>
>ps:因为有时候装上药半个小时都没打针，有时候会浪费100mCi的药，最为理想的状态为装上药就开始打针。
>
>因为剂量越大衰变越快，使用平均间隔时间来处理衰变计算对起初的剂量计算较为不准，我在想使用进度来处理衰变计算是否可行？
>
>例如，平均间隔时间为8分钟的话，那么刚开始的8分钟衰变的剂量肯定要远远大于快结束时8分钟衰变的剂量。
>
详细见附表2；

## python计算代码
详细见forecast.py;
