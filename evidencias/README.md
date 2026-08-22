# Evidências do projeto

Esta pasta reúne os registros que documentam o **processo de aprendizagem realizado com o NotebookLM** no projeto **Gestão Financeira Pessoal**.

O objetivo é organizar o que está efetivamente preservado no repositório e permitir compreender o percurso do projeto: **fontes → perguntas → prompts → interações → análise → verificação → síntese**.

## Estrutura atual

```text
evidencias/
├── README.md
└── notebooklm/
    ├── fontes/
    ├── imagens/
    ├── perguntas/
    ├── prompts/
    ├── relatorios/
    └── respostas/
```

As subpastas são mantidas porque representam diferentes tipos de registro do processo. Elas não são duplicações das pastas principais do projeto.

## Conteúdo efetivamente disponível

| Subpasta | Situação atual | Função |
|---|---|---|
| `notebooklm/fontes/` | README de documentação | Explica o registro das fontes utilizadas no caderno. |
| `notebooklm/perguntas/` | README de documentação | Explica as perguntas estratégicas utilizadas. |
| `notebooklm/prompts/` | README de documentação | Explica o registro dos prompts utilizados. |
| `notebooklm/respostas/` | README de documentação | Documenta a relação entre perguntas, prompts e respostas. |
| `notebooklm/relatorios/` | README de documentação | Registra a finalidade dos relatórios preservados. |
| `notebooklm/imagens/` | **Imagens de evidência disponíveis** | Preserva registros visuais do processo no NotebookLM. |

Essa distinção é importante: **a existência de uma subpasta não significa que existam arquivos de evidência originais dentro dela**.

## Relação entre evidência e análise

As duas respostas selecionadas e seus documentos analíticos consolidados estão em [`../analises/`](../analises/).

Assim:

- `evidencias/` documenta o **processo e os registros preservados**;
- `analises/` reúne as **respostas selecionadas, avaliações, verificações e sínteses**;
- `glossario/` organiza conceitos para consulta rápida.

A antiga pasta `resultados/` foi removida após a consolidação do conteúdo em `analises/`. Não existem resultados textuais dependentes de uma pasta separada.

## Processo documentado

```text
25 fontes
    ↓
5 perguntas estratégicas
    ↓
5 prompts
    ↓
interações no NotebookLM
    ↓
registros preservados
    ↓
comparação e análise
    ↓
verificação
    ↓
síntese
    ↓
analises consolidadas
```

## Inventário de fontes documentadas

O inventário oficial do projeto contém **25 fontes**, organizadas nas seguintes categorias:

- **7** fontes acadêmicas;
- **15** fontes de artigos e portais;
- **1** fonte institucional;
- **2** fontes internas.

**Total: 25 fontes.**

A relação completa das fontes, com sua organização e identificação, está disponível em [`../fontes/`](../fontes).

Esta seção apresenta apenas a composição do inventário. A existência de uma fonte no inventário não significa, isoladamente, que ela tenha sido utilizada em cada pergunta, prompt ou análise. A relação entre perguntas e fontes está documentada em [`../catalogacao/`](../catalogacao).

## O que as evidências demonstram

Os registros disponíveis ajudam a documentar:

- curadoria e organização das fontes;
- interação com o NotebookLM;
- uso de perguntas estratégicas;
- utilização de prompts;
- registros visuais do processo;
- organização das etapas de análise e síntese.

## Evidência não significa validação automática

Uma captura de tela, uma resposta ou um relatório comprova que determinado material fez parte do processo, mas **não comprova automaticamente a correção de seu conteúdo**.

Por isso, o projeto separa quatro funções:

1. **Fonte** — de onde a informação é obtida.
2. **Evidência** — registro de como o processo ocorreu.
3. **Análise** — avaliação crítica do material.
4. **Síntese** — consolidação organizada dos resultados analisados.

## Critérios de documentação

As evidências devem ser reais, identificáveis e relacionadas ao processo realizado.

Não devem ser criadas capturas, respostas ou relatórios fictícios apenas para preencher a estrutura.

Quando determinado registro original não estiver disponível no repositório, essa ausência deve ser indicada claramente.

## Limitações

A pasta `evidencias/` não contém uma transcrição integral de todas as interações realizadas no NotebookLM. Ela preserva apenas os registros que foram efetivamente incorporados ao repositório.

A ausência de um arquivo não prova que uma etapa não ocorreu; significa apenas que ela **não está preservada como arquivo nesta versão do repositório**.

## Navegação

- [`../fontes/`](../fontes/) — fontes utilizadas.
- [`../catalogacao/`](../catalogacao/) — relação entre perguntas e fontes.
- [`../prompts/`](../prompts/) — prompts documentados.
- [`../analises/`](../analises/) — respostas, análises, verificações e sínteses.
- [`../glossario/`](../glossario/) — conceitos utilizados no projeto.

---

**Projeto:** Gestão Financeira Pessoal com NotebookLM

**Autora:** Nágyla Silva

Projeto integrante do portfólio prático em Inteligência Artificial, desenvolvido para demonstrar competências em treinamento e avaliação de sistemas de IA, análise crítica de respostas e anotação de dados, aplicadas às funções de AI Trainer, AI Response Evaluator e Data Annotator, com base em experiência em QA e Auditoria.
