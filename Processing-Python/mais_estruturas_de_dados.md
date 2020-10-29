# Estruturas de dados

Coleção é o nome genérico para diversaas estruturas de dados, as sequências são coleções preservam (guardam) a ordem dos itens, como uma lista (*list*) ou tupla (*tuple*). Outras coleções não são sequências, pois não guardam a ordem dos itens, como um conjunto (*set*) ou dicionário (*dict*).

### Listas

```python
frutas = ["manga", "manga", "morango", "abacaxi"]  # uma lista de frutas
```

Python usa `[` colchete (*square brackets*) para listas, sequências mutáveis e heterogêneas de itens (preservam a ordem, mas você pode trocar itens e reordenar).
As listas Lembram um pouco *ArrayList* e *Array* em outras linguagens, mas que eum geral só podem ter itens de um único tipo (são struturas homogêneas).

Em Python moder podemos usar a biblioteca *numpy* para obter estruturas sofisticadas como matrizes de muitas dimensões. É possível uma primeira aproximação destas estruturas usando listas de listas para representar matrizes!

```python
[[0, 12, 2, 3],
 [1, 22, 3, 4],
 [1, 22, 3, 4],
 [1, 22, 3, 4]]
```

### Tuplas

```python    
ponto = (120, 34)
```
Uma tupla pode ser construída com `( )` parenteses, para fazer uma tupla de um item só precisa acrescentar uma vírgula: `(item, )`
Tuplas são sequências imutáveis (preservam a ordem, mas não dá pra reordenar ou trocar itens)

### Conjuntos

```python
numeros_feios = {2342345, 3454674567, 2346234623463, 2473565656457}
```
Os conjuntos eliminam repetições automáticamente! Conjunto não preserva a ordem, os itens tem que ser "hasheáveis", em geral só itens imutáveis!

### Dicionários

```python
capitais = {"DF" : "Brasília", "RJ" : "Rio de Janeiro", "SP" : "São Paulo"}
```
Um dicionário pode ser criado com a forma  `{chave : valor} `
Apesar das chaves `}` não é um conjunto! Os dicionarios são conhecidos como mapeamentos ou *hash maps* em outras linguagens.
Não mantém a ordem, chave precisa ser hasheável (em geral imutável) números, strings, tuplas podem servir de chave (conjuntos e listas não!)

```python
d = {}  # cria um dicionário vazio    
```