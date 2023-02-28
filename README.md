# Credit_Risk_Resampling

![An image for the header of the Repository](/Images/risk.png)

This application uses various techniques to train and evaluate models with imbalanced classes. it also uses a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.



## Technologies
This platform uses `python 3.7.13` with the following libraries imported in the first code block includes: `Pandas`, `numpy`, `scikit-learn`, `pathlib`, and `Imbalanced Learn`.

---
## Installation Guide 

In case Pandas library is not available, run the following code in your terminal:

```python

pip install pandas
```


To install `scikit-learn`, `imbalance-learn` make sure your Conda `dev` environment is active, run the following command:

```python
pip install -U scikit-learn
```

```python
pip install -c conda-forge imbalanced-learn
```


To confirm the  installation, run the following code in your terminal:

```python
conda list scikit-learn
conda list imbalanced-learn
 ```
 
---

## Usage

Libraries that we had to import are the following:

```
import numpy as np
import pandas as pd
from pathlib import Path
from sklearn.metrics import balanced_accuracy_score
from sklearn.metrics import confusion_matrix
from imblearn.metrics import classification_report_imbalanced

```

---
## Contributors

Baha Amour
---

## License

MIT.