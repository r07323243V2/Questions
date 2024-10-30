2) Validação de Dados em uma Lista de Produtos

Suponha que você tenha uma lista de dicionários, onde cada dicionário representa um produto com os campos nome, preco (em reais), e categoria.

- Implemente uma função que filtre produtos com preços acima de R$ 50,00 na categoria eletronico.
- Retorne a lista de nomes desses produtos ordenada alfabeticamente.

Exemplo de entrada:
    [
        {"nome": "Fone de Ouvido", "preco": 35.0, "categoria": "eletronico"},
        {"nome": "Teclado", "preco": 120.0, "categoria": "eletronico"},
        {"nome": "Caderno", "preco": 15.0, "categoria": "papelaria"},
        {"nome": "Mouse", "preco": 70.0, "categoria": "eletronico"}
    ]

Exemplo de saída esperada:
    [
        "Mouse", 
        "Teclado"
    ]
