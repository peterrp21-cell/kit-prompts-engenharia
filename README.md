# Kit: 10 prompts para tirar o engenheiro da planilha

10 prompts prontos para tirar da sua frente boa parte do trabalho manual da engenharia: RDO, ata, relatório, planilha de custo, checklist, e-mail técnico. Funcionam em qualquer IA (ChatGPT, Claude, Gemini) e não dependem de nenhum software específico.

Criado por **Peter Paredes**, engenheiro civil.

## Como usar

1. Abra o prompt que você precisa na pasta [`prompts/`](prompts/) e copie o bloco de texto.
2. Troque o que está entre `[colchetes]` pelo seu contexto e cole logo abaixo o material bruto: áudio transcrito, anotações, planilha, texto do memorial.
3. A IA vai te fazer algumas perguntas antes de gerar. Responda: é esse contexto que deixa o resultado bom.
4. Revise sempre o resultado. A IA organiza e acelera, mas quem assina e decide continua sendo você.

Tudo sai como texto na própria conversa, com seções e tabelas. Para virar arquivo, peça na sequência: "formata pra colar no Word", "transforma em tabela pro Excel" ou "gera um PDF".

## Os 10 prompts

| # | Prompt | O que entrega |
|---|---|---|
| 01 | [RDO a partir de áudio](prompts/01-rdo-a-partir-de-audio.md) | RDO em 7 seções, pronto pra colar no modelo da empresa |
| 02 | [Ata de reunião de obra](prompts/02-ata-de-reuniao-de-obra.md) | Ata formal com tabela de ações (o que, quem, quando) |
| 03 | [Relatório semanal para o cliente](prompts/03-relatorio-semanal-para-o-cliente.md) | Relatório executivo de 1 página |
| 04 | [Previsto x realizado de custos](prompts/04-previsto-x-realizado-de-custos.md) | Tabela de desvios com a conta aberta e projeção de custo final |
| 05 | [Revisor de memorial descritivo](prompts/05-revisor-de-memorial-descritivo.md) | Tabela com trecho, problema, risco e nova redação |
| 06 | [Checklist de inspeção por serviço](prompts/06-checklist-de-inspecao-por-servico.md) | FVS em 3 momentos com critério de aceitação por item |
| 07 | [Resposta técnica a cliente ou fiscalização](prompts/07-resposta-tecnica.md) | E-mail pronto e versão curta pra WhatsApp |
| 08 | [Análise de interferências da compatibilização](prompts/08-analise-de-interferencias-da-compatibilizacao.md) | Apontamentos agrupados, prioridades e pauta da reunião |
| 09 | [Plano de ataque da semana](prompts/09-plano-de-ataque-da-semana.md) | Programação dia a dia, restrições e plano B |
| 10 | [Escopo para contratar empreiteiro](prompts/10-escopo-para-contratar-empreiteiro.md) | Escopo completo e perguntas para equalizar propostas |

## Cuidados

- **Dado sensível:** antes de colar, tire nome de cliente, valores de contrato e dados pessoais se a ferramenta não for aprovada pela sua empresa.
- **Revisão técnica:** a IA pode errar número, norma e quantitativo com toda a confiança do mundo. Confira tudo que vai pra assinatura ou pro cliente. Atenção redobrada nos prompts 04 (custos) e 06 (checklist).
- **Contexto faz diferença:** quanto mais você contar sobre a obra (tipo, porte, fase, cliente), melhor sai o resultado.
- **Itere:** se não ficou bom de primeira, peça ajustes na mesma conversa ("mais curto", "tom mais firme", "inclua a tabela") em vez de começar do zero.

## Contribua

Usou algum prompt e tem uma versão melhor? Abra uma issue ou um pull request. E se o kit te ajudou, deixa uma estrela no repositório.

## Licença

Conteúdo sob a licença [Creative Commons Atribuição 4.0 (CC BY 4.0)](LICENSE): pode usar, adaptar e compartilhar, inclusive comercialmente, desde que cite a fonte.
