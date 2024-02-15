# Corrective or Backfire: Characterizing and Predicting User Response to Social Correction
This repository contains data and code for our ACM Web Science 2024 publication regarding response to social correction on Twitter. 

The PDF can be accessed here: [PDF](https://faculty.cc.gatech.edu/~srijan/pubs/ma-websci23-social-correction.pdf)

## Introduction

Online misinformation poses a global risk with harmful implica- tions for society. Ordinary social media users are known to actively reply to misinformation posts with counter-misinformation mes- sages, which is shown to be effective in containing the spread of misinformation. Such a practice is defined as “social correction”. Nevertheless, it remains unknown how users respond to social cor- rection in real-world scenarios, especially, will it have a corrective or backfire effect on users. Investigating this research question is pivotal for developing and refining strategies that maximize the efficacy of social correction initiatives. 

To fill this gap, we conduct an in-depth study to characterize and predict the user response to social correction in a data-driven man- ner through the lens of Twitter, where the user response is instan- tiated as the reply that is written toward a counter-misinformation message. Particularly, we first create a novel dataset with 55, 549 triples of misinformation tweets, counter-misinformation replies, and responses to counter-misinformation replies, and then curate a taxonomy to illustrate different kinds of user responses. Next, fine-grained statistical analysis of reply linguistic and engagement features as well as repliers’ user attributes is conducted to illustrate the characteristics that are significant in determining whether a reply will have a corrective or backfire effect. Finally, we build a user response prediction model to identify whether a social cor- rection will be corrective, neutral, or have a backfire effect, which achieves a promising F1 score of 0.816. Our work enables stakehold- ers to monitor and predict user responses effectively, thus guiding the use of social correction to maximize their corrective impact and minimize backfire effects. 

## Data

1. `tweet_reply_response_id.csv`: contains (misinformation tweet ID, counter-misinformation reply ID, response ID to couter-misinformation reply).
2. for a tweet/reply/response, per Twitter's rule, we provide the ID information used for retrieval. 


We notice the change of Twitter API. If you have problems accessing to the whole dataset or the code, please contact Bing He (bhe46@gatech.edu).
