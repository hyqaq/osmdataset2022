# osmdataset2022
##Note
This data set is only used for academic exchanges and scientific research, and cannot be used for other commercial purposes or for purposes that infringe the rights of other organizations and individuals
#### Brief description of the dataset
This is a dataset about online social movements in Chinese which crawled from Sina Weibo.

The task of this dataset is to accurately classify sentiments, especially focusing on minority categories, because these two sentiments are particularly important in online social movements.
#### Dataset statistics
We crawled the comments of four online group events and two normal events in recent five years and divided them into four categories, as listed below:
| sentiment | training set |     test set | proportion (%) |label|
| :----- | :--: | :--: |:---: |:---: |
| positive |  4113  | 1039 |37.3|0|
| weak negative |  5603  | 1421 |50.9|1|
| anger |  769  | 180 |6.87|2|
| anxiety |  560  | 122 |4.94|3|


The ratio of class imbalance in this dataset is 10.3 which means that this dataset is an especial imbalanced one.

Here are examples of comments in the dataset.
| **comment** | **label** | 
| :----------------------------------------------------------------- | :--: |
| 孩子出事，学校单方面瞒着第一时间送去殡仪馆？学校有什么权利不让家长进校门见孩子？不让家长了解孩子出事的原因？学校还把监控视频删掉了？还态度蛮横说舆论和法律都不怕？回到古代了？恶霸横行天下？没钱没权人死了连申冤的地方都没有？                                                                    |   3   |
|时间、地点、人物，事情的起因、经过和结果！这都是老师教我们的！你们公然背叛？真相是啥！欲盖弥彰！滑天下之大稽！实在是可气！可笑！可耻！可恨！                                                      |     2 |
|                    监控缺失是基本操作，呵呵                                                 |    1  |
|                   希望学校还原事情真相让事件不要复杂化引起社会舆论压力。                                               |     0 |

