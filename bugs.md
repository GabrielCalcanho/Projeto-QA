# BUG IDENTIFICADO — Valor negativo permitido

# Evidencias: 
![bugs/bug001.png]
BUG001 — Sistema permite valores negativos na venda

# Descrição:
O sistema permite adicionar vendas com valores negativos, o que é incorreto para o contexto de faturamento.

# Passos para reproduzir:
Abrir a calculadora de faturamento MEI
Inserir valor: -5
Inserir data válida (ex: 18/05/2026)
Clicar em “Adicionar”

# Resultado atual:

Venda negativa é adicionada na lista
Total mensal é reduzido incorretamente

# Resultado esperado:
Sistema deve bloquear valores negativos
Exibir mensagem: “Valor inválido”

# Severidade:
Alta (afeta cálculo financeiro diretamente)

# Impacto:
Faturamento incorreto
Relatórios errados
Pode gerar decisões financeiras equivocadas