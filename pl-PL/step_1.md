Oto słownik zawierający członków zespołu. **Klucz** to pierwsza część (np. 'john'), a powiązana z nim **wartość** jest drugą częścią (na przykład 'gitara rytmiczna').

```python
zespol = {
  'john': 'gitara rytmiczna',
  'paul': 'gitara basowa',
  'george': 'gitara prowadząca',
  'ringo': 'gitara basowa'
}
```

Oto jak dodać parę klucz:wartość do słownika:

```python
# Dodaj parę klucz:wartość
zespol['yoko'] = 'wokal'
```

Oto, jak usunąć parę klucz:wartość ze słownika:

```python
# Usuń parę klucz:wartość
del zespol['paul']
```