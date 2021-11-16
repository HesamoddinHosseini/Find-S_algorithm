# Find-S_algorithm

Introduction : 
The find-S algorithm is a basic concept learning algorithm in machine learning. The find-S algorithm finds the most specific hypothesis that fits all the positive examples. We have to note here that the algorithm considers only those positive training example. The find-S algorithm starts with the most specific hypothesis and generalizes this hypothesis each time it fails to classify an observed positive training data. Hence, the Find-S algorithm moves from the most specific hypothesis to the most general hypothesis. 





 Steps Involved In Find-S : 

Start with the most specific hypothesis. 
h = {ϕ, ϕ, ϕ, ϕ, ϕ, ϕ}
Take the next example and if it is negative, then no changes occur to the hypothesis.
If the example is positive and we find that our initial hypothesis is too specific then we update our current hypothesis to a general condition.
Keep repeating the above steps till all the training examples are complete.
After we have completed all the training examples we will have the final hypothesis when can use to classify the new examples.
