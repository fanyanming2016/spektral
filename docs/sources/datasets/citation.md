### load_data


```python
spektral.datasets.citation.load_data(dataset_name='cora', normalize_features=True)
```



Loads a citation dataset using the public splits as defined in
[Kipf & Welling (2016)](https://arxiv.org/abs/1609.02907).

**Arguments**  

- ` dataset_name`: name of the dataset to load ('cora', 'citeseer', or
'pubmed');

- ` normalize_features`: if True, the node features are normalized;

**Return**  
 The citation network in numpy format, with train, test, and
validation splits for the targets and masks.
