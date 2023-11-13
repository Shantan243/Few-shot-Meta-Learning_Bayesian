# Few-shot-Meta-Learning_Bayesian
This is extension to oneshot_learning by siamese. Please go through readme of oneshot for dataset link
To classify the images using Few shot Meta-learning with Bayesian &amp; Deep Kernel transfer
The dataset used here are 1. Casted iron from Kaggle has 2 labels (Defect/No Defect), 2. Automobilt tool parts (Private dataset) and 3. GC-10DET (steel defect dataset available on Kaggle)
Meta-learning or as often referred to learning to learn is achieved by abstracting learning into two or more levels. The inner-most levels acquire task-specific knowledge (e.g. fine-tuning a model on a new dataset) , whereas the outer-most level acquires across-task knowledge (e.g. learning to transfer between tasks more efficiently).
Few-shot learning is the problem of making predictions of unknown classes based on a limited number of samples. 
Bayes Thearom: The probability of an event occurrence, based on prior knowledge of conditions that might be related to the event.
DKT: Deep kernel is a prior which enumerates during the process of training of Outer loop of the network which has a knowledge of the input and output distribution.
This prior with parameters shared across tasks, so that given a new unseen task it is possible to effectively estimate the posterior distribution over a query set conditioned on a small support set.
As this prior transfer the knowledge from Outer loop to inner loop, this is called as DKT.
Architecture and other details can be found in ppt.
We have acheived 83% on steel surface dataset while usual supervised DNN acheived only 55%. There are other results as well. Kindly go through ppt.
