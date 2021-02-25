# Got in the top 2% of all global participants of the kaggle mnist dataset challenge

## I used 25 ensembled CNNs with the usual Conv & MaxPool layers along with some dropout and batch normalization to spice it up a bit and get my model more accurate. I was able to get a validation accuracy anywhere between .994 - .999 which made me pretty happy.
## The biggest problem's I faced were figuring out how to get my ensemble to work correctly and in tandem which after some relentless googling I was able to do it. The next one took me a couple tries to get right but it was a very small fix. When I was splitting my training data into train and validation, I did not set my random state and spent far longer than I'd like on such a simple issue. Live and learn.
