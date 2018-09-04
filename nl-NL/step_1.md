Hier is een woordenboek van bandleden. De **key** (sleutel) is het eerste deel (bijv. 'John') en de bijbehorende **value** (waarde) is het tweede deel (bijv. 'Ritmegitaar').

```python
band = {
  'john' : 'ritmegitaar',
  'paul' : 'basgitaar',
  'george' : 'lead guitar',
  'ringo' : 'basgitaar'
}
```

Hier lees je hoe je een key:value (sleutel en waarde) toevoegt aan het woordenboek:

```python
# Voeg een key:value toe
band['yoko'] = 'zang'
```

Ga als volgt te werk om een ​​key:value uit het woordenboek te verwijderen:

```python
# Een key:value verwijderen
del band['paul']
```