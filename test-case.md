# CASOS DE TESTE — Calculadora MEI

# CT01 — Adicionar venda válida

# Pré-condição: sistema aberto

# Passos:

1-Inserir valor “100”
2-inserir data válida

Clicar em “Adicionar”

# Resultado esperado:

venda é adicionada na lista
valor aparece corretamente
data é exibida corretamente
total mensal atualiza para 100
sistema não exibe erro

CT02 — Impedir valor vazio

# Passos:

Clicar em “Adicionar” sem preencher campo

# Resultado esperado:

Sistema bloqueia ação
Exibe mensagem de erro
CT03 — Impedir valor negativo

# Passos:

Inserir “-50”
Clicar em adicionar

# Resultado esperado:

Sistema rejeita valor
Mostra mensagem de erro
CT04 — Soma correta

# Passos:

Adicionar 100
Adicionar 50

# Resultado esperado:

Total = 150
CT05 — Remover venda

# Passos:

Adicionar valor
Remover item

# Resultado esperado:

Item removido
Total atualizado