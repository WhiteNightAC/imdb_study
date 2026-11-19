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


## 三、lstm

## 四、gru

## 五、transformer

## 六、bert

## 七、roberta

## 数据汇总
