# Implementation Notes

## On Decision Tree Regressor Implementation
### Next Steps
1. Perform Refactor
- Simplify the code as much as possible. Remove all the fluff.
- Figure out why `jax` was slower in numpy.
- Rethink on how the trees actually grow.
2. Investigate the important hyperparameters in Decision Tree Regression on Sklearn
- Select certain hyperparameters and implement them
3. Figure out how to make Decision Tree faster at `min_leaves=1`


## Implement Decision Tree Classifier
1. Repurpose Regression Trees to Work as Classifier