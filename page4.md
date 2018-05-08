# Results

## Sentiment Analysis
 
| State                      | California    | Arizona       |
| ---------------------------| ------------- | ------------- |
| Arithmetic mean sentiment  | 0.34          | 0.46          |
| Min                        | -2            | -1            |
| Max                        | 4             | 3             |
| Standard deviation         | 0.65          | 0.67          |
| Arithmetic mean polarity   | 3.30          | 3.36          |

 ![A Complicated History]({{ site.url }}/recreationalmarijuana/assets/images/Sentiment.png)

## Conclusion from Sentiment Anaysis
As can be seen, sentiment on the topic of marijuana use and the propositions for the legalisation of recreational use is very similar in both states. What is noteworthy in this sense, is that the arithmetic mean of the sentiment scores (which can vary from -10 for very negative articles to +10 for very positive articles) is only slightly positive and not in fact significantly different between the two reflecting the absence of a clear bias in any of the states. In fact, the arithmetic mean of the polarity score, which can be between 0 (lowest polarity) and 10 (highest polarity), is only just over 3 in both states. This explains the relatively low intensity of sentiment, with most articles having a sentiment score close to 0, reflecting a neutral standpoint. Considering this result, it cannot be stated that the different outcome of the votes in Arizona and California reflects a difference in sentiment on the topic in the media in both states.


## Conclusion on topic modeling:

We conclude that the topics ‘regulation’, ‘law and order’, ‘voting’ and ‘border control’ are interesting and well established. With the topic ‘judicial’ and ‘business’ we are more cautious and need to look into specific cases. We could not interpret ‘Religion and education’ and ‘event, lifestyle, education’ in a meaningful way. Furthermore, we had two other topics (number 9 and 10) which had no meaning at all. We labeled them as ‘none’.

<iframe src="https://documents.cortext.net/fffe/fffe099e8698415cab40fe230f8115fc/74482/vislda.html#topic=0&lambda=0.4&term=" frameborder="0" style="overflow:hidden;border:1px solid #DDDDDD;" width="1000" height="1000" allowfullscreen></iframe>



## Conclusion on Contingency Matrix:

All three topics ‘regulation’, ‘law and order’ and ‘judicial’ seem to be more frequent in the Californa newspapers than in Arizona. On the other hand, ‘voting’, ‘border control’ and ‘business’ is stronger represented in Arizona’s newspapers than in California’s.

<iframe src="https://documents.cortext.net/b8e2/b8e2acb9d23ef73e3a4e229fc48cc46a/74616/contingency_matrix-arizona-and-california-logFalse-Headline_custom_Region2-projection_cluster_LDA_Text_10-y-60_48-reordered-nFchi2.pdf" frameborder="0" style="overflow:hidden;border:1px solid #DDDDDD;" width="1000" height="1000" allowfullscreen></iframe> 

