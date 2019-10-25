1.1a log curve where the threshold is 0.5
1.1b yes, with iters=500 and lr=0.05
1.2a no, since the dataset is not linearly separable
1.2b AND: w1=1, w2=1, w0=-1.2; OR: w1=1, w2=1, w0=-0.5
1.2c w11=1, w12=-1, w10=0.5, w21=-1, w22=1, w20=-0.5
1.3b not necessarily, since 0.95 separator already seems to work well and one datapoint seems to be an outlier.
2.a #units of output layer: 1, actfunc of output layer: linear, lossfunc: quadratic
2.b #units of output layer: 1, actfunc of output layer: sigmoid, lossfunc: NLL
2.c #units of output layer: #email folders, actfunc of output layer: softmax, lossfunc:NLL
2.d #units of output layer: #topics, actfunc of output layer: sigmoid, lossfunc:NLL


