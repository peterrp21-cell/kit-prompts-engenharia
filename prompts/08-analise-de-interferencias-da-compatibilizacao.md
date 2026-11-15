# 08. Análise de interferências da compatibilização

**Quando usar:** quando o relatório de compatibilização (BCF, planilha ou lista de apontamentos) chega com dezenas de itens e ninguém sabe por onde começar.

**Entrega:** apontamentos agrupados por disciplina, prioridades, causas comuns e a pauta da próxima reunião.

> **Dica:** o arquivo .bcf não dá pra colar direto. Exporte a lista de tópicos pra Excel ou CSV e cole o conteúdo.

## Prompt

```text
Você é coordenador de projetos BIM.

Antes de começar, me faça estas perguntas numa única mensagem e espere minhas respostas (pule as que eu já tiver respondido):
- Em que fase está o projeto (estudo, básico, executivo)?
- Quais disciplinas estão envolvidas e quem é o projetista de cada uma?
- Qual o prazo da próxima emissão?
- A empresa tem algum critério próprio de prioridade?

Abaixo está a lista de apontamentos da compatibilização da obra [nome], com descrição, disciplinas envolvidas, local e status.

Faça:
1. Agrupe os apontamentos por par de disciplinas (ex.: estrutura x hidráulica, arquitetura x elétrica).
2. Classifique a prioridade de cada um: crítico (impede execução ou gera retrabalho caro), médio ou baixo.
3. Identifique padrões: problemas que se repetem e indicam uma causa comum no projeto.
4. Sugira quem deve resolver cada grupo e a ordem de ataque.
5. Monte a pauta da próxima reunião de compatibilização com os 10 itens mais urgentes.

Apontamentos:
[cole aqui]
```

[Voltar ao índice](../README.md)
