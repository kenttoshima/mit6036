# Lab 7
1.A
i. sigmoid for each unit, NLL
ii. linear , squared loss

1.B No

1.C  Identity matrix; yes, it would work for unknown input and it would not be a compression

1.D
i. the bigger the size is, the better (clearer) the reconstructio is
2048 is worse than 256 since it is overfitting; learn the noise
ii. It does

1e clusetering

2.A $\sigma(z)(1-\sigma(z))\cdot x$

2.B $\sigma(z)(1-\sigma(x)\cdot\theta$

2.C if we set target_class to some number, the probability of predicting the class of that number would be higher. 1st and 3rd elements of input will be smaller than 2nd and 4th elements if we set input=0 and target=1. Vice versa.
--> With enough number of iteration, the output would be biased for the target class no matter what the input class is

2.D
i. classifier output looks more like the input class
ii. not at all, since as long as we set the target class to certain class, then the classifier will learn to classify images to be that target class

2.E Yes, if putting stickers on stop sign could mess up auto-driving, that would be really scary.
