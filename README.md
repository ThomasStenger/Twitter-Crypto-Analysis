# Twitter-Crypto-Analysis

This is a project I worked on during my studies. It covers the following phases of the big data value chain: 
1) Sources - Twitter Data in JSON-Format; 
2) Ingestion - Apache NiFi; 
3) Storage - Hadoop HDFS; 
4) Processing - Apache Spark (APIs: Pyspark, Spark SQL). 



My group and I wanted to better understand the fast-moving world of cryptocurrencies. One of the problems in the crypto world is its fast-changing nature with one trend quickly being surpassed by the next one. This becomes evident to anyone who is observing this space, even if they just started this year – we’ve had to learn new abbreviations and concepts on a regular basis from Blockchain, Smart-Contracts, POW, POS, POA, DeFi, NFTs, Metaverse and the list goes on and on. This raises an important question – how can investors be ahead of the curve and spot the next trend early on? Being able to do so could translate into better investment decisions and boost profitability. 

This question defines our main problem to tackle throughout this project. But in what concrete context can we try to approach this issue? In the crypto space, one of the main mediums of communication and to exchange investment ideas is the social media platform Twitter. Twitter is a central point for crypto-influencers, projects, media outlets, companies and retail investors to discuss anything crypto-related. Events such as Elon Musk sending DogeCoin’s course on a strong upward trajectory just by tweeting about it (or vice-versa tanking Bitcoin’s course by tweeting about its environmental impact) or Michael Saylor, CEO of BI company MicroStrategy, announcing the latest purchase of bitcoins for his company’s treasury are just some of the examples of crypto-related tweets with a real impact on markets. 

Therefore, we thought it’s a good idea to be able to analyze large amounts of tweets coming from Twitter and perform data analysis on them to be able to get insights from this continuous crypto conversation on the platform. This could help us in spotting new trends early on by analyzing and identifying relevant twitter accounts that generate a lot of engagement, understand what crypto projects are most talked about, to see in which geographies users are into crypto, and so on. Also, with the foundations laid in the ingestion-, storage-, and processing phase in this project, we can easily implement new analysis methodologies in the future.
