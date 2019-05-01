# Neural-Network-Test-with-Tensorflow-in-2x2-Factorial-Design
This study utilized the MNIST dataset from tensorflow.keras.datasets to explore neural network structures within a benchmark experiment of a 2x2 factorial design. Due to the time required to fit each neural network, we observe only one trial for each cell in the design. The two factors selected for this study are: nodes-per-layer (128, 10) and optimizer (adam optimizer and RMSProp Optimizer). For each combination, we build a neural network with tensorflow.keras on the training set come with MNIST and evaluate the its performance by caculating accuracy rate on both training and test set. We also record the time spent on building and evaluating each model. The results from each combination are then compared for analysis.**
<br>

The result shows that as the number of nodes-per-layer increases, so dose the predictive performance of the neural network model. RMSProp optimizer outperformed Adam optimizer in both scenariors (nodes-per-layer = 128 and nodes-per-layer = 10). This may be because the approach taken by RMSProp optimizer which impedes our search in direction of oscillations better avoided overshooting in this data set.**
<br>

It is also important to point out that the result of this study will generalize poorly. During the experiment, highly fluctuated accuracy values were witnessed on both training and testing set for all four (4) combinations, without tuning other paramters but simplying runing the test various times.** 
