# Simple cohort analysis wrapper on pandas

## USAGE

```python
!pip install pandas-cohort

import pandas_cohort as ch
import pandas as pd

cohorts = df.cohort.retention(user_col='CustomerID', date_column='InvoiceDate',)
```
