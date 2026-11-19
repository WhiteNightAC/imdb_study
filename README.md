# IMDB 实验

实验基于 Kaggle **Bag of Words Meets Bags of Popcorn / Word2Vec NLP Tutorial** 的 IMDB 电影评论情感分析项目。
## 数据集

数据来自 Kaggle 的 [Word2Vec NLP Tutorial](https://www.kaggle.com/competitions/word2vec-nlp-tutorial)。

数据文件包括：

- `labeledTrainData.tsv`：带情感标签的训练评论。
- `unlabeledTrainData.tsv`：无标签评论。
- `testData.tsv`
- `sampleSubmission.csv`：提交格式示例。

## 一、word2vec实验
进行了Random Forest、平均词向量 + Random Forest、聚类 + Random Forest的实验。通过kaggle对预测结果进行评分。结果如下
| 排名 | 模型 | 得分 |
| ---: | --- | ---: |
| 1 | Random Forest | 0.84248 |
| 2 | 平均词向量 + Random Forest | 0.83316 |
| 3 | 聚类 + Random Forest | 0.78620 |

## 二、cnn
cnn、cnn+lstm实验，kaggle score如下
| 排名 | 模型 | 得分 |
| ---: | --- | ---: |
| 1 | CNN | 0.96532 |
| 2 | CNN + LSTM | 0.93863 |

## 三、lstm
lstm、lstm+attention、capsule+lstm实验，kaggle score如下
| 排名 | 模型 | 得分 |
| ---: | --- | ---: |
| 1 | Attention + LSTM | 0.96308 |
| 2 | Capsule + LSTM | 0.95790 |
| 3 | LSTM | 0.93578 |
## 四、gru
gru kaggle score 如下
| ---: | --- | ---: |
|1|GRU | 0.96128 |
## 五、transformer
transformer kaggle score 如下
| Transformer | 0.95691 |
## 六、bert
进行了bert_scratch、bert_native、bert_trainer实验，kaggle score如下
| 排名 | 模型 | 得分 |
| ---: | --- | ---: |
| 1 | bert trainer | 0.97541 |
| 2 | bert native | 0.97339 |
| 3 | bert_scratch | 0.94703 |

## 七、roberta
roberta kaggle score 如下
| RoBERTa（Trainer） | 0.98360 |
## 数据汇总
| 排名 | 模型 | 得分 |
| ---: | --- | ---: |
| 1 | RoBERTa（Trainer） | 0.98360 |
| 2 | BERT（Trainer） | 0.97541 |
| 3 | BERT（Native） | 0.97339 |
| 4 | DistilBERT（Trainer） | 0.97099 |
| 5 | DistilBERT（Native） | 0.96989 |
| 6 | CNN | 0.96532 |
| 7 | Attention + LSTM | 0.96308 |
| 8 | GRU | 0.96128 |
| 9 | Capsule + LSTM | 0.95790 |
| 10 | Transformer | 0.95691 |
| 11 | BERT（从零训练） | 0.94703 |
| 12 | CNN + LSTM | 0.93863 |
| 13 | LSTM | 0.93578 |
| 14 | Random Forest | 0.84248 |
| 15 | 平均词向量 + Random Forest | 0.83316 |
| 16 | 聚类 + Random Forest | 0.78620 |

