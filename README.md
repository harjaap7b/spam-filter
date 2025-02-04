# spam-filter
## Creating a spam filter with the Naive Bayes algorithim

In this project I aim to create a spam filter that filters out spam SMS messages with help of the Naive Bayes algorithim. I will be using a dataset form the UC Irvine machine learning respository named SMS Spam Collection. I will be looking for specific markers on dataset of 5572 SMS messages already classified by humans to teach the computer to mark messages as 'spam' or 'non-spam'. To achieve this will be using the multinomial Naive Bayes Algorithim. The multinomial Niave Bayes formula is as follows:

p(S|wn)∝p(S)⋅∏ni=1p(wi|S) (1.0) 

and for non-spam messages it will just be the complement of the spam messages, donated as 'C':

p(SC|wn)∝p(SC)⋅∏ni=1p(wi|SC) (1.1) 
p(S|wn)=the probability the message is spam with words w_n in it 
p(SC|wn)=the probability the message is non-spam with words w_n in it
