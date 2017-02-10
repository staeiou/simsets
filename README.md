# simsets

Python package for creating random simulated datasets using the variables and values in an existing dataset.

## Usage

pip install simsets

```
import simsets
import pandas as pd

original_dataframe = pd.from_csv("data.csv") # or any other way of creating a pandas dataframe

simulated_dataframe = simsets.simulate_data(original_dataframe, length_of_simulated_dataframe)
```
## Dependencies

numpy, pandas

