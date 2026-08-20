# Prompts utilizados no projeto

Esta pasta reúne os prompts elaborados, testados e refinados durante a experiência com o **NotebookLM**, no projeto **"Treinando uma IA de Aprendizagem: Gestão Financeira Pessoal com NotebookLM"**.

Os prompts foram estruturados para orientar diferentes etapas da investigação, desde a exploração inicial dos conceitos até a comparação de fontes, análise crítica e síntese do conhecimento.

O objetivo desta pasta é documentar a **engenharia de prompts** aplicada ao projeto, permitindo compreender como as perguntas e instruções foram utilizadas para direcionar a interação com a IA e apoiar o processo de aprendizagem ativa.

---

## 1. Objetivo dos prompts

Os prompts foram desenvolvidos para apoiar a investigação sobre **Gestão Financeira Pessoal**, considerando aspectos relacionados à educação financeira, comportamento econômico, economia comportamental, vieses cognitivos, organização financeira, planejamento e tomada de decisões.

A elaboração dos prompts buscou:

- orientar a exploração dos conteúdos disponíveis nas fontes;
- aprofundar conceitos relevantes para a investigação;
- estabelecer relações entre diferentes informações;
- comparar perspectivas apresentadas pelas fontes;
- estimular a análise crítica das respostas;
- diferenciar informações diretamente apoiadas pelas fontes de interpretações e inferências;
- organizar e sintetizar os conhecimentos obtidos durante o processo.

---

## 2. Perguntas estratégicas que orientaram os prompts

As perguntas estratégicas abaixo (também documentadas na seção 5 do [README principal](../README.md)) foram formuladas antes da engenharia de prompts e serviram de base para a elaboração das instruções aplicadas no NotebookLM. Elas estão organizadas por objetivo de investigação, não por prompt individual — cada prompt (seção 4) foi construído considerando o conjunto de perguntas relevante à sua etapa.

### 2.1 Educação financeira e comportamento

1. Como os vieses cognitivos e a psicologia afetam nossas decisões econômicas?
2. Qual é a distinção teórica fundamental entre "educação financeira" e "organização financeira pessoal"?
3. De que forma o "Viés do Presente" (ou desconto hiperbólico) explica a dificuldade sistemática dos indivíduos em poupar para objetivos de longo prazo?

### 2.2 Economia comportamental e tomada de decisão

1. Qual é a diferença fundamental entre o modelo do "Homo Economicus" e o comportamento real dos seres humanos descrito pela economia comportamental?
2. O que define um "Nudge" e por que ele deve ser barato e fácil de evitar para não ser considerado um mandato ou proibição?
3. Qual é o papel do "Arquiteto de Escolhas" na estruturação do ambiente onde as decisões financeiras são tomadas?

### 2.3 Organização financeira, investimentos e planejamento

1. Quais são os três componentes fundamentais (o "tripé") de qualquer investimento e por que eles nunca estão em níveis máximos simultaneamente?
2. Quais são os cinco passos necessários para transformar um "sonho" abstrato em um "projeto" financeiro concreto?

### 2.4 Análise crítica e integração das fontes

1. Quais são os principais pontos de convergência entre as fontes sobre a importância da educação financeira para a tomada de decisões econômicas?
2. Quais diferenças ou divergências relevantes existem entre as fontes quanto à influência do conhecimento financeiro, do comportamento e dos vieses cognitivos sobre as decisões econômicas?
3. Quais afirmações apresentadas nas respostas anteriores estão diretamente fundamentadas nas fontes disponíveis e quais exigem cautela, interpretação ou verificação adicional?
4. Como os conceitos apresentados nas diferentes fontes podem ser integrados para explicar, de forma abrangente, a relação entre conhecimento financeiro, organização dos recursos, comportamento e tomada de decisões econômicas?

---

## 3. Sequência de investigação

Os prompts foram organizados em uma sequência progressiva, acompanhando o desenvolvimento da investigação no NotebookLM:

**exploração e conceituação → aprofundamento → comparação → análise crítica → síntese**

Essa organização permite passar de uma compreensão inicial dos conceitos para etapas de maior aprofundamento e integração das informações.

---

## 4. Prompts desenvolvidos

| Prompt | Finalidade | Arquivo |
|---|---|---|
| 01 | Exploração/conceituação | `prompt-01-exploracao-conceituacao.md` |
| 02 | Aprofundamento | `prompt-02-aprofundamento.md` |
| 03 | Comparação entre fontes | `prompt-03-comparacao-fontes.md` |
| 04 | Análise crítica | `prompt-04-analise-critica.md` |
| 05 | Síntese | `prompt-05-sintese.md` |

### 4.1 Prompt 01 — Exploração e conceituação

Objetivo: iniciar a investigação e identificar conceitos relacionados ao comportamento financeiro, à tomada de decisão econômica e à influência de fatores psicológicos e cognitivos. A etapa busca estabelecer uma base conceitual antes do aprofundamento dos temas.

### 4.2 Prompt 02 — Aprofundamento

Objetivo: aprofundar os conceitos identificados na etapa inicial, explorando suas características, relações e possíveis aplicações no contexto da Gestão Financeira Pessoal.

### 4.3 Prompt 03 — Comparação entre fontes

Objetivo: comparar informações provenientes de diferentes fontes, identificando convergências, diferenças e possíveis complementaridades entre as perspectivas apresentadas.

### 4.4 Prompt 04 — Análise crítica

Objetivo: analisar criticamente as informações e respostas produzidas durante a investigação, verificando sua fundamentação nas fontes, coerência, limitações, ambiguidades e necessidade de confirmação adicional.

### 4.5 Prompt 05 — Síntese

Objetivo: consolidar os conhecimentos explorados nas etapas anteriores, relacionando conceitos, evidências e perspectivas em uma estrutura organizada de aprendizagem.

---

## 5. Resultados observados

- **Exploração/conceituação:** o prompt direcionou a resposta para a identificação e explicação de conceitos relacionados aos vieses cognitivos, emoções e comportamento financeiro.
- **Aprofundamento:** a instrução mais específica permitiu concentrar a análise no Viés do Presente, no desconto hiperbólico e nas dificuldades relacionadas à poupança de longo prazo.
- **Comparação entre fontes:** o prompt direcionou a resposta para a identificação de pontos de convergência entre diferentes fontes sobre educação financeira e tomada de decisões econômicas.
- **Análise crítica:** a resposta foi orientada para diferenciar informações diretamente fundamentadas nas fontes de interpretações, conclusões e afirmações que exigiam cautela ou verificação adicional.
- **Síntese:** o prompt buscou integrar diferentes conceitos e estabelecer relações entre conhecimento financeiro, organização dos recursos, comportamento e tomada de decisões.

De modo geral, os testes indicaram que prompts com **objetivo claramente definido, contexto específico e critérios de resposta** produziram resultados mais direcionados à finalidade de cada etapa da investigação.

---

## 6. Critérios utilizados na elaboração e no refinamento

Durante a elaboração dos prompts, foram considerados diferentes aspectos para melhorar a qualidade da investigação:

- **Clareza:** instruções apresentadas de forma objetiva e compreensível.
- **Contextualização:** definição do tema e do objetivo da investigação.
- **Especificidade:** indicação do tipo de análise ou informação desejada.
- **Fundamentação:** orientação para considerar as fontes disponíveis no NotebookLM.
- **Pensamento crítico:** incentivo à identificação de limitações, inconsistências e lacunas.
- **Distinção entre evidência e inferência:** preocupação em não apresentar interpretações como fatos diretamente comprovados pelas fontes.
- **Organização:** solicitação de estruturas que facilitassem a análise e posterior documentação.
- **Reutilização:** desenvolvimento de instruções que possam ser adaptadas a outros contextos de aprendizagem.

A engenharia de prompts foi tratada como um processo iterativo: os mesmos critérios acima guiaram tanto a criação quanto o refinamento. Quando uma resposta não atendia adequadamente ao objetivo da investigação, o prompt era reformulado, com atenção adicional a dois aspectos específicos do refinamento:

1. **formato esperado da resposta** — se a estrutura solicitada facilitava ou dificultava a análise posterior;
2. **tipo de análise solicitada** — se a instrução pedia exploração, comparação, avaliação crítica ou síntese de forma inequívoca.

Esse processo permitiu observar que alterações na formulação das instruções podem modificar a forma como a IA organiza e apresenta as informações.

---

## 7. Organização dos arquivos

A pasta está organizada da seguinte maneira:

```text
prompts/
├── README.md
├── prompt-01-exploracao-conceituacao.md
├── prompt-02-aprofundamento.md
├── prompt-03-comparacao-fontes.md
├── prompt-04-analise-critica.md
└── prompt-05-sintese.md
```

Cada arquivo registra uma etapa específica da engenharia de prompts utilizada durante a investigação.

---

## 8. Relação com o restante do projeto

Os prompts documentados nesta pasta estão diretamente relacionados às respostas apresentadas na seção 7 (Respostas) do [README principal](../README.md).

A sequência geral do processo foi:

**Fontes → Perguntas estratégicas → Prompts → Respostas**

As evidências correspondentes às interações realizadas no NotebookLM são organizadas na pasta [`evidencias/`](../evidencias/).

---

## 9. Consideração final

A documentação dos prompts permite acompanhar não apenas o conteúdo das perguntas realizadas à IA, mas também a estratégia utilizada para conduzir a investigação.

O processo evidencia a utilização da engenharia de prompts como uma ferramenta de aprendizagem, permitindo **explorar, aprofundar, comparar, questionar, analisar e sintetizar informações** a partir das fontes selecionadas.

---

**CI&T – Do Prompt ao Agente** · **DIO — Treinando uma IA de Aprendizagem** · **NotebookLM**  
**Autora:** Nágyla Silva  

**Projeto:** *Treinando uma IA de Aprendizagem: Gestão Financeira Pessoal com NotebookLM*  

*Projeto integrante do portfólio prático de estudos em Inteligência Artificial, desenvolvido com foco em Educação Financeira, Engenharia de Prompts, Aprendizagem Ativa, curadoria de fontes, avaliação crítica de respostas de IA e organização do conhecimento, contribuindo para o desenvolvimento de competências para AI Trainer, AI Response Evaluator e Data Annotator.*