# Sentiment Analysis On Customer Support of Some of the Biggest Brands Using Twitter.

Sentiment Analysis On Customer Support of Some of the Biggest Brands Using Twitter.

Model used: Bert Base 

Customer Supports under observation : AppleSupport, AmazonHelp, Uber Support, Delta, SpotifyCares,
        Tesco, AmericanAir, comcastcares, TMobileHelp, British Airways,
        SouthwestAir, Ask Spectrum, hulu support, ChipotleTweets, sprintcare,
        VirginTrains, AskPlayStation, XboxSupport, UPSHelp, sainsburys
        
Customer Support Dataset: https://www.kaggle.com/datasets/thoughtvector/customer-support-on-twitter/code

Dataset used to fine-tune the model: Stanford Sentiment TreeBank with 5 labels (SST-5)

The pre-trained Bert model is used to perform sentiment analysis on a dataset consisting of over 3 million customer support related tweets from some of the biggest brands. 
The model does in general show a lower accuracy of around 50% when trained on the SST-5 Dataset which is due to the increased complexity of the fine-grained sentiment classification task. Also, subtle differences in sentiment make it harder for models to achieve high accuracy on SST-5. 
However, the lower accuracy is still on par with the state-of-the-art accuracy which indicate that even with sophisticated models, the accuracy plateaus around 50 %.










Inference derived from the graphs:
Graph 1: Sentiment Analysis of Initial Customer Tweets 


![image](https://github.com/user-attachments/assets/10339200-826b-4a6d-a073-8a0548d39d8a)


SouthwestAir shows a more balanced distribution with a higher percentage of positive and very positive tweets compared to many other brands. This suggests a generally favorable customer experience with SouthwestAir 's support.

Delta and AmericanAir have an exceptionally high percentage of negative and very negative tweets in both graphs. This is attributed to poor customer service.

Spotify shows a relatively balanced sentiment distribution, with a noticeable portion of positive tweets. This indicates better customer satisfaction and engagement. 


Graph 2: Sentiment Analysis of Customer Responses to Brand Tweets 

![image](https://github.com/user-attachments/assets/4886e713-4b2d-4ddb-afc5-d46fe6bceb0d)



Delta, hulu support, Ask Spectrum and AmericanAir does still show notable negative responses, indicating ongoing dissatisfaction despite customer support interactions.

SpotifyCares also shows a higher percentage of positive responses in the second graph, indicating successful customer engagement and issue resolution.

Brands like AppleSupport and AmazonHelp show high neutral sentiment in responses, suggesting that their customer support teams are effective in resolving issues without further aggravating the customer, leading to a more neutral response.

