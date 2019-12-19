1a. Since we are standardizing, everything below the average would be below 0 after standardized
1b. gal milage threshold 23
1c.
i. averaged perceptron: acc 0.9005128205128207; trees: acc 0.9080769230769231 slightly better for tree
ii. feat 1, 5, 7; cylinders4.0, displacement, weight
iii. 1=good, 0=bad 
1d. feat0 = weight is more important
1e. The accuracy is almost the same (slightly better for standardized), and trees have almost the same structure
standardizing is just scaling --> same for weights
origin --> different because there are three one-hot
1f. linear classifier: if we wanna classify into more than two categories; neural net: when we wanna know the relationships between variables and output; much easier to train; less data to train

2a. if we set `N_THRESHOLD = 1` then the minimum training error would be 0. It's overfitting.
2b. when we would stop splitting the tree: determine generalization and overfitting
2c. `N_THRESHOLD = size_of_dataset`

3a. 0.8876923076923078
3b. slightly better if standardized; change the distance
3c. weight distance based on different features; do transformation when metric
3d. k=4 is best, 0.898076923076923

4a. mountains or trees
4b. it is affected by what a lot of people like, which could be insidious when people gets to see something more contents similar to that would be recommended and watched.
4c. it would not be recommended since people have not watched it
