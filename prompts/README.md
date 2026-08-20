# Prompts utilizados no projeto

Esta pasta reúne os **5 prompts** utilizados e documentados durante a experiência com o NotebookLM.

Os prompts representam a evolução da investigação: primeiro compreender o tema, depois aprofundar, comparar, analisar criticamente e sintetizar.

## Os 5 prompts

| Nº | Arquivo | Finalidade |
|---|---|---|
| 01 | [`prompt-01-exploracao-conceituacao.md`](./prompt-01-exploracao-conceituacao.md) | Explorar e conceituar o tema a partir das fontes. |
| 02 | [`prompt-02-aprofundamento.md`](./prompt-02-aprofundamento.md) | Aprofundar conceitos e relações identificadas. |
| 03 | [`prompt-03-comparacao-fontes.md`](./prompt-03-comparacao-fontes.md) | Comparar perspectivas e evidências entre fontes. |
| 04 | [`prompt-04-analise-critica.md`](./prompt-04-analise-critica.md) | Avaliar criticamente respostas e evidências. |
| 05 | [`prompt-05-sintese.md`](./prompt-05-sintese.md) | Integrar os principais achados em uma síntese. |

## Sequência metodológica

```text
01 Explorar
      ↓
02 Aprofundar
      ↓
03 Comparar
      ↓
04 Analisar criticamente
      ↓
05 Sintetizar
```

Essa sequência mostra que os prompts não foram utilizados como perguntas isoladas. Eles compõem um processo progressivo de investigação e aprendizagem.

## Critérios dos prompts

Os prompts foram estruturados considerando:

- objetivo explícito;
- contexto suficiente;
- instrução clara;
- uso das fontes disponíveis no NotebookLM;
- solicitação de comparação quando necessária;
- separação entre evidência e interpretação;
- formato esperado para a resposta;
- possibilidade de refinamento.

## Relação com as perguntas estratégicas

As perguntas estratégicas definem **o que investigar**; os prompts definem **como orientar a IA para realizar a investigação**.

```text
pergunta estratégica
        ↓
       prompt
        ↓
resposta do NotebookLM
        ↓
verificação e análise
```

## Rastreabilidade

- [`../fontes/`](../fontes/) — materiais utilizados pelo NotebookLM.
- [`../evidencias/`](../evidencias/) — registros do processo.
- [`../analises/`](../analises/) — comparação e avaliação das informações.
- [`../resultados/`](../resultados/) — resultados selecionados.

## Padronização

Os cinco arquivos de prompt seguem o mesmo padrão de apresentação no Markdown. O conteúdo dos prompts foi preservado; a padronização tem como objetivo melhorar a leitura, a comparação e a documentação.

## Resultado

A pasta demonstra a aplicação prática de **engenharia de prompts** em uma investigação baseada em fontes, evidenciando evolução da consulta inicial até a síntese final.

---

**CI&T – Do Prompt ao Agente** · **DIO — Treinando uma IA de Aprendizagem**  
**Projeto:** *Gestão Financeira Pessoal com NotebookLM*  
**Autora:** Nágyla Silva