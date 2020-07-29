येथे बँड सदस्यांचा शब्दकोष आहे. **key** पहिला भाग आहे (उदा. 'john'), आणि त्याशी संबंधित **value** दुसरा भाग आहे (उदा. 'rhythm guitar'').

```python
band = {
  'john' : 'rhythm guitar',
  'paul' : 'bass guitar',
  'george' : 'lead guitar',
  'ringo' : 'bass guitar'
    }
```

key कशी जोडावी ते येथे आहेः शब्दकोशात मूल्य जोडया जोडणे:

```python
# Add a key:value pair
band['yoko'] = 'vocals'
```

key कशी काढून टाकावी ते येथे आहे: शब्दकोषातून मूल्य जोडया काढणे:

```python
# Remove a key:value pair
del band['paul']
```