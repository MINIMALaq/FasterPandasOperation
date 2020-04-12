# FasterPandasOperation
evaluate different methods speed on a pandas DataFrame.

In NumericTimeTest.ipynb I evaluated speed of iterrows() vs itertuples() vs apply() vs map() vs np.vectorize() vs np.where() vs numba vs fortran magic for the same task. The difference is huge. The best method is 480X faster than the worst method on the same function.

In nonNumericTimeTest.ipynb I evaluated speed of iterrows() vs itertuples() vs apply() vs map() vs np.vectorize() vs np.where() vs pandas.Series.map() for the same task.
