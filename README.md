# Iterative-policy-evaluation

Policy evaluation calculates the state-value function (vπ) for a given policy iteratively through the Bellman expectiation. The initial state-value function(v1) may start from states' value is 0. However, the value will be updated after iterative evaluation and then it will convergence to the some value. At this point, policy can made by values which was convergenced.
It uses full-back method(use the values of the state of the previous steps to obtain the state of a new step for each state).

