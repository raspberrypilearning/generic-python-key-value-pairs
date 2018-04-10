موضح أدناه قاموس بأعضاء فرقة موسيقية. يكون **المفتاح** هو الجزء الأول (مثل 'john')، وتكون **القيمة** المقترنة به هي الجزء الثاني (مثل 'rhythm guitar').

python```
band = {
  'john' : 'rhythm guitar',
  'paul' : 'bass guitar',
  'george' : 'lead guitar',
  'ringo' : 'bass guitar'
	}
```

تكون إضافة زوج مفتاح:قيمة إلى القاموس كما يلي:

python```
# Add a key:value pair
band['yoko'] = 'vocals'
```

تكون إزالة زوج مفتاح:قيمة من القاموس كما يلي:

python```
# Remove a key:value pair
del band['paul']
```
