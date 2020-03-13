İşte burada müzik grubu üyelerine ait bir sözlük. **key** (anahtar) birinci kısımdır (örneğin; 'ipek') ve bununla ilişkili **value** (değer) ise ikinci kısımdır (örneğin 'ritim gitar').

```python
müzikgrubu = {
  'ipek' : 'ritim gitar',
  'ceyda' : 'bas gitar',
  'volkan' : 'solo gitar',
  'gülşen' : 'bas gitar'
    }
```

Burada sözlüğe nasıl anahtar:değer (key:value) eşleri ekleneceği gösteriliyor:

```python
# Bir anahtar:değer (key:value) eşi ekleyin
müzikgrubu['yağmur'] = 'vokal'
```

Burada sözlükten bir anahtar:değer (key:value) eşinin nasıl kaldırıldığı gösteriliyor:

```python
# Anahtar:değer (key:value) eşini kaldır
del müzikgrubu['naz']
```