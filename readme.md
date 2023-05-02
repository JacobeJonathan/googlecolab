# GoogleColab

- [GoogleColab](#Google-colab-python)
- [Librerias](#Importando-librerias)

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

### Importando Librerias
```py
import matplotlib.pyplot as plt
import numpy as np
import pandas as pd
import scipy as sc
import seaborn as sns

```