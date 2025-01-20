# Race predictions
Just a bit of fun
Keeping up to date with data processing and visualisation by looking at F1 race results.

| Notebook | Changes on previous | Accuracy | # Positions away | Comments |
| ----- | ----- | ----- | ----- | ----- |
| [Add hyper-parameter tuning](./race_predictions_v3.ipynb) | Add hyperparameter tuning | 6.35% | 3.95 | A decent improvement over the previous itteration. In the next itteration when we add previous seasons to the dataset I expect the tuning will be even more hepful and the performance will dramatically increase, although the model will take far longer to train.  |
| [Probabilistic Model](./race_predictions_v2.ipynb) |  <ul><li>Change to a probabilistic model </li><li>Add additional parameters</li></ul>| 3.75% | 5.30 | Lower performance as expected, the constraints on the model choices have huge impact but are necessary for usability |
| [Baseline classifier](./race_predictions.ipynb) | Baseline classifier | 11.25% | 4.50 | 