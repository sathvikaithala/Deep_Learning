# Deep Learning and Neural Networks
UC Berkeley Extension Data Analytics Boot Camp Module 19

---

## Objectives:

- Import, analyze, clean, and preprocess a “real-world” classification dataset
- Select, design, and train a binary classification model
- Optimize model training and input data to achieve desired model performance

## Analysis & Discussion:

#### Notes on combinations tried:
    
Trial 1: 1 layer, 25 nodes, Relu, 100 epochs -- ACCURACY SCORE: 74.5% - Very close to our goal of 75%.

- Our initial model performed very close to our target accuracy of 75%

Trial 2: 2 layer, 25/10 nodes, Relu, 100 epochs -- ACCURACY SCORE: 74.9% - Even closer to 75%!

- Adding a second layer to our model slightly increased our accuracy.

Trial 3: 1 layer, 35/10 nodes, Relu, 75 epochs -- ACCURACY SCORE: 74.8 % - Slight degradation over Trial 2.

- We reduced the number of epochs since there was not much of an improvement in loss or accuracy beyond 60-75 epochs. We found that increasing the number of nodes in layer 1 did not improve our accuracy.

Trial 4: 1 layer, 25/15 nodes, Relu, 75 epochs -- ACCURACY SCORE: 74.7% - Slight degradation over Trial 3.

- In this trial, we reduced the number of layer 1 nodes back to 25, and increased the number of layer 2 nodes to 15. We found that this model performed worse than our second attempt. However, all four attempts were within 1 percentage point of our target accuracy of 75%.


#### Were you able to achieve target model performance?

Our goal for this project was to achieve an accuracy of 75%. Through four trials, I was able to achieve an accuracy of 74.9%. While it is slightly short of our goal, it is very close.


#### If you were to implement a different model to solve this classification problem, which would you choose and why?

In the case of this specific project, I believe an accuracy of 75% can be achieved with the models used, but with more trial and error. While other methods might also work, I would argue that the model we used here achieves our goal just as well.
