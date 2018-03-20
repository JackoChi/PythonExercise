Jeopardy is a popular TV show in the US where participants answer questions to win money. 
It's been running for a few decades and is a major force in popular culture. 
The dataset is named jeopardy.csv, and contains 20000 rows from the beginning of a full dataset of Jeopardy questions.

I first normalized text and columns, then I realized that only 6% answers were deduced from the question by using 
the repeated words in both answer and question. Similarly, I figured out that There is about 70% overlap between 
terms in new questions and terms in old questions. I computed the chi-squared value based on the expected counts 
and the observed counts for high and low-value questions. None of the terms had a significant difference in usage 
between high value and low-value questions. Additionally, the frequencies were all lower than 5, so the chi-squared 
test isn't as valid. It would be better to run this test with only terms that have higher frequencies.


Jeopardy是美国一个受欢迎的电视节目，参与者回答问题以赢取金钱。
它已经运行了几十年，是流行文化的主要力量。该数据集名为jeopardy.csv，并且包含从Jeopardy问题完整数据集开始的20000条数据。

我首先将文本和列标准化，通过查询在问题和答案中使用重复的单词我意识到只有6％的答案是通过问题推导出来的。 
同样，我发现新问题和旧问题中的术语之间约有70％的重叠。我根据预期计数和高价值和低价值问题的观察计数来计算卡方值。
没有一个术语在高价值和低价值问题的使用上有显着差异。此外，这些频率都低于5，所以卡方检验不是有效的。使用频率更高的术语运行此测试将会更好。


