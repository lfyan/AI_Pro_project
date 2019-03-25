***Fata already built the framework. There are some areas we can play with to improve. ***

TODO list:
1. In training data, 6% is labelled as 1. So 1 and 0 are not in balanced. Try to duplicate sentences which is labelled as 1 to make the ratio to around 50:50.

2. Currenly the glove we use is glove.6B/glove.6B.100d.txt. Some words cannot be found in this glove. For example, the max length of sentences is > 100 words before glove. After glove the max is 78.  Play with other glove version to see whether this can be improved.

3. Fata includes a "wordcloud" part. We can explore it for fun :)

** add any if you can think of
