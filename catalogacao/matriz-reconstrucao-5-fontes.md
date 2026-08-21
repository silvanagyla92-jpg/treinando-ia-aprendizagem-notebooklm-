# Matriz de reconstrução das 5 fontes do caderno

## Objetivo

Esta matriz registra o cruzamento entre as referências encontradas nas perguntas, prompts, respostas e análises e o inventário oficial de 25 fontes.

O objetivo é separar claramente:

- fontes efetivamente identificadas no inventário;
- fontes citadas nas análises;
- fontes que aparecem como referências do processo;
- fontes cuja utilização original no caderno ainda não pode ser comprovada.

## 1. Resultado da auditoria

O repositório comprova a existência de **25 fontes catalogadas** e comprova referências a essas fontes nas análises. Entretanto, os documentos atuais não preservam uma lista textual que identifique, de forma inequívoca, quais cinco fontes foram originalmente carregadas no caderno do NotebookLM.

Por isso, a frequência de uma fonte nas análises não será usada como prova de que ela pertence ao conjunto original de cinco fontes.

## 2. Fontes citadas nas análises

As análises identificam referências individuais por código e arquivo. Entre elas estão fontes acadêmicas, artigos e portais, fonte institucional e fontes internas.

A matriz oficial em [`analises/rastreabilidade-fontes.md`](../analises/rastreabilidade-fontes.md) relaciona as 25 fontes e seus temas analíticos.

## 3. Classificação da evidência

| Critério | Significado |
|---|---|
| Uso direto comprovado | Existe registro explícito que identifica a fonte como utilizada no caderno. |
| Referência analítica | A fonte é citada em uma análise, mas isso não comprova que foi uma das cinco fontes originais do caderno. |
| Evidência insuficiente | Há indícios ou contexto relacionado, mas não existe comprovação documental suficiente. |
| Não identificado | Não foi localizada evidência específica de uso no caderno. |

## 4. Estado das cinco fontes

| Fonte do caderno | Fonte correspondente nas 25 | Categoria | Evidência de uso original | Status |
|---|---|---|---|---|
| Fonte 01 | Não identificada documentalmente | Não determinada | Não localizada | Evidência insuficiente |
| Fonte 02 | Não identificada documentalmente | Não determinada | Não localizada | Evidência insuficiente |
| Fonte 03 | Não identificada documentalmente | Não determinada | Não localizada | Evidência insuficiente |
| Fonte 04 | Não identificada documentalmente | Não determinada | Não localizada | Evidência insuficiente |
| Fonte 05 | Não identificada documentalmente | Não determinada | Não localizada | Evidência insuficiente |

## 5. O que foi confirmado

### Inventário

O projeto possui 25 fontes:

- 7 acadêmicas;
- 15 artigos e portais;
- 1 institucional;
- 2 internas.

Total: **25 fontes**.

### Referências analíticas

As análises utilizam referências individuais das fontes. Por exemplo, a Resposta 02 identifica A01, A05, A07, I01, P13, A02, A04, P05, P08, P14, P15, INT01, P01, P02, P03, P07, P09, P10, P11, P12 e INT02 em diferentes seções.

Isso comprova que essas fontes fazem parte da camada documental da análise, mas não comprova, isoladamente, que foram as cinco fontes inicialmente selecionadas no NotebookLM.

### Prompts

O Prompt 03 determina que a comparação seja feita com base nas fontes disponíveis, mas não apresenta uma relação nominal das cinco fontes carregadas. Portanto, também não pode ser utilizado isoladamente para reconstruir a seleção original.

## 6. Regra para conclusão

A identificação definitiva das cinco fontes somente deve ser feita quando houver pelo menos uma evidência direta, como:

- exportação ou registro textual do NotebookLM;
- lista original das fontes carregadas;
- registro documental que associe explicitamente a fonte ao caderno;
- captura de tela legível que mostre a seleção, caso possa ser validada de forma inequívoca.

Prints aleatórios da interface do NotebookLM não serão considerados prova da seleção das cinco fontes.

## 7. Conclusão

A auditoria não encontrou evidência suficiente para afirmar quais cinco das 25 fontes compuseram originalmente o caderno.

Isso não significa que as cinco fontes não tenham sido utilizadas. Significa apenas que **a seleção original não está preservada de forma documental suficiente no estado atual do repositório**.

Até que exista evidência adicional, o README principal não deve declarar uma distribuição específica das cinco fontes por categoria.

---

**Projeto:** Gestão Financeira Pessoal com NotebookLM  
**Autora:** Nágyla Silva

*Projeto integrante do portfólio prático de estudos em Inteligência Artificial, com foco em engenharia de prompts, avaliação crítica de respostas de IA e desenvolvimento de competências para AI Trainer, AI Response Evaluator e Data Annotator.*
