# Race predictions
Just a bit of fun
Keeping up to date with data processing and visualisation by looking at F1 race results.

| Notebook | Changes on previous | Accuracy | # Positions away | Comments |
| ----- | ----- | ----- | ----- | ----- |
|  ~~~ | <ul><li>Update model from random forest to regression based</li><li>Re-implement days since as a model weight rather than column</li> | ~~ | ~~ | ~~ |
| [Add additional seasons data to training](./race_predictions_v4.ipynb) | Add previous 2 seasons results to training data | 8.75% | 3.55 | Again a solid improvement over the previous results, shows how previous experience and maybe car specifics impact performance | 
| [Add hyper-parameter tuning](./race_predictions_v3.ipynb) | Add hyperparameter tuning | 6.35% | 3.95 | A decent improvement over the previous itteration. In the next itteration when we add previous seasons to the dataset I expect the tuning will be even more hepful and the performance will dramatically increase, although the model will take far longer to train.  |
| [Probabilistic Model](./race_predictions_v2.ipynb) |  <ul><li>Change to a probabilistic model </li><li>Add additional parameters</li></ul>| 3.75% | 5.30 | Lower performance as expected, the constraints on the model choices have huge impact but are necessary for usability |
| [Baseline classifier](./race_predictions.ipynb) | Baseline classifier | 11.25% | 4.50 | 