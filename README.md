

# 1. Finance using Reinforcement Learning
Stock Prediction by Reinforcement Learning.

It's implementation of Q-learning applied to (short-term) stock trading. 
The model uses n-day windows of closing prices to determine if the best action to take at a given time is to buy, sell or sit.

As a result of the short-term state representation, the model is not very good at making decisions over long-term trends, but is quite good at predicting peaks and troughs
## Usage

- To train the model :   
```
cd ReinforcementLearning-Finance
mkdir models
python train.py ^GSPC 10 1000`
```
- Then after training finishes : 
```
python evaluate.py ^GSPC_2011 model_ep1000
```
## Tutorial 
Jupyter Notebook for stock prediction.

## References 
[Deep Q-Learning with Keras and Gym](https://keon.io/deep-q-learning/) - Q-learning overview and Agent skeleton code

[Siraj Raval-School of AI](https://www.theschool.ai/courses/move-37-course/)

 https://medium.com/ai%C2%B3-theory-practice-business/reinforcement-learning-part-1-a-brief-introduction-a53a849771cf
https://blog.floydhub.com/an-introduction-to-q-learning-reinforcement-learning/ https://deepsense.ai/what-is-reinforcement-learning-the-complete-guide/ https://analyticsindiamag.com/reinforcement-learning-in-finance-a-newbie-in-portfolio-selection-and-allocation/



