You can add and remove items from a dictionary quite easily. For instance, in the following dictionary:

```python
band = {
    'john' : 'rhythm guitar',
    'paul' : 'base guitar',
	'george' : 'lead guitar',
    'ringo' : 'base guitar'
	}
```

you can do the following to add or remove key:value pairs.

```python
## removing key:value pairs
del band['paul']
## adding key:value pairs
band['yoko'] = 'vocals'
```
