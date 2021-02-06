# COAR_Fall2020

In Fall 2020, I conducted research on different algorithims aimed at improving the efficiency of the regular Q-Learning algorithim. I covered the Double Q- Learning algorithm, and the Fitted Q- Learning algorithm. 

## Double Q Learning

The paper for the Double Q-Learning algorithm can be found [link](https://papers.nips.cc/paper/2010/file/091d584fced301b442654dd8c23b3fc9-Paper.pdf "here"). 

My code is all in one file (DoubleQ_MPD.ipynb) and covers the code using a Uniform, Epsilon Greedy, and Boltzmann behavior policies (generally with constant step size = 0.1). I analyzed the difference in convergence rates against regular Q-Learning using number of iterations as well as runtime. Using both analyzes I found that the results were inconclusive. 

## Fitted Q Learning
The paper for the Fitted Q-Learning algorithm can be found [link](https://www.jmlr.org/papers/volume6/ernst05a/ernst05a.pdf "here").

My code is all on one file (FQLearning.ipynb). The sample batches are collected using a uniform policy with my batch size being 20000 for both versions of the code. The first code is regular Fitted Q-Learing as it plots the difference between the updating Q-Function and the optimal Q-Function found through value iteration. As the first code shows rge Q-Function convergeing but not to the optimal Q-Function, we attempted to see if it would converge to a projection. In the second code I solve the Markov Stationary Matrix and find the projection to plot that difference. HOwever, this did not yield better results. Therefore, the findings are inconslusive. 

