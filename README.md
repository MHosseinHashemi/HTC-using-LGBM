# Logging the fine-tuninig

Version-0:<br>
```python
params = {
    'max_depth': 6,         
    'learning_rate': 0.05,
    'num_leaves': 60,        
    'num_class': total_classes,
    'objective': 'multiclass',
    'min_data_in_leaf': 20,
    'min_sum_hessian_in_leaf': 1e-4,
    'n_jobs': -1,
    'verbose': -1             
}
```


Early stopping activated on epoch: <b>748</b><br>
validation's multi_logloss: <b>1.7545</b><br>
best epoch is: <b>648</b><br>
validation's multi_logloss: <b>1.7530</b><br>

------------------------------------------------------------

Version-1:<br>
```python
params = {
    'max_depth': 6,         
    'learning_rate': 0.05,
    'num_leaves': 120,        
    'num_class': total_classes,
    'objective': 'multiclass',
    'min_data_in_leaf': 20,
    'min_sum_hessian_in_leaf': 1e-4,
    'n_jobs': -1,
    'verbose': -1             
}
```


Early stopping activated on epoch: <b>678</b><br>
validation's multi_logloss: <b>1.7529</b><br>
best epoch is: <b>648</b><br>
validation's multi_logloss: <b>1.7526</b><br>


<br>
<h5><i>In progress...</i></h5>
