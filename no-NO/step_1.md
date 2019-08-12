Her er en ordbok av bandmedlemmer. **Nøkkelen** er den første delen (f.eks. 'john'), og den tilhørende **verdien** er den andre delen (f.eks. 'rytmegitar').

```python
band = {
  'john': 'rytmegitar',
  'paul': 'bassgitar',
  'george': 'hovedgitar',
  'ringo': 'bassgitar'
}
```

Slik legger du til et nøkkel:verdi-par i ordboken:

```python
# Legg til et nøkkel:verdi-par
band ['yoko'] = 'vokal'
```

Slik fjerner du et nøkkel:verdi-par fra ordlisten:

```python
# Fjern et nøkkel:verdi-par
del band ['paul']
```