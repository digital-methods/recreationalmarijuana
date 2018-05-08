# Methodology

## Research Objective
Using the example of recreational marijuana legalisation in the United States, we analysed the connection between media and voter behaviour. The main rationale behind such an analysis is that voters are making decisions on the basis of information, and that this information is often provided through media. They therefore may be affected by the choice of media source through which they stay up to date i.e.through the overall presentation of information by different media sources.

Overall, our goal was to look at the correlation between how media sources talk about marijuana related topics, and thus political issues, and how that might affect voter behaviour, and vice versa by:

- Finding and analyzing the important topics being discussed surrounding the legalization of marijuana. specifically in newspapers.
- Comparing different states’ public discussion of the issues through media, specially as it pertains to states who pass legislation vs those where legislation fails.


## Comparative Study


We chose two states in the US (Arizona and California) to conduct a comparative study. The rationale behind such an approach was to isolate third variable effects. In assuming that both states are similar with regard to third variables such as population, interest groups, political mechanisms and so on, we isolated the effect media could have on the population.

Despite the fact that the similarity assumption needs further investigation, the next paragraph will discuss the advantage of our choice of states.

### Why AZ & CA?

- Neighboring states
- While CA is 5 times the size of AZ (population), they have similar demographics, specially in terms of growth and minority makeup. 
- Both deal with a Mexican border which is a significant narrative related to marijuana usage i.e. its connection to organized crime
- They both passed medical marijuana laws through a voter referendum in 1996 (albeit one that ended up being useless in AZ because of state legislator  
- Both had 2016 rec marijuana prop on ballot that were quite similar ie possession, sale, tax, regulation, and cultivation
- That said, they also have significant ideological differences. AZ is seen as one of the most conservative law and order states in the country. That said, AZ, is generally more conservative than CA. 

![Map of US States and Laws]({{ site.url }}/recreationalmarijuana/assets/images/marijuana_laws.0.png.jpeg)


## Corpus Collection

![A Complicated History]({{ site.url }}/recreationalmarijuana/assets/images/Screen Shot 2018-05-08 at 6.57.43 PM.png)

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
  
 
### Limits to Corpus
It is important to note that the Arizona corpus is significantly smaller than the California corpus, both in terms of the number of articles and the number of sources. Three sources is an especially low number and this lack of representativeness should be considered as an important disclaimer regarding the conclusions that can be drawn from the analysis carried out on this corpus.

## Tools Utilized

![A Complicated History]({{ site.url }}/recreationalmarijuana/assets/images/Digital Methods Presentation_2 Recreational Marijuana-2.pdf)

### Sentiment Analysis
As we sought to discover the underlying reasons that led to the proposition on the legalisation of recreational marijuana being rejected in Arizona, while being accepted in neighbouring California on the same date, our first analysis was a simple sentiment analysis on the articles collected. This sentiment analysis was carried out using the sentiment analysis script in Cortext and was done separately for California and Arizona, so as to allow an easy comparison of the results. This tool allows to rank every article from the corpus based on a sentiment and a polarity score. The sentiment score ranges from -10 to 10 and reflects whether the article uses more positive or more negative words. The polarity score ranges from 0 to 10 and reflects whether the article is written in an objective or subjective manner.

### Topic Modeling
Topic modeling allows to discover the thematic structure of a corpus of texts. It is comparable to a library where books do not have a title but one would still like to know what the book is about. This tool allows to discover the content of such books, as it identifies words and classifies them according to similar topics.

We used the topic modeling to get a sense of what topics were treated in newspaper articles, and therefore of what those newspapers were talking about. The idea is that newspapers, even though they employ a neutral language, can highlight different topics and as such influence voters.

We derived 10 different topics from our joint corpus of newspaper articles published in Arizona and California. They are further described in the result section.

The limits of topic modeling are twofold. First, topics are generated out of the frequency distribution of words in a text and their association one with another, thus checking for which words pop up together. When topics are presented however, words are without context and can thus lose its initial meaning. The interpretation of topics is thus a delicate task which can introduce a serious reader bias. Secondly, even though topics are correctly identify, one does not know how newspaper treat this topic. For example, Arizona might talk about the business aspect of marijuana legalisation, but we do not know whether this is in a positive or negative way, whether businesses accept or oppose the law, and so on.

### Contingency Matrix
A contingency matrix is a table which displays the frequency distribution of two different variables. We used such a matrix in order to display how our identified topics are distributed over different states. The red color shows a higher relative frequency of articles for the concerning state, whereas blue indicates a relative lower frequency. The size of the squares shows the frequency of articles attributed to the concerning category. Therefore, the wider in heigh, the more articles were attributed to a specific topic, the wider in with, the more articles were published in the according state.


