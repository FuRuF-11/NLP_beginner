此项目用于完成邱锡鹏老师的[nlp-beginner项目](https://github.com/FudanNLP/nlp-beginner)。

github上也有很多相关的实现，但是都和我想象中的实现都不太一样，有些没有完全按照原要求来写、还有一些实现的写法不是很通用。

故在此分享自己的一种实现，欢迎大家提issue。
 + task1:(done)，使用纯numpy实现BOW\N-gram文本表示、softmax回归、mini-batch SGD、特折选择，效果比sklearn原生的logistics回归效果好。
 + task2:(done)，实现了随机向量初始化、word2vec、GloVe三种方式的词嵌入，使用pytorch搭建了一个TextCNN和RNN对文本进行分类。由于数据量较大，建议使用GPU。
 + task3:(done)，使用融合了双向的token2token attention的ESIM实现。数据较大，仅使用其中的一部分进行训练。
 + task4:(doing)，
 + task5:(doing)，