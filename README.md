# UDLND---Project-4---Generate-TV-Scripts

This project required using RNNs to generate TV show scripts.  It was a learning experience, with the most interesting aspect of it being that for an RNN, you have to turn on Retain_Graph for the backpropagation or else you end up with an ever-growing training time as the model tries to adjust weights all the way back over every iteration.  This also requires converting the weights to a tuple. 

![Retained graph](https://github.com/D-Nations/UDLND---Project-4---Generate-TV-Scripts/blob/master/RNN%20backprop.PNG)

## What I Learned

Once again, I learned that you can waste a lot of time on training if the code is wrong.  It took me a long time to figure out why I couldn't implement the tuple on the weights (I forgot the square brackets).  RNNs are great but after finishing this project I didn't think they were the best way to approach this particular problem.
