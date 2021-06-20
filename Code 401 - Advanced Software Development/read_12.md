# Pandas

- A python package used for data manipulation and analysis.

> import pandas as pd

## What can be done using pandas?

### Object creation

> Series by passing a list of values, letting pandas create a default integer index:
> s = pd.Series([1, 3, 5, np.nan, 6, 8])

> DataFrame by passing a NumPy array, with a datetime index and labeled columns:
> df = pd.DataFrame(np.random.randn(6, 4), index=dates, columns=list("ABCD"))

### Viewing data

> df.head() ==> top rows of the frame
> df.tail(3) ==> bottom rows of the frame
> df.index
> df.columns
> df.to_numpy() ==> datatype to float

### Selection

- Getting (df["A"]) -- slices the row
- Selection by label (df.loc[:, ["A", "B"]])

### Missing data

(NaN)

### Operations

- Stats
- Apply
- Histogramming
