The jupyter notebook file "1d_test_code.ipynb" runs using the d2l library in jupyter.
The base data is the weekly supplied gasoline in the US. This data series was chosen as it is highly periodic and it has a very volitile event during 2020.
These properties test the capabilities of the method.
For the covariance kernels I choose the sum of the RBF kernel and the Periodic kernel provided by the d2l library.
The period hyperparameter was constrained to one year.
