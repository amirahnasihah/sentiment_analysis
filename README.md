# Sentiment analysis 
A part of the Natural Language Processing (NLP) techniques that consists in extracting emotions related to some raw texts. This is usually used on social media posts and customer reviews in order to automatically understand if some users are positive or negative and why. The goal of this study is to learn how sentiment analysis can be performed using python.

Here use some hotel reviews data. Each observation consists in one customer review for one hotel. Each customer review is composed of a textual feedback of the customer's experience at the hotel and an overall rating. The data can be found [HERE](https://www.kaggle.com/jiashenliu/515k-hotel-reviews-data-in-europe)


Python libraries:
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

![Web capture_4-3-2022_22318_colab research google com](https://user-images.githubusercontent.com/89834315/156893273-271855a5-571b-4a93-a33c-f6d905c78f7a.jpeg)

![Web capture_4-3-2022_22219_colab research google com](https://user-images.githubusercontent.com/89834315/156893279-92692a9a-cee7-410a-a245-f678eb935190.jpeg)

