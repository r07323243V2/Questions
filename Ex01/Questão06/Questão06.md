6) Ranking de Produtos por Avaliação

Suponha uma lista de produtos, onde cada produto é representado por um dicionário com nome, preco, e avaliacao (número de 1 a 5).

- Filtre produtos com avaliação menor que 4.
- Retorne uma lista dos nomes dos produtos restantes, ordenados pela avaliação em ordem decrescente, e, em caso de empate, pelo menor preço.

Exemplo de entrada:
    [
        {"nome": "Produto A", "preco": 100, "avaliacao": 5},
        {"nome": "Produto B", "preco": 200, "avaliacao": 3},
        {"nome": "Produto C", "preco": 150, "avaliacao": 4},
        {"nome": "Produto D", "preco": 130, "avaliacao": 5}
    ]

Exemplo de saída esperada:
    [
        "Produto A", 
        "Produto D", 
        "Produto C"
    ]
