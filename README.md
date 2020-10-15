# Apache Spark optimization
Spark optimizations techniques
Apache spark is a powerful and effecient big data tool, it's ability to use in memory computing, it's flexibility and the large number of operators it offers to treat data makes it a natural choice for big companies to treat their huge amounts of data

Despite being very easy to learn and to use when we only have to filter, aggregate, join .. our dataframes or rdds, apache spark, suddenly, becomes complicated and hard to use when we need to explore the optimizations techniques it offers, playing with partitions, buckets and broadcasts isn't as fan as it seems the first time we take a look at those concepts, in this paper I will try to explain this part of apache spark so you can have enough knowledge to start optimizing and tuning your jobs efficiently

I - How apache spark works
