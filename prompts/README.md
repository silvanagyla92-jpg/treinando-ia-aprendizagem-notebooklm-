# Prompts utilizados no projeto

Esta pasta reúne os prompts elaborados, testados e refinados durante a experiência com o **NotebookLM**, no projeto **"Treinando uma IA de Aprendizagem: Gestão Financeira Pessoal com NotebookLM"**.

Os prompts documentam a engenharia de prompts aplicada à investigação: exploração, aprofundamento, comparação, análise crítica e síntese.

## Arquivos

| Etapa | Prompt | Finalidade |
|---|---|---|
| 01 | [`prompt-01-exploracao-conceituacao.md`](./prompt-01-exploracao-conceituacao.md) | Explorar e conceituar o tema a partir das fontes. |
| 02 | [`prompt-02-aprofundamento.md`](./prompt-02-aprofundamento.md) | Aprofundar conceitos e relações identificadas. |
| 03 | [`prompt-03-comparacao-fontes.md`](./prompt-03-comparacao-fontes.md) | Comparar perspectivas e evidências entre fontes. |
| 04 | [`prompt-04-analise-critica.md`](./prompt-04-analise-critica.md) | Avaliar criticamente as respostas e suas evidências. |
| 05 | [`prompt-05-sintese.md`](./prompt-05-sintese.md) | Integrar os achados em uma síntese estruturada. |

## Organização

```text
prompts/
├── README.md
├── prompt-01-exploracao-conceituacao.md
├── prompt-02-aprofundamento.md
├── prompt-03-comparacao-fontes.md
├── prompt-04-analise-critica.md
└── prompt-05-sintese.md
```

## Sequência de investigação

**exploração e conceituação → aprofundamento → comparação → análise crítica → síntese**

Os prompts foram construídos a partir das perguntas estratégicas documentadas no [README principal](../README.md).

## Critérios utilizados

- clareza e objetivo explícito;
- contextualização do tema;
- especificidade da tarefa;
- fundamentação nas fontes disponíveis no NotebookLM;
- distinção entre evidência, síntese, interpretação e inferência;
- organização esperada da resposta;
- possibilidade de refinamento e reutilização.

O processo foi iterativo: quando uma resposta não atendia adequadamente ao objetivo, a instrução era reformulada, especialmente quanto ao formato e ao tipo de análise solicitado.

## Relação com o restante do projeto

```text
fontes → perguntas estratégicas → prompts → respostas → análises → resultados
```

- [`fontes/`](../fontes/) — fontes utilizadas na investigação.
- [`evidencias/`](../evidencias/) — registros das interações e materiais do processo.
- [`analises/`](../analises/) — análises e validações.
- [`resultados/`](../resultados/) — resultados documentados.

---

**CI&T – Do Prompt ao Agente** · **DIO — Treinando uma IA de Aprendizagem** · **NotebookLM**  
**Autora:** Nágyla Silva  

**Projeto:** *Treinando uma IA de Aprendizagem: Gestão Financeira Pessoal com NotebookLM*