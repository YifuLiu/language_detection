# language detection
A total of 31 test data for multiple language detection: the different length of test data per language is created based on the Leipzig Corpora Collection: http://wortschatz.uni-leipzig.de/en/download and the word vectors we use is from the papaer of "Learning Word Vectors for 157 Languages"(https://arxiv.org/abs/1802.06893) and the actual word vector data location: https://fasttext.cc/docs/en/crawl-vectors.html

The dataset is created by the clustering method of Kmeans and visualization method of TSNE to check if the Kmeans clustering make sense or not. The purpose of this test dataset is to evaluate different language detection tool: such as google translation, aws comprehend, etc.


![alt text](https://github.com/YifuLiu/language_detection/language_code.png)

English                                                              en

Spanish (Spain, Latin America)                                       es

German (Germany, Austria, Switzerland)                               de

French (France, Canada, Belgium, Switzerland, Morocco, etc.)         fr

Chinese, Simplified (People’s Republic of China)                     zh

Chinese, Traditional (Taiwan)                                        zh-tw

Korean (South Korea)                                                 ko

Japanese (Japan)                                                     ja

Italian (Italy, Switzerland, etc.)                                   it

Portuguese (Brazil, Portugal)                                        pt

Arabic (North Africa, West Asia)                                     ar

Turkish (Turkey, Cyprus)                                             tr

Thai (Thailand)                                                      th

Polish (Poland)                                                      pl

Russian (Russian Federation, various former USSR)                    ru

Hebrew (Israel)                                                      he

Dutch (Netherlands, Belgium, South Africa)                           nl

Bahasa Malaya (Malaysia)                                             ms

Bahasa Indonesia (Indonesia)                                         id

Swedish (Sweden)                                                     sv

Finnish (Finland)                                                    fi

Hindi (India)                                                        hi

Czech (Czech Republic)                                               cs

Norwegian (Norway)                                                   no

Danish (Denmark)                                                     da

Croatian (Croatia)                                                   hr

Greek (Greece, Cyprus)                                               el

Romanian (Romania)                                                   ro

Hungarian (Hungary)                                                  hu

Farsi (Iran)                                                         fa

Slovak (Slovakia)                                                    sk
