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

## 2. Sequência de investigação

Os prompts foram organizados em uma sequência progressiva, acompanhando o desenvolvimento da investigação no NotebookLM:

**exploração e conceituação → aprofundamento → comparação → análise crítica → síntese**

Essa organização permite passar de uma compreensão inicial dos conceitos para etapas de maior aprofundamento e integração das informações.

---

## 3. Prompts desenvolvidos

### 3.1 Prompt 01 — Exploração e conceituação

Arquivo:

`prompt-01-exploracao-conceituacao.md`

Objetivo: iniciar a investigação e identificar conceitos relacionados ao comportamento financeiro, à tomada de decisão econômica e à influência de fatores psicológicos e cognitivos.

A etapa busca estabelecer uma base conceitual antes do aprofundamento dos temas.

---

### 3.2 Prompt 02 — Aprofundamento

Arquivo:

`prompt-02-aprofundamento.md`

Objetivo: aprofundar os conceitos identificados na etapa inicial, explorando suas características, relações e possíveis aplicações no contexto da Gestão Financeira Pessoal.

---

### 3.3 Prompt 03 — Comparação entre fontes

Arquivo:

`prompt-03-comparacao-fontes.md`

Objetivo: comparar informações provenientes de diferentes fontes, identificando convergências, diferenças e possíveis complementaridades entre as perspectivas apresentadas.

---

### 3.4 Prompt 04 — Análise crítica

Arquivo:

`prompt-04-analise-critica.md`

Objetivo: analisar criticamente as informações e respostas produzidas durante a investigação, verificando sua fundamentação nas fontes, coerência, limitações, ambiguidades e necessidade de confirmação adicional.

---

### 3.5 Prompt 05 — Síntese

Arquivo:

`prompt-05-sintese.md`

Objetivo: consolidar os conhecimentos explorados nas etapas anteriores, relacionando conceitos, evidências e perspectivas em uma estrutura organizada de aprendizagem.

---

## 4. Critérios utilizados na elaboração

Durante a elaboração e o refinamento dos prompts, foram considerados diferentes aspectos para melhorar a qualidade da investigação.

Entre eles:

- **Clareza:** instruções apresentadas de forma objetiva e compreensível.
- **Contextualização:** definição do tema e do objetivo da investigação.
- **Especificidade:** indicação do tipo de análise ou informação desejada.
- **Fundamentação:** orientação para considerar as fontes disponíveis no NotebookLM.
- **Pensamento crítico:** incentivo à identificação de limitações, inconsistências e lacunas.
- **Distinção entre evidência e inferência:** preocupação em não apresentar interpretações como fatos diretamente comprovados pelas fontes.
- **Organização:** solicitação de estruturas que facilitassem a análise e posterior documentação.
- **Reutilização:** desenvolvimento de instruções que possam ser adaptadas a outros contextos de aprendizagem.

---

## 5. Refinamento dos prompts

A engenharia de prompts foi tratada como um processo iterativo.

Quando uma resposta não atendia adequadamente ao objetivo da investigação, o prompt podia ser reformulado considerando aspectos como:

1. clareza da instrução;
2. nível de especificidade;
3. contexto fornecido;
4. tipo de análise solicitada;
5. formato esperado da resposta;
6. necessidade de fundamentação nas fontes;
7. distinção entre fato, interpretação e inferência.

Esse processo permitiu observar que alterações na formulação das instruções podem modificar a forma como a IA organiza e apresenta as informações.

---

## 6. Relação entre conhecimento financeiro e comportamento

Uma das questões investigadas durante o projeto foi a relação entre conhecimento financeiro e comportamento financeiro.

A relação pode ser compreendida de forma bidirecional:

- **Conhecimento financeiro → comportamento:** compreender conceitos como orçamento, juros, inflação, risco e planejamento pode ajudar a pessoa a avaliar alternativas e tomar decisões mais informadas.
- **Comportamento → aplicação do conhecimento:** fatores como hábitos, emoções, vieses cognitivos, autocontrole e contexto podem determinar se o conhecimento adquirido será efetivamente aplicado.
- **Síntese:** existe uma diferença entre **saber o que fazer** e **conseguir transformar esse conhecimento em comportamento**. Uma pessoa pode conhecer princípios financeiros e, ainda assim, tomar decisões influenciadas pelo presente, pela aversão à perda, pelo excesso de confiança ou por outros fatores comportamentais.

No contexto deste projeto, essa relação é relevante porque demonstra que a educação financeira não deve ser analisada apenas como aquisição de conhecimento. A aplicação prática desse conhecimento também pode depender de fatores psicológicos, comportamentais e contextuais.

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

## 8. Relação com as respostas

Os prompts estão diretamente relacionados às respostas documentadas na pasta `respostas/`.

A sequência geral do processo foi:

**Fontes → Perguntas → Prompts → Respostas → Análise → Síntese**

As evidências correspondentes às interações realizadas no NotebookLM são organizadas na pasta `evidencias/`.

---

## 9. Consideração final

A documentação dos prompts permite acompanhar não apenas o conteúdo das perguntas realizadas à IA, mas também a estratégia utilizada para conduzir a investigação.

O processo evidencia a utilização da engenharia de prompts como uma ferramenta de aprendizagem, permitindo **explorar, aprofundar, comparar, questionar, analisar e sintetizar informações** a partir das fontes selecionadas.

---

**CI&T – Do Prompt ao Agente** · **DIO — Treinando uma IA de Aprendizagem** · **NotebookLM**  
**Autora:** Nágyla Silva

*Projeto integrante do portfólio prático de estudos em Inteligência Artificial, com foco em Educação Financeira, Engenharia de Prompts, Aprendizagem Ativa, avaliação crítica de respostas de IA e desenvolvimento de competências para AI Trainer, AI Response Evaluator e Data Annotator.*
