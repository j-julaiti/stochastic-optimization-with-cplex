# Stochastic Optimization with CPLEX

Different stochastic optimization methodologies will be implemented using CPLEX in python with examples.

## Part I:
A production planning problem with uncertain demands is modeled. Five methods are implemented to solve the problem and the performances of the models are evaluated via simulations. A good method should have a low objective function value while having a high probability of being feasible when uncertain events are realized (meeting the demands in this context). 

The methods are:
1. Deterministic model: ignore the uncertainty
2. Worst-case model: make sure the demands are met in the worst case
3. Scenario-based model: K scenarios are sampled, and the corresponding (deterministic) problem is solved. Then the final decision will be the one in the worst case of the K scenarios
4. Model with chance constraints: the model ensures that each uncertain demand will have 1-epsilon probability to be met
5. Model with recource: the model will allow the infeasibility by assigning penalty



