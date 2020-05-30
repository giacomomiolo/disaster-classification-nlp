# NLP - Disaster Classification Task

In our project we leverage the highly unorganized massive source of information that Twitter provides in order to identify user generated content that might be useful for disaster management.
We focus on improving the built-in Twitter search function by proposing a model that filters out noisy information that is not of interest to people involved in disaster management.
Our approach leverages transfer learning and supervised learning in order to better classify tweets related to disasters and tweets that might contain keywords related to disasters but are referring to a different context.
In particular, we use DistilBERT for transfer learning and stacking to ensemble multiple classification machine learning algorithms.
The results obtained were compared with a small manually labelled set of tweets scraped using the Twitter search function.
