# Results

## Conclusion from Sentiment Anaysis
As can be seen, sentiment on the topic of marijuana use and the propositions for the legalisation of recreational use is very similar in both states. What is noteworthy in this sense, is that the arithmetic mean of the sentiment scores (which can vary from -10 for very negative articles to +10 for very positive articles) is only slightly positive and not in fact significantly different between the two reflecting the absence of a clear bias in any of the states. In fact, the arithmetic mean of the polarity score, which can be between 0 (lowest polarity) and 10 (highest polarity), is only just over 3 in both states. This explains the relatively low intensity of sentiment, with most articles having a sentiment score close to 0, reflecting a neutral standpoint. Considering this result, it cannot be stated that the different outcome of the votes in Arizona and California reflects a difference in sentiment on the topic in the media in both states.

### Sentiment Analysis
 
| State                      | California    | Arizona       |
| ---------------------------| ------------- | ------------- |
| Arithmetic mean sentiment  | 0.34          | 0.46          |
| Min                        | -2            | -1            |
| Max                        | 4             | 3             |
| Standard deviation         | 0.65          | 0.67          |
| Arithmetic mean polarity   | 3.30          | 3.36          |

 ![A Complicated History]({{ site.url }}/recreationalmarijuana/assets/images/Sentiment.png)


## Conclusion on Topic Modeling

We identified and interpreted 8 different topics and conclude that the topics ‘regulation’, ‘law and order’, ‘voting’ and ‘border control’ are interesting and well established. With the topic ‘judicial’ and ‘business’ we are more cautious and need to look into specific cases. We could not interpret ‘religion and education’, and ‘event, lifestyle, and education’ in a meaningful way. Furthermore, we had two other topics (number 9 and 10) which had no meaning at all. We labeled them as ‘none’.

### Topic Modeling

We identified and interpreted 8 different topics. Relevance metric was kept at λ=0.4.


##### 1) Regulation
20 most relevant words: *marijuana, medical, dispensary, city, cannabis, pot, would, said, use, measure, law, recreational, council, patient, initiative, legal, state, cultivation, regulation, ordinance*

Words such as *dispensary*, *medial*, *measure*, *law*, *council*, *initiative* or *legal* lead us to interpret this topic as regulation centered. One can imagine that the discourse about recreational marijuana legalisation triggered questions such as how recreational marijuana is administered (who will administer and under what regulatory framework), who will have access, under which circumstances one will have access (what medical problems) and so on.

At the same time, this topic contains some noise such as *would* or *said*. However, we considered this noise of being relatively small and thus think the ‘Regulaion’ topic has high explanatory value.

##### 2) Law and Order
20 most relevant words: *fire, police, said, man, arrested, reported, vehicle, block, officer, deputy, found, country, suspect, suspicion, road, stolen, authority, sheriff, crash, shasta*

Words such as *police*, *arrested*, *officer*, *deputy*, *suspect*, *stolen* or *sheriff* lead us to interpret this topic as centered around domestic law and order. It is marked by the discussion of how order can be sustained even with a partial legalisation of a drug. It could be driven by fears that recreational marijuana legalisation would attract additional crime and thus needs close supervision. Also news about crimes with possession of marijuana fall in this topic.

Noise is very low in this topic. It consists of the usual words such as *said* or *near*. We thus conclude that this topic has high explanatory value.

##### 3) Religion and Education 
20 most relevant words: *student, it, school, church, people, life, like, thing, kid, im, me, know, get, really, he, cook, love, there, thought, say*

No clear pattern can be identified in this topic. It seems to contain two different topics, one marked by education (*student*, *school*) and one marked by religion (*church*, *christian*).

Furthermore, this topics contains a high amount of noise words which cannot be successfully classified, such as *people*, *like*, *thing*, *know*, *get*, *really*, *he*, *there* or *say*. We thus conclude that this topic has only limited explanatory value.

##### 4) Voting
20 most relevant words: *percent, republican, voter, trump, candidate, poll, political, democrat, state, vote, election, yes, senate, clinton, housing, environmental, tax, democratic, campaign, sander*

Words such as *republican*, *voter*, *candidate*, *poll*, *political*, *vote*, *election* or *campaign* led us to interpret this topic as centered around voting processes. Ideally, this topic is all about how the voting outcome has been for the laws aiming at recreational marijuana legalisation, or about forecasts for future voting.

This topic contains a relatively small amount of noise words. We thus think that the voting topic has high explanatory value.

##### 5) Business
20 most relevant words: *company, article, business, executive, firm, journal, anacstpd, bizjournalscomsubscribe, 18668533661, useful, partner, investment, technology, capital, investor, ceo, visit, chairman, president*

Words such as *company*, *business*, *firm*, *investment* or *capital* lead us to conclude that this topic is centered around a business aspect. It could be about how much revenue recreational marijuana would generate, what kind of businesses would be allowed to produce marijuana, what prices it would be sold or what market design recreational marijuana should have.

This topic contains few, but extraordinary noise words, such as *bizjournalscomsubscribeI* or *18668533661*. We thus conclude that this topic has high explanatory value, are however cautious about its interpretation.

##### 6) Event, Lifestyle, and Enviroment
20 most relevant words: *tree, plant, weed, event, redding, festival, music, pm, soil, water, band, ave, saturday, spring, garden, feature, painting, st, concert, book*

Words like *event*, *festival*, *music* and *band* seem to suggest that it contains festivals or free time activities. Also *garden* and *painting* would point in this direction. However, there are also words which could point at the cultivation of cannabis or its environmental impact, such as *plant*, *three*, *water* or *soil*. Because the topic is not clear but noise words are only a few, we conclude that this topic has medium explanatory value.

##### 7) Judical
20 most relevant words: *prosecutor, capello, trial, video, murder, inmate, nayen, jail, attorney, dwyer, pappa, joseph, testified, escape, judge, raid, lopez, prison, testimony, court*

World like *prosecutor*, *trial*, *murder*, *inmate*, *jail*, *attorney*, *testified*, *judge*, *testimony* or *court* let us to conclude that this topic is mostly about judicial affairs. It could be closely related to the ‘law and order’ topic.

This topic however contains a considerable amount of noise words, such as *video*, *nayeri*, *dwyer*, *pappa* or *joseph*, which makes it rather difficult to interpret clearly. We thus conclude that this topic has only medium explanatory value.

##### 8) Border Control
20 most relevant words: *border, agent, drug, fence, patrol, marinovich, mexico, drone, nogales, mexican, smuggling, seized, cocaine, sector, enforcement, offender, rancher, sonora, cbp, tucson*

Worlds like *border*, *drug*, *fence*, *patrol*, *mexico* or *smuggling* leads us to conclude that this topic talk about border issues such as illegal traffic. It is rather clear in this respect, with only little noise words or words pointing at a different interpretation of this topic. We thus conclude that it has high explanatory value.

##### 9) and 10) no relevant topic
We did not find any pattern for these topics. One seems to contain Spanish words, the other seems to contain only noise words. We thus excluded these two topics from our further analysis by labelling them with 'none'.


<iframe src="https://documents.cortext.net/fffe/fffe099e8698415cab40fe230f8115fc/74482/vislda.html#topic=0&lambda=0.4&term=" frameborder="0" style="overflow:hidden;border:1px solid #DDDDDD;" width="1000" height="1000" allowfullscreen></iframe>



## Conclusion on Contingency Matrix

All three topics ‘regulation’, ‘law and order’ and ‘judicial’ seem to be more frequent in the Californa newspapers than in Arizona. On the other hand, ‘voting’, ‘border control’ and ‘business’ is stronger represented in Arizona’s newspapers than in California’s.

### Contingency Matrix

<iframe src="https://documents.cortext.net/b8e2/b8e2acb9d23ef73e3a4e229fc48cc46a/74616/contingency_matrix-arizona-and-california-logFalse-Headline_custom_Region2-projection_cluster_LDA_Text_10-y-60_48-reordered-nFchi2.pdf" frameborder="0" style="overflow:hidden;border:1px solid #DDDDDD;" width="1000" height="1000" allowfullscreen></iframe> 

