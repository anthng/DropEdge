# DropEdge
This is a Pytorch implementation of paper: DropEdge: Towards Deep Graph Convolutional Networks on Node Classification

The data format is [this repo](https://github.com/tkipf/gcn). The `load_data()` function in the [utils.py](https://github.com/tkipf/gcn/blob/master/gcn/utils.py),
this function helps organize data in preparation of training.

```python

  # load_data() function in train.py
  
  adj, features, y_train, y_val, y_test, train_mask, val_mask, test_mask = load_data(FLAGS.dataset)
  
```

