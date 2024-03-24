# Article-Recommendation-System
This is a github repository for recommending BBC news articles, and here's the link to the Medium article I wrote about it: https://medium.com/@rithvikdonnipadu/article-recommendation-system-cc992e456de5

Here's a brief of what the code looks like:

1. Convert the text into n*300 dimensional GloVe vectors
2. Calculate their centroid by taking a column wise mean, which gives us a 1*300 dimensional vector
3. For each article, compute the euclidean distances between all the other articles
4. The top 5 articles with the least distance are the ones to recommend!

References:
1. D. Greene and P. Cunningham. “Practical Solutions to the Problem of Diagonal Dominance in Kernel Document Clustering”, Proc. ICML 2006.
2. Thanks to Professor Yannet’s repository! https://github.com/yanneta/msds692
