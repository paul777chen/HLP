# Speaker Verification

> 这部分主要介绍输入一段话，辨别出是不是同一个人讲的：
>
> ![](png/sv1.png)

这种输入一段语音，输出分类有非常多的应用，比如：

![](png/sv2.png)

但这一部分主要关注在==语者验证（speaker verification）==上面。

## ① 与语者验证类似的问题

语者辨别（speaker recognition / speaker identification）

- 输入一段语音，判别是谁说的

![](png/sv3.png)

语者验证（speaker verification）

- 判断两段语音是否为同一个人所说

![](png/sv4.png)

语者分段标记（speaker diarization）

- 在一段语音中，判断谁在何时说话

![](png/sv5.png)

> 语者数目是否已知也可以划分为两种问题：
>
> - 语者数目已知：那就是将分割后的每段话进行分类（比如客服系统，判断一句话是客服讲的还是客户讲的）
> - 语者数目未知：那就是利用聚类的方式，来对相似的语音聚在一起

## ② 语者验证的评价指标

![](png/sv6.png)

- EER就是图中FFR=FN地方的值

## ③ Speaker Embedding

