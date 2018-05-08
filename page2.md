# Methodology

## Comparative Study


TEXT NEEDED


# Why we chose AZ and CA:

- Neighboring states
- While CA is 5 times the size of AZ (population), they have similar demographics, specially in terms of growth and minority makeup. 
- Both deal with a Mexican border which is a significant narrative related to marijuana usage i.e. its connection to organized crime
- They both passed medical marijuana laws through a voter referendum in 1996 (albeit one that ended up being useless in AZ because of state legislator  
- Both had 2016 rec marijuana prop on ballot that were quite similar ie possession, sale, tax, regulation, and cultivation
- That said, they also have significant ideological differences. AZ is seen as one of the most conservative law and order states in the country. That said, AZ, is generally more conservative than CA. 

![Map of US States and Laws]({{ site.url }}/recreationalmarijuana/assets/images/marijuana_laws.0.png.jpeg)


## Research Objective
At the example of recreational marijuana legalisation in the United States, we analyse the effect of media on voters behaviour. The main rationale behind such an analysis is that voters are deciding on the basis of information provided through media, and are therefore  not only affected by the choice of media source through which they stay up to date, but also through the overall presentation of information by different media sources.

We therefore look at the correlation between how media sources talk about political issues and the voter’s behaviour and thus poll outcomes.

## Corpus Collection

![A Complicated History]({{ site.url }}/recreationalmarijuana/assets/images/Screen Shot 2018-05-08 at 6.13.30 PM.png)

Four our research, we needed to collect a corpus large enough to be able to use data analysis tools. As such, we were presented with a few different options. The first one, considering the political nature of the topic, was of course Twitter, which hosts a large number of individual statements with a generally high subjectivity score. However, collecting a corpus of Tweets would have presented a number of issues that ultimately had us reject it as source for our corpus. Firstly, it would have been nigh impossible to filter the Tweets by region. Our research is limited to the political sentiment regarding decisions in California and Arizona and tweets on the same topic from other regions would have made it impossible to single out developments in these States. Furthermore, it would have been more difficult to separate the discussion on these specific proposals from wider discussions on Marijuana policy in the country, as many tweets on the topic of these referendums do not include a specific reference to the decisions we were looking to study.

As such, we decided to collect our corpus through Factiva. This is a website aggregating articles from a large number of both licensed and free media sources from across the world. This tool, provided by Dow Jones & Company since 1999 is the world’s leading database for news research. This tool notably allowed us to specifically target media sources from California and Arizona respectively through the use of the ‘source’ option in the search engine, which allows to filter the search results based on the American State (or other region) the source of the article is based in.

Furthermore, we decided to use as our search terms for extracting articles from this database a number of synonyms of the word marijuana, so as to incorporate all the discussion in this state on the topic of marijuana consumption so as to be able to analyse which developments are perceived to be linked to the decisions at hand, as well as the wider sentiment on the topic of marijuana use in these states. On top of this, we included references to the specific decisions, by using the number of the proposition as a search term in each state.

As such, we used the following search terms for the collection of articles from California:
- cannabis or marijuana or marihuana or hashish or thc or weed or cbd or splif or indica or sativa or cannabinoid or "proposition 64”
And from Arizona: 
- cannabis or marijuana or marihuana or hashish or thc or weed or cbd or splif or indica or sativa or cannabinoid or "proposition 205”

As our analysis only concerns these specific decisions, which were both taken on the 8th of November 2016, the same day as the US presidential elections, we limited our search to articles published in the two years leading up to this date until one month after this date (8 November 2014 – 8 December 2016). As such, we ensured discussions on earlier decisions were not taken into account, while also allowing for the inclusion of those articles representing the reaction to the votes in the two states. 
Lastly, we excluded obituaries from our search, as an initial analysis had shown that many articles were in fact obituaries published following deaths in a town that includes the word ‘weed’ in its name.
This search gave us the following corpus:

| State                      | California    | Arizona       |
| ---------------------------| ------------- | ------------- |
| Number of unique articles  | 2275          | 456           |
| Number of words (fulltext) | 1,549,247     | 328,295       |
| Number of sources          | 22            | 3             |
  
 
## Limits to Corpus
It is important to note that the Arizona corpus is significantly smaller than the California corpus, both in terms of the number of articles and the number of sources. Three sources is an especially low number and this lack of representativeness should be considered as an important disclaimer regarding the conclusions that can be drawn from the analysis carried out on this corpus.

## Sentiment Analysis
As we sought to discover the underlying reasons that led to the proposition on the legalisation of recreational marijuana being rejected in Arizona, while being accepted in neighbouring California on the same date, our first analysis was a simple sentiment analysis on the articles collected. This sentiment analysis was carried out using the sentiment analysis script in Cortext and was done separately for California and Arizona, so as to allow an easy comparison of the results. These are presented in the figures below:
 
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



