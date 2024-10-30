Atividade proposta pela professora Maiara sacramento da faculdade Anhanguera do curso de Análise e desenvolvimento de sistemas com o objetivo de criar uma calculadora de simulação de juros.
  
  # ATIVIDADE "SOU DEV" DA DISCIPLINA LOGICA E MATEMATICA COMPUTACIONAL

  Explicação dos codigos

  Função "calcular_juros":

Objetivo: Calcular os juros com base no dia de pagamento.

  Parâmetros:

total: o valor total das compras.

dia_pagamento: o dia em que a fatura foi paga.

  Lógica:

Se o pagamento for até o dia 25, não há juros (return 0).

Caso contrário, calcula os dias de atraso (dias_atraso) e aplica os juros: 3% sobre o total mais 1% por dia de atraso.


  Função " main":
  Explicação:

Objetivo: Principal função do programa que coleta os dados das compras, calcula os juros e exibe o total da fatura.

  Processo:

Inicializa total_compras com zero.

  Loop While:

Solicita o valor da compra e adiciona ao total.

Pergunta se é a última compra. Se sim ('s'), sai do loop.

Solicita o dia do pagamento da fatura.

Chama a função calcular_juros para obter os juros aplicáveis.

Calcula o total da fatura somando as compras e os juros.

Exibe o total das compras, os juros aplicados e o total da fatura.
