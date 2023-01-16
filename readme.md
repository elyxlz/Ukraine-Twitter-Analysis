# DATA VISUALISATION, ANALYSIS AND INTERPRETATION OF RESULTS

In this section, we will integrate the data visualisation, data analysis and interpretation. In the data analysis we will describe the trends seen in the data visualisation, pointing out key features and describing the nature of the type of data visualisation. In the interpretation we will interpret the reasons why the trends may have occurred and justifying these assertions using our knowledge of the datasets, information in the background section and taking into account broader socio-economic and demographic conditions.

**LANGUAGE DISTRIBUTION PLOT**

[https://elyxlz.github.io/Ukraine-Twitter-Analysis/Plots/language_count.html](https://elyxlz.github.io/Ukraine-Twitter-Analysis/Plots/language_count.html)

Analysis: As we can see from the graph in logarithmic scale, most of the tweets in our data are written in German (de), Italian (it), French (fr), and Spanish (es), which accounts for 89.09% of the total dataset. Within the dataset of 3.7 million tweets, German contributed 1.1 million tweets, which is ~30% of the data.  While the least language in our research is Slovenian (sl), which is about 2,450 (0.07%). As seen by the y-axis log scale in both the total and mean versions of the interactive graph, the distribution between the tweets by country is massively unevenly distributed. 

Interpretation: In our analysis, we assign each country with its national language, so that we can further investigate in the topic modelling and sentiments and see how the discussion of certain topics relating to the war alters over time by countries. Therefore, in this graph, we assume that most of the tweets are written in German (both in Germany and Austria), Italian, French, and Spanish, while the least are written in Slovenian. The uneven distributions is mainly  explained by the differences in national population size between the countries since this countries are some of the most populated in Europe. Furthermore, the German language will include tweets from Austria as well as Germany contributing to the tweet count. Additionally, the uneven distribution may also be due to differences in the amount of users in Twitter in each every country. 

**DAILY TWEET COUNT PLOT BY LANGUAGE OVER TIME**

[https://elyxlz.github.io/Ukraine-Twitter-Analysis/Plots/daily_tweets_per_language.html](https://elyxlz.github.io/Ukraine-Twitter-Analysis/Plots/daily_tweets_per_language.html)

Analysis: According to the graph, daily tweet count can be split into two broad categories, with Europe’s largest nations having a considerably higher output than other languages. Namely, France, Germany and Spain. Despite this, all countries appear to follow similar trends, except for Romania and Czechia, which have a stable tweet output with no apparent peaks. There are four main peaks in the graph; in May, where Spain produced the highest tweet count of all with 10,870, June, where Germany exhibited an acute peak, September/October, which was mostly Germany, and December, where several countries showed a minor increase in tweet count. The overall tweet count appears to generally reduce over time, excluding peaks. This will be explored further in following sections. 

Interpretation: The two broad categories are likely resultant of the population of the countries, with Europe’s largest nations having a major tweet output and the smaller ones having less. The peaks can be explained by various events in European countries. The first peak might be explained by Madrid explosion on May 6th. The peak in September is likely due to German inflation hitting a record high and energy prices increasing. 

**DAILY TWEET COUNT OVER TIME COMPARED TO NORD STREAM GAS FLOWS** 

**TAG Word CLOUD GRAPHICAL REPRESENTATION**

Analysis: Several themes pertaining to the Ukraine War were prevalent in the tag cloud, with “Ukraine” being the most prominent tag. Other similar tags which were also heavily prominent include “war”, “mobilization” and “governments”. Football also proved to be a common theme, with tags “WOLLEE”, “LeedsUnited”, and “lufc” being significant. Other themes were market related tags such as “market”, “DAX”, and “volatile”. Tags in foreign languages were popular to a lesser extent, such as “Guerr” and “GuerraUcraniaARV” but were largely concerning the Ukrainian war. 

Interpretation: Ukraine likely featured as the top tag as the war affected a multitude of countries in many ways so there was a high volume of tweets regarding it. Football and stock trading are common interests shared by many, which might explain their prevalence. 

**TOPIC MAP 2D & INTERACTIVE TOPIC MAP 3D**

[https://elyxlz.github.io/Ukraine-Twitter-Analysis/Plots/tweet_by_topic_map.html](https://elyxlz.github.io/Ukraine-Twitter-Analysis/Plots/tweet_by_topic_map.html)

3D version [here.](https://elyxlz.github.io/Ukraine-Twitter-Analysis/Plots/tweet_by_topic_map_3d.html)

Analysis: The density-based spatial clustering algorithm Hierarchical Density-Based Spatial Clustering of Applications with Noise (HDBSCAN) processed the ~3.7 million tweets in our data frame to produce 112 topics which are displayed above both in two and three dimensional interactive maps. Whilst there are some spherical-shaped clusters, the majority of topics identified by the algorithm are arbitrary-shaped clusters. Clusters that shared similar semantic features are closer together on the map and in some instances, spatially overlap each other. For example, topic 21 ‘fifaworldcup_qatar22[…]’ (orange) and topic 9 ‘eurovision_ukraine[…]’ (light are seen clustered close together around the 30-40 mark on y-axis of the maps. As seen on the 2D map, these 2 topics are much higher on the y-axis than the other clusters which might be because they have less semantic features linked to the war and are clustered close since the tweets discuss the respective entertainment events. Another example, cluster 73 and 76 which both discuss nuclear weaponry and nuclear plants, are clustered closely around the (-2, -15) coordinate on the map seen in pink and red which can be due to their overlapping semantic features. Of the 112 clusters, we discarded 78 clusters due a very low tweet density or seemingly irrelevant topic detected by the AI. The remaining 34 clusters further investigated in our analysis were recognised as having a reliable tweet density as well as having a reasonable topic recognised between the individual tweets. This was achieved using our own judgement using the interactive 3D map and evaluating the tweets in each cluster, considering the unique words per cluster and its proximity to other clusters sharing similar semantic features.

Interpretation: Of the 34 clusters identified as semantically and statistically valuable (check Appendix A for justification), it is evident that the algorithm managed to cluster tweets together with a shared topic discussed that was reasonably associated with most tweets within that specific cluster. The hierarchical nature of the clustering method means that the most semantically relevant topics with higher tweet counts spatially congregate around the centre of the map whilst less relevant topics cab be seen scattered around the peripheries of the map, most of which were discarded in the valuable topic selection process doe to lack of relevance and abnormally low tweet counts. 

**LOG SCALE TWEET COUNT BY THE 34 TOPICS RECOGNISED AS SEMANTICALLY VALUABLE**

[https://elyxlz.github.io/Ukraine-Twitter-Analysis/Plots/topic_counts.html](https://elyxlz.github.io/Ukraine-Twitter-Analysis/Plots/topic_counts.html)

Analysis: By listing the topics by tweet count we were able to identify the topic with the highest number of tweets. The cluster with the highest tweet count is topic 33 ‘gas_russia_ukraine_putin_sanctions’ which had 234,437 tweets, almost 1/4th of a million. This topic included discussions of bans on Russian gas imports, government statements of economic plans in EU due to dependency on Russian gas and criticisms of financial transactions between EU countries and Russia. From our judgment it included both sentiment towards supporting Ukraine as well as discussion on the negative implications of supporting Ukraine in the war due to reasons mentioned in the literature review. One tweet claimed that climate change activists would slowly start supporting the Russian government due to the climate impact of the energy crisis in Europe. Discussions on whether the sanctions are even helping, “are we harming ourselves more.”

Interpretations 

**R^2 GRID PLOT WITH NORD STREAM PIPELINE FLOWS BY THE PROPORTION OF TWEETS BY TOPIC** 

[https://elyxlz.github.io/Ukraine-Twitter-Analysis/Plots/r_squared_heatmap.html](https://elyxlz.github.io/Ukraine-Twitter-Analysis/Plots/r_squared_heatmap.html)

Analysis:

Interpretation:

**TOPIC 86(”Stand_with_Ukraine”) OVER TIME BY LANGUAGE**

[Topics over time by language](DATA%20VISUALISATION,%20ANALYSIS%20AND%20INTERPRETATION%20OF%200939f82b75ef44dca6545b2549ead77c/Untitled.html)

Analysis: The graph depicts the proportion of tweets that talks about the topic “stand with Ukraine” in each language. In the graph, x is the date, and y is the proportion of tweets compared to all tweets in the specific languages. The reasons for taking the proportion instead of the amount are (1) to normalise the number by total tweets so that the effect of varied user bases in each country could be excluded, and (2) to eliminate the effect of the trend of decreasing topic discussion over time, since people has gradually paid less attention to the development of war over time and thus there are less and less tweets mentioning “stand with Ukraine” as well.

As we can see on the 24th of August, several languages reach their peak on that date. For instance, about 39.13% of the tweets in Finnish includes the hashtag in support of Ukraine, while 25.56% of the tweets in Czech, and 24.81% in Polish. And on the 12th of March, about 16% of the tweets in Romanian also expresses their pro attitude toward Ukraine on that date.

Interpretation: To investigate in the reason of the trajectory of the topic discussion in each language/country, we find some articles that keeps track of the development of war and the major actions of the involved governments have made. For the progress of the war, Russian forces faced challenges in keeping the front line in Denmark, and Russian government also struggled with the partisan and internal challenges during the time. 

- Russian forces have lost an area larger than Denmark since the high-water mark of their invasion of Ukraine in mid-March and gained an area the size of Andorra (one percent of what they have lost) in the last 39 days.
- Russian Defense Minister Sergey Shoigu reaffirmed that Russia has not changed its maximalist strategic war aims.
- Russian forces conducted limited ground attacks southwest and southeast of Izyum, northeast, and south of Bakhmut, and west and southwest of Donetsk City.
- Russian forces conducted a limited ground attack in northwestern Kherson Oblast.
- Ukrainian forces continued to target Russian military assets and ground lines of communication (GLOCs) in Kherson and Zaporizhia Oblasts.
- Russian occupation authorities continue to face partisan and internal challenges to the administration of occupation agendas.
- Russian proxy leadership is continuing efforts to oversee the legislative and administrative integration of occupied territories into Russian systems.
