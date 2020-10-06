Aquí tienes un diccionario con los miembros de una banda de música. La **clave** es la primera parte (por ejemplo, 'john'), y su **valor** asociado es la segunda parte (por ejemplo, 'guitarra rítmica').

```python
banda = {
  'john': 'guitarra rítmica',
  'paul': 'bajos',
  'george': 'guitarra solista',
  'ringo': 'bajos'
}
```

Así puedes añadir una pareja clave:valor al diccionario:

```python
# Añadir un par clave: valor
banda['yoko'] = 'vocales'
```

Aquí te mostramos cómo eliminar una pareja clave:valor del diccionario:

```python
# Eliminar un par clave:valor
del banda['paul']
```