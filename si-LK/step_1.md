සංගීත කණ්ඩායමේ සාමාජිකයන්ගේ ශබ්ද කෝෂය(dictionary එක) මෙන්න. **යතුර(key)** යනු පළමු කොටසයි (උදා: 'ජෝන්' - john), සහ ඔහුට සම්බන්ධ **අගය(value)** දෙවන කොටසයි (උදා: 'රිදම් ගිටාරය' - rhythm guitar).

```python
band = {
  'john' : 'rhythm guitar',
  'paul' : 'bass guitar',
  'george' : 'lead guitar',
  'ringo' : 'bass guitar'
    }
```

ශබ්ද කෝෂට(dictionary එකට) යතුර:අගය (key:value) යුගලයක්(pair එකක්) එකතු කරගන්නේ කෙසේද යන්න පහත පරිදි වේ:

```python
# Add a key:value pair
band['yoko'] = 'vocals'
```

ශබ්ද කෝෂයෙන් (dictionary එකෙන්) යතුර:අගය (key:value) යුගලයක්(pair එකක්) ඉවත් කරගන්නේ කෙසේද යන්න පහත පරිදි වේ:

```python
# Remove a key:value pair
del band['paul']
```