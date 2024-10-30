9) Agrupamento de Dados por Categoria e Soma de Valores

Dada uma lista de dicionários representando despesas com categoria e valor, implemente uma função que:

- Agrupe os valores por categoria e some os valores de cada grupo.
- Retorne um dicionário onde as chaves são as categorias e os valores são as somas dos valores.

Exemplo de entrada:
    [
        {"categoria": "Alimentação", "valor": 100},
        {"categoria": "Transporte", "valor": 50},
        {"categoria": "Alimentação", "valor": 30},
        {"categoria": "Transporte", "valor": 20},
        {"categoria": "Lazer", "valor": 60}
    ]

Exemplo de saída esperada:
    {
        "Alimentação": 130, 
        "Transporte": 70, 
        "Lazer": 60
    }
