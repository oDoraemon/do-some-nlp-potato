# Basic NLP算法模型demo
数据建模做特征工程的时候可能会需要使用简单的文本特征，因此研究相关算法并做一些demo，了解算法思想和特性。

## 1.三国演义文本特征
从网上下载的三国演义txt文档，通过词袋模型统计相关特征。尝试通过Word2Vec处理，但输出结果有些莫名奇妙。似乎不太适用于中文文本？

### $todo
* 词频可视化
* 创建语料库，做词过滤
* 使用tfidf模型，查看权重