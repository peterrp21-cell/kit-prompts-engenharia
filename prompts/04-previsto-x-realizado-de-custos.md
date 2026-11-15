# 04. Previsto x realizado de custos

**Quando usar:** no fechamento do mês ou antes de uma reunião com a diretoria sobre o custo da obra.

**Entrega:** tabela de desvios com a conta aberta, os maiores estouros, projeção de custo final e sugestões.

> **Atenção:** IA pode errar conta em tabela grande. Confira os números antes de usar. Se a sua ferramenta aceitar arquivo, envie a planilha em vez de colar o texto.

## Prompt

```text
Você é engenheiro de custos.

Antes de começar, me faça estas perguntas numa única mensagem e espere minhas respostas (pule as que eu já tiver respondido no material):
- Em que fase está a obra e qual o percentual executado?
- Os valores do orçamento incluem BDI?
- O que já está contratado e o que ainda falta contratar?
- Pra que é essa análise: reunião com diretoria, revisão de orçamento, negociação?

Abaixo estão o orçamento previsto e o custo realizado até agora da obra [nome], por etapa ou item.

Faça:
1. Uma tabela com item, previsto, realizado, diferença em valor e em percentual, ordenada pelos maiores desvios.
2. Os 5 itens que mais pesam no estouro, com as causas prováveis (preço, quantidade, perda, retrabalho, escopo).
3. A projeção de custo final se o ritmo atual continuar.
4. Sugestões práticas pra recuperar margem nos itens que ainda não foram executados.

Regras: mostre a conta de cada diferença pra eu conferir e separe o que é cálculo do que é hipótese. Se algum dado parecer inconsistente, aponte antes de calcular.

Dados:
[cole aqui a planilha ou a tabela]
```

[Voltar ao índice](../README.md)
