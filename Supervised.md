Supervised
regression -predict numeric value or quantity
classification - categorization

Training set - used to train model
validation set - tune model parameters and validate performance
Test set = Evaluate final model performance

Feature engg - using domain knowlge to select transform raw 
Helps enhance perf
extraction
selection
Transformation

Can be done on struc data, unstruct data

**unsupervised**
unlabelled data
Discover patterns, relation ships
Machine should create groups, but still label output
Clustering

Semi supervised - small amt of labelled and large amt of unlabelled to train

**Self supervised**

Generate psuedo label on own - Learn on its own
used in GPT

unlabelled data=>Pretext task=>labelled

**Reinforcement**

agent learns to make decisions
env
action choice made
reward - feedback
state - current situation
policy - strategy agent choses

Agent update policy based on reward
Goal - max reward
Optimized everytime

**Reinforcement with Human feedback**
Model response compared with Human response
Human assess quality of model

Used in Gen AI LLM
improves model perf

Data collection
Supervised fine tuning
Asks human which response they prefer, fine tune model
build separate reward model
optimize language model with reward based


Model fit bisas variance

FIT - Poor performance then need to look at FIT

Overfit- performs well on training data but not in evaluation
underfit - poor on training data

Bias - diff between prdicted and actual value
High bias - does not match training data, underfit
To fix - more number of features

Variance - How much perf changes if trained on diff data set which has similar distribu

High variance - model is sensitive to change in traing data, overfit
High bisas - Underfit
Balanced - lB LV
