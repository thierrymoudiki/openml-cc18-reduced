# OpenML CC-18 reduced 

- Data sets with more than 1000 rows and 10 columns are reduced to shape `(1000, 10)`

- Subsample to `1000` using `nnetsauce.Subsampler` (histogram-based subsampling of response variable)

- `10` most important features according to sklearn's `RandomForestClassifier` with 50 trees

