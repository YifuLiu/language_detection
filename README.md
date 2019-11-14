# language detection
A total of 31 test data for multiple language detection: the different length of test data per language is created based on the Leipzig Corpora Collection: http://wortschatz.uni-leipzig.de/en/download and the word vectors we use is from the paper of "Learning Word Vectors for 157 Languages"(https://arxiv.org/abs/1802.06893) and the actual word vector data location: https://fasttext.cc/docs/en/crawl-vectors.html

The dataset is created by the clustering method of Kmeans and visualization method of TSNE to check if the Kmeans clustering make sense or not. The purpose of this test dataset is to evaluate different language detection tool: such as google translation, aws comprehend, etc.

<img src="https://github.com/YifuLiu/language_detection/blob/master/language_code.png" width="450">
