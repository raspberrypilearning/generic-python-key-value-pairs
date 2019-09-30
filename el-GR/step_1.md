Here is a dictionary of band members. The **key** is the first part (e.g. 'john'), and its associated **value** is the second part (e.g. 'rhythm guitar').

```python
band = {
  'john': 'ρυθμική κιθάρα',
  'paul': 'μπάσο',
  'george': 'σόλο κιθάρα',
  'ringo': 'μπάσο'
}
```

Mπορείς να προσθέσεις ένα ζευγάρι κλειδιού:τιμής στο λεξικό ως εξής:

```python
# Πρόσθεσε ένα ζεύγος κλειδιού:τιμής
band['yoko'] = 'φωνητικά'
```

Έτσι μπορείς να καταργήσεις ένα ζεύγος κλειδιού:τιμής από το λεξικό:

```python
# Remove a key:value pair
del band['paul']
```