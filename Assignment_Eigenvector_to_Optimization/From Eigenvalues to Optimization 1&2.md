
# Assignment 1 : From Eigenvalues to Optimization 

**Task 1.** Read Good Optimization introduction for ML and this discussion and outline: 
What are the basic elements of optimization? Give some examples. 
Why is optimization important in machine learning? Give some examples. 

### What are the basic elements of optimization? Give some examples.

Basic elements of optimization:
1. Variables: Parameters which will be passed to optimization algorithm.
2. Constraints: These are the boundaries within which the parameters (or some combination thereof) must fall
3. Objective Function: This is the set of goal towards which the algorithm drives the solution. For machine learning, often this amount to minimizing some error measure or maximizing some utility function.

#### For example:

Example question : The regular air fare between Boston and San Francisco is 500 dolars . An airline using
planes with a capacity of 300 passengers on this route observes that they fly with an average of
180 passengers. Market research tells the airlines’ managers that each $ 5 fare reduction would
attract, on average, 3 more passengers for each flight. How should they set the fare to maximize
their revenue? Explain your reasoning to receive credit.

1. Variables : 1- Air fare which will be regulated 2- Quantity of passengers
2. Constraints : Air fare should be regulated by preserving from making loss.
3. Objective Function : Making the most profit arranging with number of quantity of passengers and air fare

### Why is optimization important in machine learning? Give some examples. 

Optimization is used to find more accurate results by using loss function. And in machine learning, Predicted values are deduced from some finite data. That's why optimization is very important for machine learning algorithms. **For example** while working on neural networks, arranging weight and type of nodes is done by result of optimization of loss function between predicted values and actual values.


**Task 2.** Recollect : What is a loss function /cost function? Give examples 

**Loss function or cost function** is a function that maps an event or values of one or more variables onto a real number intuitively representing some "cost" associated with the event.Basically If predictions deviates too much from actual results, loss function would cough up a very large number. Gradually, with the help of some optimization function, loss function learns to reduce the error in prediction.
**For example:** You have neural network which takes some data related to some house and predicts its price. Loss function is how predicted values deviates from the actual prices.


```python

```
