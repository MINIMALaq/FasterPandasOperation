# FasterPandasOperation

These notebooks are for [this post](https://medium.com/data-science/how-to-simply-make-an-operation-on-pandas-dataframe-faster-adaea5e41e96) in Towards Data Science.

In NumericTimeTest.ipynb I evaluated speed of iterrows() vs itertuples() vs apply() vs map() vs np.vectorize() vs np.where() vs numba for the same task. The difference is huge. The best method is 480X faster than the worst method on the same function.

In nonNumericTimeTest.ipynb I evaluated speed of iterrows() vs itertuples() vs apply() vs map() vs np.vectorize() vs np.where() vs pandas.Series.map() for the same task.

I added some usecases of Jupyter Notebook's Fortran magic in FortranMagic.
