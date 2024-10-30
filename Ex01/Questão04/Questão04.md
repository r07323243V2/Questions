4) Filtragem e Cálculo de Transações Bancárias

Você recebe uma lista de dicionários representando transações bancárias, cada uma com os campos tipo (saque ou depósito), valor, e data.

- Filtre e some os valores de todas as transações de saque feitas no último mês.
- Retorne o total dos saques do mês.

Exemplo de entrada:
    [
        {"tipo": "saque", "valor": 100, "data": "2023-09-01"},
        {"tipo": "deposito", "valor": 200, "data": "2023-10-01"},
        {"tipo": "saque", "valor": 150, "data": "2023-10-02"},
        {"tipo": "saque", "valor": 120, "data": "2023-10-05"}
    ]

Exemplo de saída esperada: 370
