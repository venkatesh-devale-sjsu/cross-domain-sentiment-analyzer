# cross-domain-sentiment-analyzer
We found many sentiment analysis models which analyzed the sentiments of any review attached to a specific domain.
We wanted to study if using multiple domain datasets can we build a generic machine learning model so that it can predict the sentiments for any type of review.

We implemented this model using CNN, Python, Flask:
We first generate the word embeddings for the words in the reviews available in the entire dataset.
Based on this probability we do word tagging to make text buckets for similar probabilities and pass on this to CNN model which gives us a output of the text sentiment.

We have not implemented the bigram but we have used Google playstore reviews dataset, amazon food reviews and a restuarant review which were pretty diverse to achieve the study.
