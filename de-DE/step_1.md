Hier ist ein Wörterbuch der Bandmitglieder. Der **Schlüssel** ist der erste Teil (z.B. 'John'), und der dazugehörige **Wert** ist der zweite Teil (z.B. 'Rhythmusgitarre').

```python
band = {
  'John': 'Rhythmusgitarre',
  'Paul': 'Bassgitarre',
  'George': 'Leadgitarre',
  'Ringo': 'Schlagzeug'
}
```

So fügst du dem Wörterbuch ein Schlüssel-Wert-Paar hinzu:

```python
# Ein Schlüssel-Wert-Paar hinzufügen
band ['Yoko'] = 'vocals'
```

So entfernst du ein Schlüssel-Wert-Paar aus dem Wörterbuch:

```python
# Ein Schlüssel-Wert-Paar entfernen:
del band ['Paul']
```