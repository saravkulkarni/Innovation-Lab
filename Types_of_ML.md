Types of Machine Learning

There are three main types of machine learning. Each type has different requirements for the data it learns from and each has a different usecase.

These are supervised, unsupervised, and reinforcement learning. This guidebook will primarily focus on supervised learning, as it is the simplest and the most ubiquitous. 

:::{card}
:header: Supervised Learning
For supervised learning, the training data must be labelled. That is to say, that each input (feature) has a correct output (label) associated with it. The algorithm then analyses this data in order to then be able to make predictions about unknown data. For example, you could have cell data where each is classified as either a benign or malignant tumour. You could then ask it to predict based on patterns it has recognised, whether a particular tumour is benign or malignant. 

Supervised learning divides into two further types, both of which will be discussed in more detail later. 

Classification is used when the outputs are categorical; they are in two or more classes. Classification algorithms would be used on the example above, as the tumours are labelled as either benign or malignant; there are no other other options. 

Regression is used to predict real or continuous values. In this cases, the regression algorithms analyse the relationships between two or more variables. An example of this might be predicting the reaction rate based on a set of input reaction conditions.

While supervised learning is highly useful in a wide variety of contexts, the data it is trained on has to be labelled. Data annotation jobs exist precisely because companies, particularly those with an investment in AI, need lots of labelled data.

However, the quality of the predictions can only ever be as good as the quality of the labelling in the training data. Poorly labelled data can lead to incorrect and potentially dangerous predictions. 
Furthermore, a model that is very accurate with the data it was trained on may prove to be useless with faced with an external dataset where there are other trends and factors in play. 
:::

:::{card}
:header: Unsupervised Learning
For unsupervised learning, the data does not need to be labelled. There are no defined goals and the algorithms work to learn patterns from the data it is given. It can help when faced with large and complex datasets, as it can potentially highlight connections and features to then look more deeply at. 

Unsupervised learning divides into three further types. 

Clustering breaks the data down into clusters (groups) based on the similarities within. 

Association rule mining is when the algorithms are tasked with finding relationships and correlations between the data points. 

Dimensionality reduction is when the number of features (dimensions) is reduced. It removes the irrelevant and random parts of the data. 
:::

:::{card}
:header: Reinforcement Learning
Reinforcement learning is when an 'agent' learns through trial and error, receiving feedback in the form of rewards and penalties for its decisions. After making an action, the feedback the agent receives, informs the action it will next take. Over time, the agent learns what actions are likely to earn it the most rewards.

While reinforcement learning can solve problems effectively, it needs a lot of data to interact with, which can be draining. In certain cases, there are safety risks, as it may take an action that could damage something or someone. 

:::
