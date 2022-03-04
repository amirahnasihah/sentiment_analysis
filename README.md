# sentiment_analysis
🦾 try out sentiment analysis on a large data of hotel reviews dataset for sentiment analysis

```python
import pandas as pd
import matplotlib.pyplot as plt
import numpy
import tensorflow as tf
import seaborn as sns
```

```python
from tensorflow.keras.preprocessing.text import Tokenizer
from tensorflow.keras.preprocessing.sequence import pad_sequences
from tensorflow.keras.models import Sequential
from tensorflow.keras.layers import LSTM,Dense,Dropout,SpatialDropout1D
from tensorflow.keras.layers import Embedding
```
