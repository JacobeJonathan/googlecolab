# GoogleColab

- [GoogleColab](#Google-colab-python)


### Google colab python

- Primero subimos el archivo csv
- Luego utilizamos el  archivo csv 
- verificamos si se subio 
```py
from google.colab import files 
uploaded = files.upload()

import pandas as pd
df = pd.read_csv('iris.csv')

print(df)

```