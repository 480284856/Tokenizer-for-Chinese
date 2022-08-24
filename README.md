# tokenizer-for-Chinese
中文分词，只用到了numpy这个包。

实验效果：
```python
sentence = "我是顾小杰我今年二十岁我在巴基斯坦卖包子"
file_ngram = "人民日报96年语料.124-gram.word"
Tokenizer(file_ngram).encode(sentence)

['我是', '顾小', '杰', '我', '今', '年二', '十岁', '我在', '巴基斯坦', '卖', '包子']
```

依赖文件下载链接：https://cloud.189.cn/t/JRJFn2VNrmqy (访问码:2qee)，把人民日报96年语料.124-gram.word放到和ipynb文件同一个文件夹下即可运行。
