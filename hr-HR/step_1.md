Pogledaj ovaj rječnik u kojem se nalaze imena članova benda. Prvi dio (npr. „ivan”) je **ključ**, a drugi dio (npr „ritam gitara”) je **vrijednost** s kojom je ključ povezan.

```python
bend = {
  'ivan': 'ritam gitara',
  'marko': 'bas gitara',
  'marin': 'glavna gitara',
  'petar': 'bas gitara'
}
```

Evo kako dodati ključ:vrijednost par u rječnik:

```python
# Dodaj ključ:vrijednost par
bend['ana'] = 'vokal'
```

Evo kako ukloniti ključ:vrijednost par iz rječnika:

```python
# Ukloni ključ:vrijednost par
del bend ['marko']
```