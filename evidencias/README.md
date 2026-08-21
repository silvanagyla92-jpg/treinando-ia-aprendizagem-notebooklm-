# Evidências do projeto

Esta pasta reúne os registros que documentam o **processo de aprendizagem realizado com o NotebookLM** no projeto **Gestão Financeira Pessoal**.

O objetivo é organizar o que está efetivamente preservado no repositório e permitir compreender o percurso do projeto: **fontes → perguntas → prompts → interações → análise → verificação → síntese → resultados**.

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
| `notebooklm/respostas/` | README de documentação; as duas respostas selecionadas estão em `resultados/` | Documenta a relação entre perguntas, prompts e respostas. |
| `notebooklm/relatorios/` | README de documentação | Registra a finalidade dos relatórios e uma inconsistência de contagem observada. |
| `notebooklm/imagens/` | **Imagens de evidência disponíveis** | Preserva registros visuais do processo no NotebookLM. |

Essa distinção é importante: **a existência de uma subpasta não significa que existam arquivos de evidência originais dentro dela**.

## Relação entre evidência e resultado

As duas respostas selecionadas para o projeto estão documentadas em [`../resultados/`](../resultados/), e não como arquivos duplicados em `evidencias/notebooklm/respostas/`.

Assim:

- `evidencias/` documenta o **processo e os registros preservados**;
- `resultados/` reúne os **resultados textuais selecionados**;
- `analises/` reúne a **avaliação crítica** desses materiais.

## Processo documentado

```text
25 fontes
    ↓
perguntas estratégicas
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
resultados
```

## 25 fontes

O inventário oficial do projeto contém **25 fontes**:

- **7** acadêmicas;
- **15** artigos e portais;
- **1** institucional;
- **2** internas.

**Total: 25 fontes.**

A relação completa está em [`../fontes/`](../fontes/).

### Observação sobre a contagem

Um relatório citado no material do projeto apresenta **26 fontes**, enquanto o inventário final organizado no repositório contém **25**. A diferença é mantida documentada como uma inconsistência histórica do processo e não é tratada como uma 26ª fonte sem confirmação independente.

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
4. **Resultado** — síntese selecionada e organizada para o projeto.

## Critérios de documentação

As evidências devem ser reais, identificáveis e relacionadas ao processo realizado.

Não devem ser criadas capturas, respostas ou relatórios fictícios apenas para preencher a estrutura.

Quando determinado registro original não estiver disponível no repositório, essa ausência deve ser indicada claramente.

## Limitações

A pasta `evidencias/` não contém uma transcrição integral de todas as interações realizadas no NotebookLM. Ela preserva apenas os registros que foram efetivamente incorporados ao repositório.

A ausência de um arquivo não prova que uma etapa não ocorreu; significa apenas que ela **não está preservada como arquivo nesta versão do repositório**.

## Navegação

- [`../fontes/`](../fontes/) — fontes utilizadas.
- [`../prompts/`](../prompts/) — prompts documentados.
- [`../analises/`](../analises/) — análises produzidas.
- [`../resultados/`](../resultados/) — resultados selecionados.

---

**CI&T – Do Prompt ao Agente** · **DIO — Treinando uma IA de Aprendizagem**  
**Projeto:** *Gestão Financeira Pessoal com NotebookLM*  
**Autora:** Nágyla Silva