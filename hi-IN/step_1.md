यहाँ बैंड सदस्यों का एक शब्दकोश है। पहला भाग **key** है (जैसे 'john'), और दूसरा भाग इसका संबद्ध **value** है (जैसे 'rhythm guitar')।

```python
band = {
  'john' : 'rhythm guitar',
  'paul' : 'bass guitar',
  'george' : 'lead guitar',
  'ringo' : 'bass guitar'
    }
```

यहां एक key:value जोड़ी को शब्दकोश में जोड़ने का तरीका बताया गया है:

```python
# एक key:value जोड़ी को जोडे।
band['yoko'] = 'vocals'
```

यहां एक key:value जोड़ी को शब्दकोश से हटाने का तरीका बताया गया है:

```python
# एक key:value जोड़ी को हटाएं
del band['paul']
```