## Amazon Personalize expands the number of events considered by filters to make recommendations even more relevant

[Amazon Personalize](https://aws.amazon.com/personalize/) has extended the capabilities of its filters, increasing limits and providing control over the number of interactions considered by each filter. Amazon Personalize filters improve the relevance of recommendations by removing products that users have already purchased, videos they have already watched, or other digital content they have already consumed in their recent interactions. Receiving repeated recommendations may be frustrating for users, which could lead to lower user engagement and lost revenue opportunities. Amazon Personalize now offers the option to extend the number of interactions considered by the filters to better capture users’ historical activity, particularly for use-cases where customers have a high volume of interactions. Filters now consider up to 100 interactions per user per event type.

Setting up and using Recommendation Filters is simple. First, you use the Amazon Personalize console or API to create a filter using an Amazon Personalize-specific DSL (Domain Specific Language). Next, you apply this filter while querying for real time recommendations using the [GetRecommendations](https://docs.aws.amazon.com/personalize/latest/dg/API_RS_GetRecommendations.html) or [GetPersonalizedRanking](https://docs.aws.amazon.com/personalize/latest/dg/API_RS_GetPersonalizedRanking.html) API; or while generating recommendations in batch mode through a [batch inference job](https://docs.aws.amazon.com/personalize/latest/dg/API_CreateBatchInferenceJob.html). To increase the number of interactions considered by your filters, simply request a service quota increase via the Service Quota console.

> Source: https://aws.amazon.com/about-aws/whats-new/2022/08/amazon-personalize-expands-number-events-filters-recommendations-relevant/