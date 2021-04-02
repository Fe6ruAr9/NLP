# What is NLP
- NLP = NLU(Understanding) +NLG(Generation)

### Noisy-Chanel Model
- Chinese —— *Statistical Analysis(Chinese/English Bilingual Text)* —— Broken English —— *Statistical Analysis(English Text)* —— English

### Basic Task
- Tokenization(Word Segmentation)
- POS
- NER
- Syntatic Analysis
- Semantic Analysis

#### Word Segmentation
- Forward-max matching(前向最大匹配)
  - e.g 我们经常有意见分歧 max_len
  - 词典: ['我们','经常','有','有意见','意见','分歧'] 

- Question
  - Local Method (greedy)
  - OOV (out of vocabulary)
  - Semantic

- Algorithm
  - Jieba (github.com/fxsjy/jieba)
  - SnowNLP
  - LTP
  - HanNLP 

#### POS(Part of Speech) Tagging
- 依赖当前单词以及它的上下文信息
- 词性标注 aka 序列标注 (Sequence Labeling)
  - 利用概率表示序列
  - 考虑单词之间的前后依赖关系
  - 常见算法：
    - 隐马尔科夫模型(Hiddem Markov Model)
    - 条件随机场(Conditional Random Fields)

#### Syntatic Analysis
- 如何理解一个单词的意思
- 如何理解一个文本的意思
