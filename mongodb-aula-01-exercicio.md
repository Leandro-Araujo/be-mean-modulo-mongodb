# MongoDB - Aula 01 - Exercício
autor: Leandro Silva Araújo

## Importando os restaurantes

```
mongoimport --db be-mean --collection restaurantes --drop --file restaurantes.json
connected to: 127.0.0.1
2016-06-06T17:41:40.414-0300 dropping: be-mean.restaurantes
2016-06-06T17:41:42.016-0300 check 9 25359
2016-06-06T17:41:42.487-0300 imported 25359 objects
```

## Contando os restaurantes

```
db.restaurantes.find({}).count()
25359
```
