Hello. I'd like to share my take on the kaggle Quora competition(2018-2019).
This approach scored 0.69645 on public and 0.70338 on private, placing 134th.
Main architecture ideas are the use of a model with capsules, attention and Cyclic learning rate and K-fold.
Some code and ideas are taken from other kaggler's post, so I encourage you check them out. 

* https://www.kaggle.com/gmhost/gru-capsule
* https://www.kaggle.com/christofhenkel/how-to-preprocessing-when-using-embeddings
* https://www.kaggle.com/theoviel/improve-your-score-with-some-text-preprocessing
* https://github.com/mttk/rnn-classifier/blob/master/model.py
* https://www.kaggle.com/ziliwang/baseline-pytorch-bilstm
* https://www.kaggle.com/hengzheng/pytorch-starter