Iată un dicționar al membrilor unei trupe. **Cheia** este prima parte (de exemplu, „John“), și are asociată ca **valoare** cea de a doua parte (de exemplu, „chitară ritmică“).

```python
trupa = {
  'john': 'chitara ritmica',
  'paul': 'chitara bass',
  'george': 'chitara principala',
  'ringo': 'chitara bass'
}
```

Iată cum poți adăuga o pereche cheie:valoare în dicționar:

```python
# Adaugă o pereche cheie:valoare
trupa['yoko'] = 'voce'
```

Iată cum poți șterge o pereche cheie:valoare din dicționar:

```python
# Șterge o pereche cheie:valoare
del trupa['paul']
```