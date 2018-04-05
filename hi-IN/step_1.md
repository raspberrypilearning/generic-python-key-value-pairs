बैंड के सदस्यों का शब्दकोष इस प्रकार है। **की** प्रथम भाग (उदाहरण 'john') है, और इससे संबंधित **मूल्य** दूसरा भाग (उदाहरण 'rhythm guitar') है।

```python
band = {
  ‘john' : ‘rhythm guitar',
  ‘paul' : ‘bass guitar',
  ‘george' : ‘lead guitar',
  ‘ringo' : ‘bass guitar'
	}
```

शब्दकोष में एक key:value जोड़ा शामिल करने का तरीका इस प्रकार है:

```python
# Add a key:value pair
band['yoko'] = 'vocals'
```

शब्दकोष में से key:value जोड़ा हटाने का तरीका इस प्रकार है:

```python
# Remove a key:value pair
del band['paul']
```
