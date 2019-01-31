# Some notes of caution

1. It can be very easy to overfit or wrongly fit your model.
One should be frequently performing sanity checks,
cross validation, and visualization.

1. Machine learning can only be as good as your data (AKA garbage-in-garbage-out).
If the data is incorrect, or biased, or too noisy, you may be out of luck.

1. Relatedly, many datasets have underlying racist, sexist and other -ist biases.
Even if you do not intend it, models trained on these datasets will still learn these behaviors.
Building machine learning models to account for and remove these biases is an active topic of research.

1. The datasets on which machine learning models train may contain sensitive or confidential information.
You should take care to not inadvertently leak this information.
As above, dealing with this is an active topic of research.