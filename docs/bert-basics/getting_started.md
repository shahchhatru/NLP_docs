---
sidebar_position: 1
syntax_highlighting: true
---


# Install the transformer library 
#### this library is provided by hugging face.

```bash

pip install transformers -q
```
#### import the libraries

```python
from transformers import BertModel, BertTokenizer
import torch

```
#### load the bert model

```python
model = BertModel.from_pretrained('bert-base-uncased')

```
