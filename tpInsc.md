## Descrição
Preencher com o código correspondente ao tipo de inscrição, conforme [[Tabela 05]].
### Valores válidos:
1 - CNPJ
2 - CPF

---

#### ==Relação de dependentes==
[[nrInsc]]

---
# Quando pertencer ao GRUPO PAI
[[dadosLotacao]]

## Descrição
Preencher com o código correspondente ao tipo de inscrição, conforme [[Tabela 05]].
### Valores válidos:
1 - CNPJ
2 - CPF
4 - CNO
### Validação:
O campo não deve ser preenchido se [[tpLotacao]] for igual a [01, 10, 21, 24, 90, 91, 92]. Nos demais casos, observar conteúdo exigido para o campo dadosLotacao/nrInsc, conforme [[Tabela 10]].