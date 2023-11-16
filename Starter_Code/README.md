deep-learning-challenge

After trying and changing bin sizes, dropped columns, as well as activation of the seperate layers and the amount of layers themselves, the highest accuracy rating I could get my model to was .728 or 73% accuracy. This is off of the original target of 75%, and most of the changes I made kept the model accuracy the same, or decreased its accuracy, so I am pretty much at a loss for how to increase it to 75%. 

https://medium.com/@italojs/saving-your-weights-for-each-epoch-keras-callbacks-b494d9648202

As far as refrences go I used this to callback my model for when it had the highest accuracy rating during its testing, so I could see accuracy scores while I was actually training the model throughout each of the epochs, not wasting time if it ended up decreasing over time.


https://pandas.pydata.org/docs/reference/api/pandas.get_dummies.html

I also had to use the pandas documentation for pd.get_dummies since I had forgotten what that did.