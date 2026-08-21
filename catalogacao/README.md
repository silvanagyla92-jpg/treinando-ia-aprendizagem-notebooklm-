# Catalogação

Esta pasta reúne a documentação utilizada para organizar e relacionar as perguntas estratégicas do projeto com as fontes que compõem o inventário documental de 25 fontes.

A catalogação foi criada para melhorar a rastreabilidade do processo realizado com o NotebookLM, permitindo relacionar os principais elementos da investigação:

```text
Fontes
   |
   v
Perguntas estratégicas
   |
   v
Prompts
   |
   v
Análises
   |
   v
Síntese do conhecimento
```

## 1. Objetivo da catalogação

O objetivo desta pasta é registrar de forma organizada:

- quais perguntas orientaram a investigação;
- quais fontes apresentam maior relação temática com cada pergunta;
- quais documentos do projeto estão relacionados a cada etapa;
- como as fontes estão distribuídas no inventário oficial;
- quais informações possuem evidência documental e quais ainda dependem de confirmação.

A catalogação funciona como uma camada de organização entre o inventário de fontes e os documentos produzidos durante a investigação.

## 2. Inventário de fontes

O projeto possui **25 fontes catalogadas**, distribuídas nas seguintes categorias:

| Categoria | Quantidade |
|---|---:|
| Acadêmicas | 7 |
| Artigos e portais | 15 |
| Institucionais | 1 |
| Internas | 2 |
| **Total** | **25** |

O inventário completo pode ser consultado em [`fontes/`](../fontes/).

As fontes internas correspondem a documentos produzidos durante o próprio desenvolvimento do projeto e não devem ser confundidas com publicações externas.

## 3. Perguntas estratégicas

A investigação foi organizada em **5 perguntas estratégicas**, relacionadas aos cinco prompts documentados no projeto.

As perguntas representam diferentes etapas da investigação:

1. análise de vieses e decisões econômicas;
2. investigação do Viés do Presente;
3. comparação entre fontes sobre educação financeira;
4. verificação da fundamentação das informações produzidas pela IA;
5. integração entre conhecimento financeiro e comportamento.

A documentação detalhada das perguntas e sua correlação temática com as fontes está em [`perguntas-estrategicas-fontes.md`](./perguntas-estrategicas-fontes.md).

## 4. Como a correlação é realizada

A relação entre uma pergunta e uma fonte é estabelecida considerando principalmente:

- tema abordado pela fonte;
- conceitos relacionados à pergunta;
- objetivo da investigação;
- conteúdo efetivamente analisado;
- relação da fonte com os demais documentos do projeto.

A correlação é apresentada como uma relação **temática e analítica**.

Isso significa que uma fonte pode apresentar relação com mais de uma pergunta e que uma pergunta pode estar relacionada a várias fontes.

Exemplo:

```text
Pergunta 03
    |
    +-- financial-literacy-lusardi.md
    +-- financial-literacy-oup.md
    +-- economic-importance-financial-literacy.md
    +-- financial-literacy-economic-outcomes.md
```

Essa estrutura permite visualizar quais documentos apresentam maior aderência ao eixo investigado.

## 5. Correlação não significa comprovação histórica

É importante diferenciar dois conceitos.

**Correlação temática**

Indica que determinado conteúdo apresenta relação direta com o assunto ou objetivo de uma pergunta.

**Evidência de utilização no NotebookLM**

Indica que existe documentação suficiente para afirmar que determinada fonte foi efetivamente carregada ou utilizada no caderno.

Uma correlação temática, isoladamente, **não comprova que uma fonte específica foi uma das cinco fontes originalmente carregadas no NotebookLM**.

Por esse motivo, esta pasta não utiliza frequência de citações ou semelhança temática como substituto de evidência documental.

## 6. Relação com outras pastas

A catalogação funciona em conjunto com outras áreas do repositório:

```text
fontes/
   |
   | inventário documental
   v
catalogacao/
   |
   | relação entre perguntas e fontes
   v
prompts/
   |
   | instruções utilizadas na IA
   v
evidencias/
   |
   | registros do processo
   v
analises/
   |
   | interpretação e verificação
   v
glossario/
   |
   | organização dos principais conceitos
```

Essa organização separa os diferentes níveis de documentação e evita misturar fonte, pergunta, prompt, evidência e análise.

## 7. Documento desta pasta

Atualmente, a pasta contém:

- [`perguntas-estrategicas-fontes.md`](./perguntas-estrategicas-fontes.md) - reúne as cinco perguntas estratégicas e registra a correlação temática de cada uma com as fontes do inventário.

## 8. Importância para o projeto

A catalogação contribui para a qualidade documental do projeto porque permite verificar a relação entre:

**fonte -> pergunta -> prompt -> análise**

Essa relação facilita:

- auditoria do processo;
- localização das informações;
- identificação de lacunas;
- verificação das relações entre documentos;
- manutenção do repositório;
- compreensão do projeto por terceiros.

Em um contexto profissional, essa organização demonstra capacidade de estruturar informações, estabelecer critérios de rastreabilidade e documentar processos envolvendo Inteligência Artificial.

## 9. Limites da documentação

A catalogação não deve criar informações que não estejam comprovadas nos documentos do projeto.

Quando uma relação entre fonte e pergunta for apenas temática, ela deve ser apresentada como correlação.

Quando houver evidência documental direta, essa evidência deve ser identificada separadamente.

Essa distinção evita transformar uma inferência em fato e preserva a confiabilidade da documentação.

---

**Projeto:** Gestão Financeira Pessoal com NotebookLM  
**Autora:** Nágyla Silva

*Projeto integrante do portfólio prático de estudos em Inteligência Artificial, com foco em engenharia de prompts, avaliação crítica de respostas de IA e desenvolvimento de competências para AI Trainer, AI Response Evaluator e Data Annotator.*
