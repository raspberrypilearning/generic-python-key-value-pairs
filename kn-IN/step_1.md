ಬ್ಯಾಂಡ್ ಸದಸ್ಯರ ನಿಘಂಟು ಇಲ್ಲಿದೆ. **key** ಇದು ಮೊದಲ ಭಾಗವಾಗಿದೆ (ಉದಾ. 'ಜಾನ್'), ಮತ್ತು ಅದಕ್ಕೆ ಸಂಬಂಧಿಸಿದ **value** ಎರಡನೇ ಭಾಗವಾಗಿದೆ (ಉದಾ. 'ರಿದಮ್ ಗಿಟಾರ್').

```python
band = {
  'john' : 'rhythm guitar',
  'paul' : 'bass guitar',
  'george' : 'lead guitar',
  'ringo' : 'bass guitar'
    }
```

ಕೀಲಿಯನ್ನು ಸೇರಿಸುವುದು ಹೇಗೆ: ನಿಘಂಟಿಗೆ ಮೌಲ್ಯ ಜೋಡಿ:

```python
# Add a key:value pair
band['yoko'] = 'vocals'
```

ಕೀಲಿಯನ್ನು ಸೇರಿಸುವುದು ಹೇಗೆ: ನಿಘಂಟಿಗೆ ಮೌಲ್ಯ ಜೋಡಿ:

```python
# Remove a key:value pair
del band['paul']
```