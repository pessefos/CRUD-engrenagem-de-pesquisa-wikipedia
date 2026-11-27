# 📓 LOGBOOK AFP — Algoritmos e Programação (2026.2)

> **Como usar este arquivo:** copie-o para a raiz do **seu** repositório (ou para `logbook/LOGBOOK.md`) e preencha **direto no GitHub** (botão ✏️ *Edit this file*) ou no VS Code. Ele reúne todos os instrumentos do Protocolo AFP 2026.2 (Logbook Individual — Campos 01 a 04, 06 e 07; Registro de Revisão por Pares — Campo 05; Checkpoint Conceitual; Rubrica de Defesa Técnica).
>
> **Organização:** o Logbook está dividido em **3 grupos de entrega**, cada um com seu prazo. Dentro de cada grupo, os **ciclos de entrega (01 a 12)** continuam os mesmos, com as orientações de preenchimento. Siga a ordem: **Grupo 1 → Grupo 2 → Grupo 3 → Defesa Técnica**.
>
> O `Diario.md` do checklist passa a ser **este arquivo**: o registro de cada ciclo está na seção do ciclo correspondente.

## 📍 Navegação rápida

| Seção | Prazo |
|---|---|
| [👨‍🎓 Identificação](#-identificação) | Hoje |
| [🟢 Grupo 1](#-grupo-1--prazo-segunda-1611-às-23h59) · Registros 01–04, Campos 01 e 02 | **Segunda 16/11, 23h59** |
| [🟠 Grupo 2](#-grupo-2--prazo-sábado-2111-às-23h59) · Registros 05–08, Checkpoint, Campos 03 e 04 | **Sábado 21/11, 23h59** |
| [🔵 Grupo 3](#-grupo-3--prazo-quinta-2611-às-23h59) · Registros 09–12, Campos 05, 06 e 07 | **Quinta 26/11, 23h59** |
| [🏁 Defesa Técnica](#-defesa-técnica--quarta-1811) | **Quarta 18/11** |
| [🆘 Estou atrasado](#-estou-atrasado-no-logbook-e-agora) | — |

---

## 👨‍🎓 Identificação

| Campo | Preencha |
|---|---|
| **Nome do estudante** | _Caio Rafael Tavares da Silva_ |
| **Curso / Módulo** | _Engenharia de Software, 2º periodo_ |
| **Unidade curricular** | Algoritmos e Programação — UnDB 2026.2 |
| **Professor** | Rondineli Seba Salomão |
| **App-base do meu CRUD** | _ex.:Engrenagem de Pesquisa da Wikipedia_ |
| **Link do meu repositório** | _[https://github.com/](https://github.com/pessefos/CRUD-engrenagem-de-pesquisa-wikipedia)…_ |
| **Dupla de revisão (Campo 05)** | _Joás Franco_ |
| **Função neste ciclo** | _Caio Rafael · Joás Franco_ |

---

## 🧭 Regras de ouro (leia antes de preencher)

1. **Processo, não resultado.** O Logbook mostra *como você pensou*, não só o que funcionou. Registre erros, desvios e dúvidas reais.
2. **Vocabulário técnico.** Use os termos da área (ex.: "laço de repetição", "validação de entrada", "estrutura de dados"). Respostas genéricas ("aprendi Python") não são aceitas.
3. **Todo registro relevante tem 3 âncoras:** o **objeto de conhecimento** mobilizado + a **justificativa técnica** + a **referência/fonte**. *Decisão sem objeto de conhecimento e sem referência é considerada não rastreável e não conta para a avaliação formativa.*
4. **Coerência entre campos.** O Campo 02 deve ser coerente com o Campo 01. *Incoerência é evidência de autoria externa.* O Campo 07 retoma o Campo 01.
5. **IA é permitida e avaliada (Campo 04).** *Print sem análise crítica = devolução imediata. Reproduzir a IA sem questionamento = reprovado.* Você precisa mostrar o que aceitou **e** o que questionou/descartou, com argumento técnico.
6. **O histórico do Git é a sua evidência.** Faça commits pequenos e frequentes. Nunca reescreva o histórico (`force push`) do arquivo do Logbook.
7. **Campo 01 e Checkpoint são "sem consulta".** Preencha em um bloco contínuo, sem internet, sem material e sem colegas, no tempo indicado (Campo 01: durante o laboratório; Checkpoint: 20 min). Depois **não edite** esses campos — se perceber um erro, corrija em um campo posterior (Campo 03 ou 07), explicando.
8. **Os prazos dos grupos (16/11, 21/11 e 26/11, às 23h59)** valem para o commit no GitHub. O horário do commit é o registro oficial.

### ✅ Padrão de commit do Logbook

```text
docs(logbook): campo 01 — ciclo 02
docs(logbook): registro do ciclo 05
docs(logbook): campo 05 — revisão do CRUD de <colega>
```

---

## 🗓️ Calendário de entregas e Defesa

Os grupos têm **5 dias entre um prazo e outro**. O horário do commit no GitHub é o registro oficial.

| Grupo | Janela de preenchimento | **Prazo** | O que entregar |
|:--:|---|---|---|
| **1** | Qua 11/11 → seg 16/11 | **Segunda 16/11, 23h59** | Identificação · Registros dos Ciclos 01 a 04 · Campo 01 · Campo 02 |
| **2** | Seg 16/11 → sáb 21/11 | **Sábado 21/11, 23h59** | Registros dos Ciclos 05 a 08 · Checkpoint Conceitual · Campo 03 · Campo 04 |
| **3** | Sáb 21/11 → qui 26/11 | **Quinta 26/11, 23h59** | Registros dos Ciclos 09 a 12 · Campo 05 (2 revisões) · Campo 06 · Campo 07 |
| 🏁 | — | **Quarta 18/11** | **Defesa Técnica individual** (Rubrica) |

### Linha do tempo

| Data | Evento |
|---|---|
| Qua 11/11 | **Hoje:** começa o Grupo 1 |
| Seg 16/11 | ✅ Prazo do **Grupo 1** |
| **Qua 18/11** | 🏁 **Defesa Técnica** |
| Sáb 21/11 | ✅ Prazo do **Grupo 2** |
| Qua 25/11 | Avaliação P2 |
| Qui 26/11 | ✅ Prazo do **Grupo 3** |
| Qua 02/12 | Avaliação Substitutiva |
| Qua 09/12 | Avaliação Final |

> ⚠️ **Atenção:** a Defesa Técnica (18/11) acontece **antes** dos prazos dos Grupos 2 e 3. Na defesa você será arguido sobre **o que já estiver registrado e commitado**. Veja a seção [Defesa Técnica](#-defesa-técnica--quarta-1811) para saber o que priorizar até 18/11.

### Ciclos de entrega por grupo

| Ciclo | Data da aula | Tema do ciclo | Grupo | O que preencher |
|:--:|:--:|---|:--:|---|
| 01 | 12/08 | Preparação do laboratório e escolha do projeto | **1** | Registro do Ciclo |
| 02 | 19/08 | Variáveis, tipos de dados, entrada/saída | **1** | Registro + **Campo 01** + **Campo 02** |
| 03 | 26/08 | Operadores, fluxogramas, paradigmas | **1** (registro) · **2** (campos) | Registro (G1) · **Checkpoint**, **Campo 03**, **Campo 04** (G2) |
| 04 | 02/09 | Condicionais: `if`, `elif`, `else` | **1** | Registro do Ciclo |
| 05 | 09/09 | Condicionais aninhadas e operadores lógicos | **2** | Registro do Ciclo |
| 06 | 30/09 | Repetição: `for`, `while`, `break`, `continue` | **2** | Registro do Ciclo (inclui devolutiva da P1) |
| 07 | 07/10 | Listas: armazenamento e iteração | **2** | Registro do Ciclo |
| 08 | 14/10 | Busca e introdução a dicionários/matrizes | **2** | Registro do Ciclo |
| 09 | 21/10 | Atualização e exclusão: CRUD completo | **3** | Registro + **Campo 05** (revisão nº 1) |
| 10 | 28/10 | Modularização: funções | **3** | Registro do Ciclo |
| 11 | 04/11 | Recursividade | **3** | Registro + **Campo 06** |
| 12 | 11/11 | Refatoração e qualidade de código | **3** | Registro + **Campo 05** (revisão nº 2) + **Campo 07** |

---

## 📊 Painel de acompanhamento

Atualize a cada commit (troque ⬜ por ✅).

| Grupo | Item | Prazo | Preenchido | Commit |
|:--:|---|---|:--:|:--:|
| 1 | Identificação | 16/11 | ✅ | ✅ |
| 1 | Registros dos Ciclos 01, 02, 03 e 04 | 16/11 | ✅ | ✅ |
| 1 | Campo 01 — Instrumento de entrada | 16/11 | ✅ | ✅ |
| 1 | Campo 02 — Aprofundamento | 16/11 | ✅ | ✅ |
| 2 | Registros dos Ciclos 05, 06, 07 e 08 | 21/11 | ✅ | ✅ |
| 2 | Checkpoint Conceitual | 21/11 | ✅ | ✅ |
| 2 | Campo 03 — Execução e desvios | 21/11 | ✅ | ✅ |
| 2 | Campo 04 — Interação com IA | 21/11 | ✅ | ✅ |
| 3 | Registros dos Ciclos 09, 10, 11 e 12 | 26/11 | ⬜ | ⬜ |
| 3 | Campo 05 — Revisão por pares nº 1 e nº 2 | 26/11 | ⬜ | ⬜ |
| 3 | Campo 06 — Próximos passos | 26/11 | ⬜ | ⬜ |
| 3 | Campo 07 — Evolução conceitual | 26/11 | ⬜ | ⬜ |
| 🏁 | Defesa Técnica | 18/11 | ✅ | — |

---

## ❓ A questão-problema da AFP

**Título:** *O sistema em produção: diagnosticando as falhas do CRUD que você mesmo construiu.*

> **Enunciado completo (Apêndice A):** _professor(a): cole aqui o enunciado e os anexos liberados conforme o cronograma._

A questão-problema é **a mesma durante todo o semestre**: ela se aplica ao **seu** CRUD, que cresce a cada ciclo. Os **dados com defeito** do seu app chegam em um **lote cumulativo único** e vão expondo problemas diferentes conforme sua estrutura evolui. Seu trabalho é diagnosticar, ajustar o CRUD para tratar cada falha e **registrar o raciocínio** neste Logbook.

---

# 🔁 REGISTRO DO CICLO — modelo (copie em cada ciclo)

Cada ciclo tem sua própria seção abaixo, já com o modelo. Se precisar de espaço extra, acrescente linhas.

```markdown
### Registro do Ciclo NN — DD/MM
1. **Desafio do ciclo (em 1 frase):**
2. **O que implementei (commits / arquivos / links):**
3. **Objeto(s) de conhecimento mobilizado(s) (vocabulário técnico):**
4. **Desvio ou erro encontrado + causa técnica:**
5. **Decisão de ajuste + fonte (livro, doc, vídeo, colega, IA):**
6. **Feedback recebido (professor/colega) e o que mudei por causa dele:**
7. **Próximo passo:**
```

**Como preencher bem:** escreva como se explicasse a um colega que não esteve na aula. O item 3 e o item 5 são os mais importantes: eles ligam o que você fez ao **conteúdo** e à **fonte**.

| ❌ Fraco | ✅ Forte |
|---|---|
| "Aprendi a usar `if`." | "Usei estrutura condicional aninhada para validar a idade antes de cadastrar. Meu erro foi comparar `str` com `int` (resultado de `input()`); corrigi com `int()` (Pense em Python, cap. 2)." |
| "Deu erro e consertei." | "O programa quebrou com `ZeroDivisionError` ao calcular a média de um item sem avaliações. Causa: divisão por `len(lista)` com lista vazia. Ajuste: testar `if len(lista) > 0`." |

---

# 🟢 GRUPO 1 — prazo segunda 16/11 às 23h59

> **Janela:** quarta 11/11 → segunda 16/11. **O que entregar:** Identificação · Registros dos Ciclos 01, 02, 03 e 04 · Campo 01 · Campo 02.
>
> **Sugestão de ordem:** (1) Identificação → (2) **Campo 01 primeiro, sem consulta** → (3) Registros dos Ciclos 01 a 04 → (4) Campo 02, com pesquisa.

**Checklist do Grupo 1**
- [ ✅] Identificação preenchida (app-base, link do repositório, dupla de revisão)
- [✅ ] Campo 01: 3 objetos de conhecimento, 3 lacunas, hipótese de até 5 linhas
- [✅ ] Registros dos Ciclos 01, 02, 03 e 04 com os 7 itens
- [✅ ] Campo 02: 2 referências com contribuição, hipótese revisada, 3 recursos
- [✅ ] Commits no GitHub e painel atualizado

## 🟢 CICLO 01 — 12/08 — Preparação do laboratório e escolha do projeto

<details>
<summary>📘 Orientações do Ciclo 01</summary>

- **Hoje não há Campo do Protocolo.** O foco é preparar o ambiente: criar o repositório, configurar o VS Code e escolher o **app-base** do seu CRUD (e, portanto, o *schema* dos seus dados).
- Preencha a **Identificação** (no início deste arquivo) e o **Registro do Ciclo 01**.
- No item 3, registre **o que você já sabia** e o que era novo (Git, GitHub, VS Code). Isso será útil para o Campo 07.
- No item 4, registre qualquer problema de instalação ou configuração e como o resolveu — isso conta como desvio.
- Faça o primeiro commit: `docs(logbook): registro do ciclo 01`.
</details>

#### Registro do Ciclo 01 — 12/08
1. **Desafio do ciclo (em 1 frase):**Preparação para o desenvolvimento do crud com Git, Github e VS Code, inspirado na engrenagem de pesquisa da wikipedia. Ultilizei extensões de Python para me auxiliar no projeto. _…_
2. **O que implementei (commits / arquivos / links):**Foi realizado a definição do projeto de um crud em Python inspirado na engrenagem de pesquisa da wikipedia.Também foi planejada a estrutura do repositório e a configuração do ambiente no Vscode.  _…_
3. **Objeto(s) de conhecimento mobilizado(s):**Possuía conhecimento limitado em python, com poucas familiaridade com lógica e programação. Com relação ao Git e Github, tinha ciência apenas de como criar repositórios, mas não dominava as suas outras funcionalidades, como commits e gerenciamento geral.  _…_
4. **Desvio ou erro encontrado + causa técnica:**Não foram encontradas dificuldades, tanto na instalação ou configuração do ambiente. _…_
5. **Decisão de ajuste + fonte:**Decidi organizar o Wikicrud em apenas uma branche, mas com o passar do tempo decidi criar atos, do 1 até o 3 para organizar e no final dar merge com a main. _…_
6. **Feedback recebido e o que mudei:**Até o momento não tive feedbacks, o projeto foi mantido.  _…_
7. **Próximo passo:**Começar a aplicar os conhecimento adquiridos, aprofundando a lógica de programação gradualmente.  _…_

## 🟢 CICLO 02 — 19/08 — Variáveis, tipos de dados e entrada/saída

### 🧩 CAMPO 01 — Instrumento de entrada
*Grupo 1 | Prazo segunda 16/11, 23h59 | SEM CONSULTA*
*(preenchimento tardio, registrado em 15/11, sem consulta a material, internet, IA ou colegas)*

**1a. Objetos de conhecimento identificados (mínimo 3, com vocabulário técnico):**
1. Variáveis e atribuição: armazenar título e texto do artigo durante a execução.
2. Tipos de dados primitivos (`str`, `int`) e entrada/saída com `input()` e `print()`.
3. Estruturas condicionais (`if`, `elif`, `else`) para decidir qual operação do menu executar.
4. Laço de repetição `while`, para manter o menu rodando até o usuário escolher sair.

**1b. Lacunas — o que não sei e preciso descobrir (mínimo 3, com precisão técnica):**
1. Não sei como armazenar vários artigos sem criar um par de variáveis para cada um.
2. Não sei se o valor digitado em `input()` vem como texto ou como número, nem quando preciso converter.
3. Não sei como impedir que o usuário cadastre título ou texto vazio, nem como tratar uma posição que não existe.
4. Não sei como procurar uma palavra dentro de um texto para montar a pesquisa.

**1c. Hipótese inicial em até 5 linhas — com lógica da área de formação:**

> Acredito que as falhas do CRUD virão de entradas inesperadas do usuário (campo vazio, posição inexistente) e do limite de espaço para guardar os artigos. Como ainda só conheço variáveis simples, penso que cada artigo precisará de variáveis próprias, o que vai deixar o código repetitivo. Espero que condicionais bem ordenadas resolvam a validação.

### 🧩 CAMPO 02 — Aprofundamento pós-aula
*AV Qualis — Grupo 1 | Segunda 16/11, 23h59*

**2a. Aprofundamento dos objetos de conhecimento (mínimo 2 referências com síntese da contribuição para a solução):**

- **Referência 1:** DOWNEY, Allen B. *Pense em Python* — cap. 2 (variáveis, expressões e instruções) e cap. 5 (condicionais). — **Contribuição:** Entendi que `input()` sempre devolve `str`, e por isso, no menu do Wikicrud, comparo a opção como texto (`op == "1"`) em vez de número. Também entendi que a cadeia `if/elif/else` avalia as condições em ordem e executa só o primeiro bloco verdadeiro, o que sustenta as 7 opções do menu sem que duas rodem ao mesmo tempo.
- **Referência 2:** Documentação oficial do Python 3 — *Built-in Functions* (`input`, `print`) e *Built-in Types* (operações com strings, operador `in`). — **Contribuição:** Confirmei que `busca in titulo1` testa se o texto digitado é uma *substring* do título, e que a comparação diferencia maiúsculas de minúsculas. Isso explica o comportamento da minha pesquisa e mostra uma limitação: buscar "python" não encontra "Python".

**2b. Hipótese revisada — o que mudou em relação ao Campo 01 e por quê:**

> A pesquisa respondeu duas lacunas do Campo 01. (1) `input()` devolve sempre texto, então qualquer comparação ou cálculo numérico exige conversão com `int()`. (2) O operador `in` resolve a busca por trecho de texto. Quanto à lacuna 1 do Campo 01 (armazenar vários artigos), confirmei na prática que guardar tudo em variáveis separadas (`titulo1`, `texto1`...) obriga a repetir o mesmo bloco `if/elif` cinco vezes em cada operação e limita o CRUD a 5 artigos. Minha hipótese se manteve (o problema virá da repetição e das entradas inválidas), e agora a vejo mais precisa. Espero que listas e laços, vistos nos próximos ciclos, eliminem essa duplicação.

**2c. Dimensionamento inicial de recursos (recurso, quantidade estimada, justificativa técnica — mínimo 3 itens):**

| RECURSO / MATERIAL / INSUMO | QUANTIDADE ESTIMADA | JUSTIFICATIVA TÉCNICA |
|---|---|---|
| Variáveis de armazenamento | 10 (5 pares título/texto) | Sem listas ainda, cada artigo ocupa duas variáveis. O valor `""` marca a posição como livre. |
| Ramificações do menu (`elif`) | 7 (6 operações + sair) | Cada operação do CRUD é um ramo da cadeia condicional dentro do laço `while`. |
| Casos de teste manuais | 17 (3 para criar, ler, pesquisar, editar e apagar; 2 para ver todos) | Cobrir caminho normal, entrada vazia e posição inexistente/fora de 1–5. |
| Horas de estudo | 6 h (conversão de tipos, condicionais, `while`) | Base para corrigir os desvios que aparecerem nos testes. |
| Arquivo do projeto | 1 arquivo Python (~190 linhas) | Concentra o CRUD enquanto não há funções (Ciclo 10). |
| Repositório GitHub | 1 repositório, 1 branch por ato | Os commits pequenos servem de evidência do processo. |

#### Registro do Ciclo 02 — 19/08
1. **Desafio do ciclo (em 1 frase):** Usar variáveis, tipos de dados e entrada/saída para construir o menu e as primeiras operações do Wikicrud.
2. **O que implementei (commits / arquivos / links):** Arquivo `ato1` na branch `act-1`: variáveis `titulo1..5` e `texto1..5`, menu com `print()`/`input()` e as operações criar, ler, pesquisar, editar, apagar e ver todos. Repositório: https://github.com/pessefos/CRUD-engrenagem-de-pesquisa-wikipedia
3. **Objeto(s) de conhecimento mobilizado(s):** Variáveis e atribuição, tipo `str`, `input()` e `print()`, comparação de strings (`==`, `!=`), operador `in` para busca em texto, contador inteiro (`achou`, `total`).
4. **Desvio ou erro encontrado + causa técnica:** `input()` devolve `str`, então a escolha do artigo (`n`) precisa ser comparada com `"1"`, não com `1`. Comparar `str` com `int` faz a condição ser sempre falsa. Além disso, a pesquisa com `in` diferencia maiúsculas de minúsculas.
5. **Decisão de ajuste + fonte:** Comparar as opções como texto (`op == "1"`) e validar campo vazio com `== ""` antes de gravar. Fonte: *Pense em Python*, cap. 2, e documentação do Python 3 (*Built-in Types*).
6. **Feedback recebido e o que mudei:** _(preencha só se houve feedback do professor ou de colega; caso contrário, escreva "Sem feedback externo neste ciclo; projeto mantido".)_
7. **Próximo passo:** Aprofundar as condicionais (Ciclo 04) para tratar melhor as entradas inválidas e, depois, trocar as variáveis soltas por listas.

#### Registro do Ciclo 02 — 19/08
1. **Desafio do ciclo (em 1 frase):** _…_
2. **O que implementei (commits / arquivos / links):** _…_
3. **Objeto(s) de conhecimento mobilizado(s):** _…_
4. **Desvio ou erro encontrado + causa técnica:** _…_
5. **Decisão de ajuste + fonte:** _…_
6. **Feedback recebido e o que mudei:** _…_
7. **Próximo passo:** _…_

#### Registro do Ciclo 03 — 26/08
1. **Desafio do ciclo (em 1 frase):** Aplicar operadores aritméticos, relacionais e lógicos do Python às regras do menu e da validação do Wikicrud, e entender o fluxo do programa como paradigma imperativo.
2. **O que implementei (commits / arquivos / links):** No `ato1` (branch `act-1`): `==` e `!=` no menu e na validação; `or` e `and` em criar, editar e pesquisar; operador `in` na pesquisa; `+` nos contadores `achou` e `total`. Repositório: https://github.com/pessefos/CRUD-engrenagem-de-pesquisa-wikipedia
3. **Objeto(s) de conhecimento mobilizado(s):** Operadores relacionais (`==`, `!=`) com `str`; operadores lógicos (`and`, `or`) e precedência entre eles; operador de pertinência `in` em strings; operador aritmético `+` em `achou = achou + 1`; tipos `str`, `int` (contadores) e `bool` (`rodando`). Paradigma imperativo/procedural: instruções em sequência que alteram o estado das variáveis, controladas por `while` e `if`. [Se montou um fluxograma do menu, acrescente o que ele mostrou; se não, remova esta frase.]
4. **Desvio ou erro encontrado + causa técnica:** Na pesquisa, `titulo1 != "" and (busca in titulo1 or busca in texto1)` depende dos parênteses. Sem eles, o Python lê `(titulo1 != "" and busca in titulo1) or busca in texto1`, porque `and` tem precedência sobre `or`. Testei: com uma posição vazia e busca vazia, o resultado é `False` com parênteses e `True` sem eles, e uma posição vazia entraria na lista.
5. **Decisão de ajuste + fonte:** Manter os parênteses explícitos nas cinco condições da pesquisa, para que posição vazia nunca seja listada. Fontes: *Pense em Python*, cap. 5 (operadores lógicos), e Python Language Reference, seção *Operator precedence*.
6. **Feedback recebido e o que mudei:** _(preencha só se houve; senão, "Sem feedback externo neste ciclo; projeto mantido".)_
7. **Próximo passo:** Estudar as condicionais `if/elif/else` e ligar cada uma a uma regra de negócio do Wikicrud (Ciclo 04).

#### Registro do Ciclo 04 — 02/09
1. **Desafio do ciclo (em 1 frase):** Ligar cada condicional do Wikicrud a uma regra de negócio e descobrir qual entrada quebra qual condição.
2. **O que implementei (commits / arquivos / links):** No `ato1`, as regras já implementadas por condicionais: RN1 título e texto não podem ser vazios (`titulo == "" or texto == ""`); RN2 limite de 5 artigos (cadeia de `elif` terminando em "acabou o espaco"); RN3 só ler, editar e apagar artigo existente (`n == "1" and titulo1 != ""`); RN4 opção de menu inválida cai no `else`; RN5 a pesquisa só considera posições ocupadas; RN6 mensagens "nao encontrei nada" e "nenhum artigo ainda" quando não há resultado.
3. **Objeto(s) de conhecimento mobilizado(s):** Estruturas `if/elif/else`; cadeia `elif`, em que só o primeiro bloco verdadeiro executa (usada no menu e em criar); `if` independentes (usados em pesquisar e ver todos, porque várias posições podem satisfazer a condição ao mesmo tempo); expressões booleanas; string vazia `""` como valor sentinela de posição livre; validação de entrada.
4. **Desvio ou erro encontrado + causa técnica:**
   - (a) **Busca vazia:** apertar Enter na pesquisa lista todos os artigos, pois `"" in qualquer_string` é `True` em Python.
   - (b) **Só espaços:** título ou texto `"   "` passa na validação e cria um artigo "invisível", pois `"   " == ""` é `False`.
   - (c) **Maiúsculas e minúsculas:** buscar "python" não encontra "Python", pois a comparação com `in` diferencia maiúsculas de minúsculas.
   - **Comparação com o Campo 02:** entrada vazia e posição inexistente já estavam previstas nos casos de teste; (a), (b) e (c) não estavam.
5. **Decisão de ajuste + fonte:** Registrar os três desvios e tratá-los no próximo ato: (a) acrescentar uma condicional que recusa `busca == ""`; (b) comparar o texto após remover espaços com `strip()`; (c) comparar em minúsculas com `lower()`. Fontes: *Pense em Python*, cap. 5 (condicionais) e cap. 8 (strings), e documentação do Python, métodos de `str`.
6. **Feedback recebido e o que mudei:** _(preencha só se houve; senão, "Sem feedback externo neste ciclo; projeto mantido".)_
7. **Próximo passo:** Corrigir (a), (b) e (c) no `ato2` e estudar laços de repetição (Ciclo 06) para reduzir a repetição dos blocos por posição.

---

# 🟠 GRUPO 2 — prazo sábado 21/11 às 23h59

> **Janela:** segunda 16/11 → sábado 21/11. **O que entregar:** Registros dos Ciclos 05, 06, 07 e 08 · Checkpoint Conceitual · Campo 03 · Campo 04.
>
> ⚠️ O prazo cai num **sábado**: planeje terminar na sexta. Os campos do Ciclo 03 (Checkpoint, 03 e 04) aparecem **primeiro**, porque são a base da investigação.

**Checklist do Grupo 2**
- [ ✅] Checkpoint Conceitual feito conforme orientação do professor (20 min, sem consulta)
- [✅ ] Campo 03: 2 achados com objeto, 1 desvio com causa técnica, 1 decisão com fonte
- [ ✅] Campo 04: ferramenta, pergunta íntegra, resumo, o que aceitei e o que questionei
- [ ✅] Registros dos Ciclos 05, 06, 07 e 08 com os 7 itens (devolutiva da P1 no ciclo 06)
- [ ✅] Commits no GitHub e painel atualizado

### 🧩 CAMPO 03 — Execução e desvios
*AV Qualis — Grupo 2 | Sábado 21/11, 23h59*

**3a. O que descobri que mudou minha compreensão do problema (mínimo 2 achados, com objeto de conhecimento associado):**

1. Em Python a string vazia está contida em qualquer string, então `"" in titulo1` é sempre `True`. Pesquisar apertando só Enter lista todos os artigos em vez de "nenhum resultado". — **Objeto de conhecimento:** operador de pertinência `in` e strings.
2. A repetição de cinco blocos por operação não é limite da sintaxe: vem de guardar os dados em variáveis separadas. Com listas e `for`, o mesmo comportamento cabe em 94 linhas, contra 187 do `ato1`, com saídas idênticas na mesma sequência de testes. — **Objeto de conhecimento:** listas e laço `for`/`range`.
3. *(opcional)* Sem parênteses, `and` é avaliado antes de `or`, o que deixaria uma posição vazia entrar nos resultados da pesquisa. — **Objeto de conhecimento:** precedência de operadores lógicos.

**3b. Desvio em relação ao Campo 02 (ao menos 1 — causa técnica):**

**Desvio:** O Campo 02 previu como entradas problemáticas o texto vazio e a posição inexistente (17 casos de teste). Busca vazia e título ou texto só com espaços não estavam previstos, e passaram pela validação.
**Causa técnica:** `== ""` só detecta string de comprimento zero, e `"   "` tem 3 caracteres. Já `"" in s` é `True` para qualquer `s`.

**3c. Decisão de ajuste (ao menos 1) com justificativa e fonte:**

**Decisão:** Recusar busca vazia com uma condicional e comparar título e texto após `strip()`, para restaurar as regras "não pode ficar vazio" e "pesquisar só o que foi digitado".
**Fonte:** Documentação do Python 3, *Built-in Types* (operações com sequências e métodos de `str`); *Pense em Python*, cap. 8.
**Objeto de conhecimento mobilizado nesta decisão:** strings (métodos) e condicionais.

### 🧩 CAMPO 04 — Interação com IA
*AV Qualis — Grupo 2 | Sábado 21/11, 23h59 | OBRIGATÓRIO*

**4a. Ferramenta:** Claude (Anthropic), chat web. **Data:** 21/11/2026 *(confirme a data real)*

**4b. Pergunta formulada (transcrita integralmente):**

4b. Pergunta formulada (transcrita integralmente): Como posso organizar o controle de criação, alteração e exclusão de anúncios em variáveis separadas (anuncio1, anuncio2, anuncio3) usando if/elif/else e while sem que uma entrada inválida ou exclusão cancelada grave ou apague dados por engano?

**4c. Resposta da IA (resumida em parágrafo):**

.A IA sugeriu usar uma variável de controle para identificar qual anúncio será manipulado e limpá-la quando ocorrer validação inválida ou cancelamento, deixando a gravação final condicional ao fato de essa variável continuar válida; também comentou sobre checar campos vazios e confirmar antes de apagar, além de apontar limitações de escalabilidade ao manter variáveis individuais em vez de uma estrutura composta.

**4d. O que aceitei — com referência ao objeto de conhecimento do componente:**

Aceitei a lógica de usar uma variável de controle (num) que só permanece preenchida quando as condições são atendidas e volta a "" quando há falha de validação (titulo == "" ou preco == ""), inexistência do anúncio ou cancelamento da exclusão (!= "s"), evitando alterações indevidas no bloco final. Isso se apoia nos objetos de conhecimento de variáveis, tipos primitivos (str, bool), operadores relacionais/lógicos (==, !=, and, or), estruturas condicionais (if/elif/else) e laços de repetição (while), reforçados nas aulas Curso Python #06 – Tipos Primitivos e Saída de Dados e Exercício Python #004 – Dissecando uma Variável (Gustavo Guanabara — Curso em Vídeo).

**4e. O que questionei ou descartei — com argumento técnico ou fonte:**
Questionei e descartei sugestões de alterar a estrutura de dados do programa para coleções/estruturas mais avançadas neste momento, pois o recorte do projeto na disciplina trabalhava com variáveis simples, if/elif/else e while, e a prioridade era dominar o fluxo condicional, a verificação de estado de cada variável (anuncio1, anuncio2, anuncio3) e o tipo/conteúdo das entradas obtidas com input() antes de avançar para outras estruturas. Argumento técnico e fonte: manter o escopo restrito aos objetos de conhecimento estudados evita introduzir recursos não trabalhados no código e permite validar com precisão o comportamento das expressões booleanas e do controle de fluxo no laço while, com base nas aulas de Gustavo Guanabara (Curso Python #06 e Exercício Python #004) e na prática de testar cada caminho condicional no código.


#### Registro do Ciclo 05 — 09/09
1. **Desafio do ciclo (em 1 frase):** Organizar as condicionais aninhadas do Wikicrud (menu → operação → validação) e combinar condições com `and` e `or` sem gerar erros de conversão ou de índice.
2. **O que implementei (commits / arquivos / links):** No `ato1`, a cadeia externa do menu e, dentro de cada operação, uma cadeia de validação (criar: vazio → posição livre → sem espaço; editar: vazio → existe; ler/apagar: existe). No `ato2` [link do commit], refatorei: a opção inválida é filtrada primeiro (`if op not in menu`), e a posição é validada com `n.isdecimal() and 1 <= int(n) <= len(artigos)` antes de qualquer acesso. Em editar, o pedido de novo título e texto agora fica **dentro** do `if` que confirma o artigo. Base: https://github.com/pessefos/CRUD-engrenagem-de-pesquisa-wikipedia/blob/act-1/ato1
3. **Objeto(s) de conhecimento mobilizado(s):** Condicionais aninhadas (um `if` dentro de outro), cadeia `elif` (só o primeiro bloco verdadeiro executa), `and` com curto-circuito (se `isdecimal()` é `False`, o `int(n)` nem é avaliado), comparação encadeada (`1 <= int(n) <= len(artigos)`), `or` na validação de campos vazios.
4. **Desvio ou erro encontrado + causa técnica:** No `ato1`, editar pedia novo título e novo texto **antes** de verificar se o artigo existia. Com posição inválida e campos vazios, a resposta era "nao pode ficar vazio" em vez de "artigo nao existe", e o usuário digitava dados que seriam descartados. Causa: a verificação de campo vazio vinha antes da de existência na cadeia, e os `input()` já tinham sido executados.
5. **Decisão de ajuste + fonte:** Aninhar o pedido dos novos dados dentro da condição que confirma o artigo. Usar `isdecimal()` antes de `int()`, pois o `and` em curto-circuito impede o `ValueError` com entradas como "abc". Fontes: *Pense em Python*, cap. 5 (condicionais encadeadas e aninhadas, operadores lógicos), e documentação do Python 3, *Boolean operations* (curto-circuito).
6. **Feedback recebido e o que mudei:** _(preencha só se houve; senão, "Sem feedback externo neste ciclo; projeto mantido".)_
7. **Próximo passo:** Estudar `for`, `while`, `break` e `continue` para eliminar a repetição de blocos.

#### Registro do Ciclo 06 — 30/09
1. **Desafio do ciclo (em 1 frase):** Usar `while` e `for` no Wikicrud para controlar o menu e eliminar a repetição de blocos, entendendo quando cada laço para.
2. **O que implementei (commits / arquivos / links):** No `ato1`, o menu roda em `while rodando`, flag que passa a `False` na opção "0". No `ato2` [link do commit]: o menu é impresso por `for chave, descricao in menu.items()`, e pesquisar e ver todos percorrem os artigos com `for i in range(len(artigos))`, substituindo os 5 blocos repetidos por um. Não usei `break` nem `continue`: estudei os dois e mantive a flag como única saída.
3. **Objeto(s) de conhecimento mobilizado(s):** `while` com condição booleana (flag `rodando`), `for` com `range()` e com `.items()`, `break` e `continue` (estudados), valor sentinela ("0") para sair do menu.
4. **Desvio ou erro encontrado + causa técnica:** Ao escolher "0", o programa faz `rodando = False` mas **não sai na hora**: o restante do corpo ainda é executado e a condição só é testada no início da próxima volta. Hoje é inofensivo, porque `elif op == "0"` é o último ramo, mas qualquer linha colocada depois da cadeia `if/elif` rodaria mesmo após o usuário sair. Causa: o `while` só reavalia sua condição ao fim de cada iteração, e não no momento em que a variável muda.
5. **Decisão de ajuste + fonte:** Manter `while rodando` com uma única saída clara, deixando o encerramento como último ramo da cadeia, e reservar `break` para saídas antecipadas dentro de laços internos. Usar `for` onde o número de passos é conhecido (`range(len(artigos))`) e `while` onde depende do usuário (o menu). Fontes: *Pense em Python*, cap. 7 (iteração), e tutorial do Python 3, *More Control Flow Tools* (`for`, `range`, `break` e `continue`).
6. **Feedback recebido (inclui devolutiva da P1) e o que mudei:** **Ainda não teve devolutiva da P1**
7. **Próximo passo:** Substituir as 10 variáveis do `ato1` por listas e iterar sobre elas (Ciclo 07).

#### Registro do Ciclo 07 — 07/10
1. **Desafio do ciclo (em 1 frase):** Trocar as 10 variáveis soltas do `ato1` (`titulo1..5`, `texto1..5`) por uma lista dinâmica de artigos e percorrê-la com `for`, sem gerar erros de índice.
2. **O que implementei (commits / arquivos / links):** Arquivo `ato2` [coloque o link do commit]: `artigos = []` guarda cada artigo como uma linha `[titulo, texto]` (lista de listas); criar usa `append()`, apagar usa `pop()`, e ver todos e pesquisar percorrem com `for i in range(len(artigos))`. Ler, editar e apagar acessam `artigos[int(n) - 1]` depois de validar a posição. O arquivo passou de 187 linhas (`ato1`) para 100. Base: https://github.com/pessefos/CRUD-engrenagem-de-pesquisa-wikipedia/blob/act-1/ato1
3. **Objeto(s) de conhecimento mobilizado(s):** Listas (`append`, `pop`, `len`, indexação), lista de listas (matriz), laço `for` com `range()`, diferença entre índice (começa em 0) e posição exibida (`i + 1`), conversão com `int()` e validação com `isdecimal()`.
4. **Desvio ou erro encontrado + causa técnica:** Ao calcular `artigos[int(n) - 1]` direto da entrada, três casos falham: (a) `"6"` gera `IndexError`, pois o índice passa do tamanho da lista; (b) `"abc"` gera `ValueError` em `int()`; (c) `"0"` não dá erro e devolve o **último** artigo, pois `int("0") - 1` vale `-1` e Python aceita índice negativo. Causa: o índice calculado a partir de texto digitado não era limitado ao intervalo da lista. Outro efeito: com `pop()`, apagar o artigo 2 faz o 3 virar 2, e no `ato1` a posição ficava vazia.
5. **Decisão de ajuste + fonte:** Validar `n.isdecimal() and 1 <= int(n) <= len(artigos)` antes de qualquer acesso, de modo que "0", "6" e "abc" caiam em "artigo nao existe". Aceitei a renumeração do `pop()` porque a lista dinâmica elimina o limite de 5 artigos. Fontes: *Pense em Python*, cap. 10 (listas), e tutorial do Python 3, seção *More on Lists*.
6. **Feedback recebido e o que mudei:** _(preencha só se houve; senão, "Sem feedback externo neste ciclo; projeto mantido".)_
7. **Próximo passo:** Estudar a consulta (busca) e dicionários no Ciclo 08, e usar essas estruturas na pesquisa e no menu.

#### Registro do Ciclo 08 — 14/10
1. **Desafio do ciclo (em 1 frase):** Melhorar a busca do Wikicrud e usar dicionários, `map` e matriz para organizar menu, consulta e resultados, mantendo o comportamento do CRUD.
2. **O que implementei (commits / arquivos / links):** No `ato2` [link do commit]: o menu virou o dicionário `menu = {"1": "criar artigo", ...}`, impresso com `for chave, descricao in menu.items()` e validado com `op not in menu`; a pesquisa percorre a matriz `artigos` e guarda os resultados no dicionário `achados` (posição → título); `map(str.lower, artigos[i])` põe título e texto em minúsculas para a busca ignorar a caixa; busca vazia é recusada e `strip()` remove espaços de título e texto.
3. **Objeto(s) de conhecimento mobilizado(s):** Busca sequencial em matriz; dicionário (chave → valor, `.items()`, `in` sobre chaves); função `map()` com `str.lower` e desempacotamento `a, b = map(...)`; `strip()` e `lower()` em strings.
4. **Desvio ou erro encontrado + causa técnica:** O dicionário `achados` guarda a **posição** como chave, e essa posição só vale enquanto a lista não muda: se o usuário pesquisa, vê "2 - Java", apaga o artigo 1 e depois lê o artigo 2, recebe outro artigo, pois `pop()` renumera a lista. Além disso, usar o **título** como chave do dicionário de artigos não funciona, porque chaves são únicas e o CRUD aceita títulos repetidos.
5. **Decisão de ajuste + fonte:** Manter a matriz `artigos` como armazenamento (título e texto juntos, sem dessincronia), usar dicionário só onde a chave é natural (opção do menu e resultado da busca) e tratar a posição do resultado como válida somente até a próxima alteração. Fontes: *Pense em Python*, caps. 10 e 11; tutorial do Python 3, *Data Structures* (*Dictionaries*, *Looping Techniques*); documentação do Python 3, função `map` em *Built-in Functions*.
6. **Feedback recebido e o que mudei:** _(preencha só se houve; senão, "Sem feedback externo neste ciclo; projeto mantido".)_
7. **Próximo passo:** A validação `n.isdecimal() and 1 <= int(n) <= len(artigos)` aparece três vezes (ler, editar, apagar); o estudo de funções (Ciclo 10) permite escrevê-la uma só vez.

# 🔵 GRUPO 3 — prazo quinta 26/11 às 23h59

> Cada seção abaixo substitui a seção de mesmo nome no `LOGBOOK_AFP_Algoritmos_Programacao_2026-2.md`.
> Código de referência: `ato1` (187 linhas, 10 variáveis) → `ato2` (100 linhas, matriz + dicionário + `map`) → `ato3` (135 linhas, funções + recursão).
> Links: https://github.com/pessefos/CRUD-engrenagem-de-pesquisa-wikipedia/blob/act-1/ato1 · `/ato2` · `/ato3`

> **Janela:** sábado 21/11 → quinta 26/11. **O que entregar:** Registros dos Ciclos 09, 10, 11 e 12 · Campo 05 (duas revisões por pares) · Campo 06 · Campo 07.
>
> ⚠️ O prazo vem **um dia depois da P2 (25/11)**. Os Campos 06 e 07 dependem de todo o Logbook: deixe-os para o final, mas **adiante o rascunho do 6c e do 7a/7b antes da Defesa (18/11)**.

**Checklist do Grupo 3**

*(marque cada item com ✅ só depois de resolver os `**[PREENCHA ...]**` correspondentes)*

- [ ✅] Registros dos Ciclos 09, 10, 11 e 12 com os 7 itens
- [✅ ] Campo 05: duas revisões (Ciclos 09 e 12), blocos 5a a 5e
- [ ✅] Campo 06: decisão autônoma, lacuna com plano, pergunta da banca com 5 linhas ou mais
- [ ✅] Campo 07: 7a a 7e, com 3 objetos, 2 equívocos corrigidos e transferência
- [✅ ] Coerência entre Campo 01 e Campo 07
- [✅ ] Painel de acompanhamento completo

**Painel de acompanhamento — linhas do Grupo 3** *(troque ⬜ por ✅ no painel do início do logbook)*

| Grupo | Item                                     | Prazo | Preenchido | Commit |
| ----- | ---------------------------------------- | ----- | ---------- | ------ |
| 3     | Registros dos Ciclos 09, 10, 11 e 12     | 26/11 | ✅          | ✅      |
| 3     | Campo 05 — Revisão por pares nº 1 e nº 2 | 26/11 | ✅          | ✅      |
| 3     | Campo 06 — Próximos passos               | 26/11 | ✅          | ✅      |
| 3     | Campo 07 — Evolução conceitual           | 26/11 | ✅          | ✅      |

---

## 🔵 CICLO 09 — 21/10 — Atualização e exclusão: CRUD completo

#### Registro do Ciclo 09 — 21/10
1. **Desafio do ciclo (em 1 frase):** Completar o CRUD do Wikicrud com atualização (editar) e exclusão (apagar) sem perder dados nem aceitar posições inexistentes.
2. **O que implementei (commits / arquivos / links):** No `ato1`, a opção 4 (editar) reatribui `tituloN, textoN = novo_titulo, novo_texto` e a opção 5 (apagar) devolve a posição ao valor `""`, ambas só depois de checar `n == "1" and titulo1 != ""`. No `ato2`, editar passou a `artigos[int(n) - 1] = [novo_titulo, novo_texto]` e apagar a `artigos.pop(int(n) - 1)`. Código: https://github.com/pessefos/CRUD-engrenagem-de-pesquisa-wikipedia/blob/act-1/ato1 e `/ato2`
3. **Objeto(s) de conhecimento mobilizado(s):** Operações CRUD (create, read, update, delete); atualização por reatribuição; exclusão lógica com valor sentinela (`""`); validação de existência antes de alterar; no `ato2`, índice de lista e `list.pop()`.
4. **Desvio ou erro encontrado + causa técnica:** No `ato1`, a exclusão lógica deixa "buracos": com 3 artigos, apagar o 2 e criar um novo faz o novo ocupar a posição 2, porque `criar` usa a primeira posição livre. A ordem de criação deixa de ser a ordem de listagem. Causa: o estado "livre" é só `titulo == ""`, e `criar` procura a primeira posição com esse valor.
5. **Decisão de ajuste + fonte:** Manter a exclusão lógica no `ato1`, que tem as posições 1 a 5 fixas, e migrar no `ato2` para remoção real com `pop()`, aceitando que as posições seguintes são renumeradas. Fontes: *Pense em Python*, cap. 10 (listas), e tutorial do Python 3, *More on Lists* (`list.pop`).
6. **Feedback recebido e o que mudei:** **[PREENCHA só se houve feedback real; senão: "Sem feedback externo neste ciclo; projeto mantido".]**
7. **Próximo passo:** Eliminar a validação de posição repetida (ler, editar, apagar) com funções (Ciclo 10).

### 🧩 CAMPO 05 — Registro de Revisão por Pares

#### Revisão nº 1
|                                   |                                                                                         |
| --------------------------------- | --------------------------------------------------------------------------------------- |
| **Autor do CRUD revisado**        | Joás Franco Rodrigues                                                                   |
| **Repositório revisado**          | https://github.com/joasfranco/Algoritmos-e-programacao *(conforme o logbook do autor)*  |
| **Revisor**                       | Caio Rafael Tavares da Silva                                                            |
| **Unidade curricular / Semestre** | Algoritmos e Programação · 2026.2                                                       |
| **Ciclo / data**                  | Ciclo 09 · revisão feita em 26/11                                                       |

**5a. AVANÇO DO PROCESSO DE REVISÃO — análise técnica de cada etapa:**

| ETAPA DO PROCESSO | RESPONSÁVEL | PRAZO | STATUS | DESVIO / JUSTIFICATIVA |
| --- | --- | --- | --- | --- |
| 1. Rodar o Anuncify com entradas válidas (cadastrar, listar, buscar) | Revisor | 26/11 | ☒ Concluída | — |
| 2. Testar entradas inválidas (vazio, negativo, texto, `nan`, `inf`, vírgula decimal) | Revisor | 26/11 | ☒ Concluída | — |
| 3. Ler o código e mapear as operações do CRUD | Revisor | 26/11 | ☒ Concluída | Menu tem 4 opções: Cadastrar, Listar, Buscar, Sair. |
| 4. Registrar achados com causa técnica | Revisor | 21/10 | ☒ Concluída | Ver 5e. |
| 5. Devolver o feedback ao Joás | Revisor / Autor | 27/11 | ☒ Em andamento | **[Envie o 5e ao Joás e troque o status para Concluída.]** |

**5b. ANÁLISE DE INSUMOS E CRITÉRIOS DE QUALIDADE:**

| RECURSO | QTDE PLANEJADA | QTDE UTILIZADA | VARIAÇÃO | JUSTIFICATIVA TÉCNICA |
| --- | --- | --- | --- | --- |
| Casos de teste manuais | 6 | 9 | +3 | Surgiram `nan`, `inf` e "1.500,50" durante a leitura do código. |
| Operações CRUD verificadas | 4 (C, R, U, D) | 2 (C, R), mais busca | −2 | Atualizar e excluir não existem no código revisado. |
| Arquivos lidos | 1 | 1 | 0 | Todo o Anuncify está em um único arquivo `.py`. |

**5c. CONTROLE DE QUALIDADE:**

- **Critério ou norma técnica:** CRUD completo (create, read, update, delete), conforme as orientações do Ciclo 09.
- **A solução atende?** ☒ Parcialmente (cadastrar, listar e buscar funcionam; **não há atualizar nem excluir**).

**5d. GESTÃO DE RISCOS:**

- **Risco:** O código revisado ser uma versão anterior à do repositório atual do Joás, e o feedback não se aplicar.
- **Estratégia de mitigação:** Conferir o commit no repositório dele antes de enviar o feedback e refazer os testes se o código tiver mudado.

**5e. RASTREABILIDADE DAS DECISÕES TÉCNICAS — COM VÍNCULO AO CONTEÚDO:**

| DATA | DECISÃO TÉCNICA | RESP. | OBJETO DE CONHECIMENTO MOBILIZADO | FUNDAMENTAÇÃO / REFERÊNCIA |
| --- | --- | --- | --- | --- |
| 26/11/26 | Apontar que o menu não tem editar nem excluir, e sugerir `lista[i] = novo` e `lista.pop(i)` com validação do índice | Revisor | CRUD; índice e `pop` em listas | *Pense em Python*, cap. 10; tutorial Python, *More on Lists* |
| 26/11/26 | Apontar que `float("nan")` e `float("inf")` passam em `preco < 0` e são cadastrados ("R$ nan"); sugerir `math.isfinite(preco)` | Revisor | Tipo `float`; validação de entrada | Docs Python, *Built-in Types* (`float`) e módulo `math` (`isfinite`) |
| 26/11/26 | Apontar que "1.500,50" vira "1.500.50" após o `replace` e é recusado como inválido; sugerir documentar o formato (ex.: 1500,50) | Revisor | Strings (`replace`) e conversão para `float` | Docs Python, *Built-in Types* (métodos de `str`) |
| 26/11/26 | Registrar como ponto forte o `try/except ValueError` seguido de `continue` na leitura do preço | Revisor | Tratamento de exceções; laço com `continue` | Tutorial Python, *Errors and Exceptions* |
| 26/11/26 | Sugerir `enumerate(anuncios, 1)` na listagem, pois ela mostra `[0]` e o usuário conta a partir de 1 | Revisor | `enumerate`; índice × posição exibida | Docs Python, *Built-in Functions* (`enumerate`) |

---

## 🔵 CICLO 10 — 28/10 — Modularização: funções

#### Registro do Ciclo 10 — 28/10
1. **Desafio do ciclo (em 1 frase):** Dividir o CRUD em funções com uma responsabilidade cada e eliminar os blocos de validação repetidos.
2. **O que implementei (commits / arquivos / links):** No `ato3` [https://github.com/pessefos/CRUD-engrenagem-de-pesquisa-wikipedia/blob/act-1/ato3]: `mostrar_menu`, `pedir_posicao`, `pedir_artigo`, `criar`, `ler`, `buscar`, `pesquisar`, `editar`, `apagar`, `ver_todos` e `main`, chamada por `if __name__ == "__main__"`. A validação de posição, que aparecia 3 vezes (ler, editar, apagar), ficou só em `pedir_posicao`, e o pedido de título e texto, que aparecia 2 vezes, ficou só em `pedir_artigo`. Teste: com as mesmas entradas do `ato2`, as saídas são idênticas, tanto no fluxo normal quanto com entradas inválidas. O arquivo foi de 100 para 135 linhas por causa de `def`, docstrings e linhas em branco.
3. **Objeto(s) de conhecimento mobilizado(s):** Definição de funções (`def`), parâmetros e `return`, retorno `None` como "entrada inválida", escopo local × global, lista como objeto mutável passado por referência, `main()` e `if __name__ == "__main__"`, docstrings.
4. **Desvio ou erro encontrado + causa técnica:** Ao escrever `apagar` como função, a linha `artigos = [item for ... if i != n]` (a forma que funcionava no código sem funções) **não apagava nada**: dentro da função, `artigos = ...` cria uma variável local nova e a lista da função chamadora continua com 3 artigos. Reproduzi num teste: depois da chamada, `len(lista)` continuava 3. Causa: atribuir a um nome dentro de uma função não altera o objeto que o chamador passou.
5. **Decisão de ajuste + fonte:** Alterar a lista no lugar com `artigos.pop(i)`, que modifica o mesmo objeto recebido por parâmetro, e devolver `None` quando a entrada for inválida para `criar`, `editar` e `apagar` não agirem. Fontes: *Pense em Python*, cap. 3 (funções) e cap. 10 (listas como argumentos); tutorial do Python 3, *Defining Functions* (escopo de variáveis).
6. **Feedback recebido e o que mudei:** **[PREENCHA só se houve feedback real; senão: "Sem feedback externo neste ciclo; projeto mantido".]**
7. **Próximo passo:** Estudar recursividade e aplicá-la na busca (Ciclo 11).

---

## 🔵 CICLO 11 — 04/11 — Recursividade

#### Registro do Ciclo 11 — 04/11
1. **Desafio do ciclo (em 1 frase):** Implementar a busca do Wikicrud de forma recursiva, com caso base e chamada recursiva corretos, sem estourar a pilha de execução.
2. **O que implementei (commits / arquivos / links):** Função `buscar(artigos, termo, inicio, fim)` no `ato3`: com a faixa vazia ou de um só artigo ela responde direto (casos base); caso contrário, divide a faixa ao meio e junta os resultados das duas metades. `pesquisar` chama `buscar(artigos, termo, 0, len(artigos))`. Antes dela, testei em um script à parte a versão linear (`buscar(artigos, termo, i + 1)`).
3. **Objeto(s) de conhecimento mobilizado(s):** Recursividade (caso base, chamada recursiva), pilha de execução e limite de recursão, divisão e conquista, divisão inteira `//`, concatenação de listas.
4. **Desvio ou erro encontrado + causa técnica:** A versão linear funciona com 900 artigos, mas com 1500 dá `RecursionError`, e o primeiro tamanho que quebra é 999. Causa: cada artigo é uma chamada empilhada, e o Python limita a pilha a 1000 chamadas (`sys.getrecursionlimit()`).
5. **Decisão de ajuste + fonte:** Adotar a divisão ao meio: a profundidade passa a ser cerca de log2(n), aproximadamente 11 para 2000 artigos, e o teste com 100000 artigos terminou sem erro. Manter `ver_todos` com `for`, que é mais simples e não tem limite de profundidade. Fontes: documentação do Python 3, `sys.getrecursionlimit`; *Pense em Python*, cap. 5 (recursividade).
6. **Feedback recebido e o que mudei:** **[PREENCHA só se houve feedback real; senão: "Sem feedback externo neste ciclo; projeto mantido".]**
7. **Próximo passo:** Refatorar o `ato3` para qualidade de código e revisar o CRUD de um colega com foco em qualidade (Ciclo 12).

### 🧩 CAMPO 06 — Próximos passos para a defesa

*AV Qualis — Grupo 3 | Individual | Quinta 26/11, 23h59*

**6a. Decisão técnica que defendo com plena autonomia — o que aprendi que é exclusivamente meu e não consigo transferir para nenhum colega:**

> **[RASCUNHO: reescreva com as suas palavras, porque este campo é avaliado como autoria sua.]** No `ato1`, uso `""` como valor sentinela de "posição livre" e validei a criação nesta ordem: primeiro campo vazio, depois posição livre, depois "sem espaço". A ordem importa: se um título `""` pudesse ser gravado, aquele artigo seria indistinguível de uma posição livre e sumiria da listagem e da pesquisa, que testam `titulo != ""`. O teste `titulo == "" or texto == ""` na frente da cadeia `elif` é o que garante que o valor sentinela nunca seja um dado válido. Foi isso que me fez ver que a validação de entrada protege também a representação interna dos dados.

**6b. Lacuna técnica e plano de ação para saná-la:**

- **Lacuna:** Meus dados somem ao encerrar o programa. Ainda não sei gravar e ler artigos em arquivo (`open`, `with`, formato de texto ou JSON).
- **Plano de ação (passos e datas):** 27/11 — ler o tutorial do Python sobre leitura e escrita de arquivos; 29/11 — gravar a lista de artigos em um arquivo ao sair e carregá-la ao iniciar; 01/12 — testar com arquivo ausente e com arquivo vazio, e commitar antes da Avaliação Substitutiva (02/12).

**6c. Pergunta que a banca pode fazer — com resposta fundamentada (mínimo 5 linhas):**

- **Pergunta:** Sua pesquisa é recursiva. Por que dividir a faixa ao meio em vez de chamar `buscar` com `i + 1`, que é mais simples? Defenda a escolha.
- **Resposta:**

> A versão com `i + 1` empilha uma chamada por artigo. O Python limita a pilha a 1000 chamadas, e eu testei: com 900 artigos funciona, com 1500 dá `RecursionError`, e o primeiro tamanho que quebra é 999. A divisão ao meio chama `buscar` duas vezes por nível, cada uma com metade da faixa, então a profundidade é cerca de log2(n): para 2000 artigos são uns 11 níveis, e com 100000 artigos o teste terminou sem erro. O custo é um pouco de complexidade e o trabalho de juntar duas listas em cada nível. Os casos base são dois: faixa vazia (`inicio >= fim`), que evita recursão infinita com lista vazia, e faixa de um só artigo, que faz a comparação de fato. Para só listar os artigos eu usei `for`, porque percorrer uma lista em ordem é mais simples e não tem limite de profundidade. A recursão compensa quando o problema se divide naturalmente, e aqui a divisão ao meio resolveu o limite sem mudar o resultado, que continua igual ao da versão com laço.

**Objeto de conhecimento mobilizado:** Recursividade (caso base, chamada recursiva, pilha de execução) **Fonte:** Documentação do Python 3, `sys.getrecursionlimit`; *Pense em Python*, cap. 5.

---

## 🔵 CICLO 12 — 11/11 — Refatoração e qualidade de código

#### Registro do Ciclo 12 — 11/11
1. **Desafio do ciclo (em 1 frase):** Refatorar o Wikicrud para eliminar duplicação e deixar o código legível, mantendo o comportamento.
2. **O que implementei (commits / arquivos / links):** No `ato3`: menu como constante `MENU` (dicionário), 11 funções pequenas, docstrings explicando entrada e retorno, `main()` separada da lógica e dois casos base documentados em `buscar`. Métricas: validação de posição de 3 blocos para 1; leitura de título e texto de 2 blocos para 1; saídas idênticas às do `ato2` nas mesmas entradas.
3. **Objeto(s) de conhecimento mobilizado(s):** Refatoração, remoção de duplicação, responsabilidade única por função, constantes, docstrings, pré-condições, casos base de recursão, teste de comportamento (comparar saídas antes e depois).
4. **Desvio ou erro encontrado + causa técnica:** Testando `buscar` isoladamente, notei que, sem o caso base `inicio >= fim`, uma lista vazia gera `RecursionError`: a faixa `[0, 0)` divide em `[0, 0)` e `[0, 0)` e nunca chega a um artigo. No programa isso apareceria ao pesquisar sem nenhum artigo cadastrado, pois `pesquisar` não testa lista vazia: quem protege esse caso é o caso base. Também documentei que `buscar` espera o termo já em minúsculas.
5. **Decisão de ajuste + fonte:** Manter os dois casos base, documentar a pré-condição (termo em minúsculas) na docstring e comparar sempre a saída nova com a antiga. Fontes: *Pense em Python*, cap. 5 (caso base); PEP 257 (docstrings).
6. **Feedback recebido e o que mudei:** **[PREENCHA só se houve feedback real; senão: "Sem feedback externo neste ciclo; projeto mantido".]**
7. **Próximo passo:** Persistir os artigos em arquivo (Campo 06b) e acrescentar testes automáticos.

### 🧩 CAMPO 05 — Registro de Revisão por Pares (revisão nº 2)
|                            |                                                                                        |
| -------------------------- | -------------------------------------------------------------------------------------- |
| **Autor do CRUD revisado** | Joás Franco Rodrigues                                                                  |
| **Repositório revisado**   | https://github.com/joasfranco/Algoritmos-e-programacao *(conforme o logbook do autor)* |
| **Revisor**                | Caio Rafael Tavares da Silva                                                           |
| **Ciclo / data**           | Ciclo 12 · revisão feita em 26/11                                                      |

**5a. AVANÇO DO PROCESSO DE REVISÃO:**

| ETAPA DO PROCESSO | RESPONSÁVEL | PRAZO | STATUS | DESVIO / JUSTIFICATIVA |
| --- | --- | --- | --- | --- |
| 1. Reler o código com foco em duplicação, nomes e estrutura | Revisor | 26/11 | ☒ Concluída | — |
| 2. Testar robustez: duplicatas, buscas com caixa diferente, busca vazia | Revisor | 26/11 | ☒ Concluída | — |
| 3. Verificar persistência dos dados entre execuções | Revisor | 26/11 | ☒ Concluída | — |
| 4. Registrar achados de qualidade | Revisor | 11/11 | ☒ Concluída | Ver 5e. |
| 5. Devolver o feedback ao Joás | Revisor / Autor | 27/11 | ☒ Em andamento | **[Envie ao Joás e atualize.]** |

**5b. ANÁLISE DE INSUMOS E CRITÉRIOS DE QUALIDADE:**

| RECURSO | QTDE PLANEJADA | QTDE UTILIZADA | VARIAÇÃO | JUSTIFICATIVA TÉCNICA |
| --- | --- | --- | --- | --- |
| Casos de teste de robustez | 4 | 5 | +1 | Incluí duplicata exata (dois "Bike", mesmo preço e categoria). |
| Funções no código revisado | — | 0 | — | Todo o fluxo está num único `while True`, sem funções. |
| Arquivos lidos | 1 | 1 | 0 | O Anuncify está num arquivo só. |

**5c. CONTROLE DE QUALIDADE:**

- **Critério ou norma técnica:** Qualidade de código do Ciclo 12: ausência de duplicação, funções com responsabilidade única, robustez a entradas vazias e inválidas.
- **A solução atende?** ☒ Parcialmente (valida bem vazio, negativo e texto, mas aceita `nan`/`inf` e duplicatas, e tudo fica em um único bloco sem funções).

**5d. GESTÃO DE RISCOS:**

- **Risco:** Sugerir refatoração para uma estrutura que o autor ainda não estudou.
- **Estratégia de mitigação:** Indicar só mudanças dentro do que o próprio Joás já usa (por exemplo, a mesma compreensão de lista que ele usa na busca) e deixar funções como sugestão opcional.

**5e. RASTREABILIDADE DAS DECISÕES TÉCNICAS — COM VÍNCULO AO CONTEÚDO:**

| DATA | DECISÃO TÉCNICA | RESP. | OBJETO DE CONHECIMENTO MOBILIZADO | FUNDAMENTAÇÃO / REFERÊNCIA |
| --- | --- | --- | --- | --- |
| 26/11/26 | Sugerir extrair o bloco de leitura do preço (`replace`, `float`, `try/except`, `< 0`) para uma função que devolve o preço ou `None` | Revisor | Funções; retorno `None`; responsabilidade única | *Pense em Python*, cap. 3; tutorial Python, *Defining Functions* |
| 26/11/26 | Apontar que dois anúncios idênticos (título, preço e categoria) são aceitos; sugerir recusar duplicata exata | Revisor | Regra de negócio em condicionais; comparação de dicionários | Docs Python, *Built-in Types* (`dict`, `in`) |
| 26/11/26 | Apontar que `str(item.get("titulo", ""))` é redundante: o título sempre existe e já é `str` | Revisor | Dicionários e tipos; simplificação | Docs Python, *Built-in Types* (`dict.get`) |
| 26/11/26 | Apontar que os anúncios só existem em memória e somem ao sair; sugerir gravar em arquivo como evolução | Revisor | Persistência (arquivos) | Tutorial Python, *Reading and Writing Files* |
| 26/11/26 | Registrar como ponto forte o tratamento de busca vazia e a busca sem diferenciar maiúsculas de minúsculas (`strip().lower()`) | Revisor | Strings (`strip`, `lower`); validação | Docs Python, *Built-in Types* (métodos de `str`) |

---

### 🧩 CAMPO 07 — Evolução conceitual

*AV Qualis — Grupo 3 | Individual | Quinta 26/11, 23h59*

**7a. O que eu pensava no início do ciclo (com base no Campo 01):**

> No Campo 01 eu listei variáveis, tipos (`str` e `int`) com `input()`/`print()`, condicionais e o laço `while` como o que eu precisava dominar. Minha hipótese era que as falhas viriam de entradas inesperadas (campo vazio, posição inexistente) e do limite de espaço, e que cada artigo precisaria de variáveis próprias, deixando o código repetitivo. Eu não sabia armazenar vários artigos sem um par de variáveis cada, não sabia se `input()` devolvia texto ou número e não sabia como procurar uma palavra dentro de um texto.

**7b. O que aprendi — conceitos, princípios ou relações técnicas que não dominava no início e que agora consigo explicar com precisão (mínimo 3 objetos de conhecimento):**

| OBJETO DE CONHECIMENTO | O QUE EU NÃO DOMINAVA | O QUE APRENDI E CONSIGO DEMONSTRAR | EVIDÊNCIA (campo do Logbook onde aparece) |
| --- | --- | --- | --- |
| Strings e operador `in` | Como procurar um trecho num texto e o que acontece com entrada vazia | `busca in titulo` testa substring e diferencia maiúsculas; `"" in s` é sempre `True`, e por isso a busca vazia listava tudo. Corrigi com recusa de busca vazia, `strip()` e `lower()` | Campo 01 (1b.4), Campo 03a, Ciclo 04 |
| Listas e matriz | Como guardar vários artigos sem 10 variáveis | `artigos` é uma matriz de linhas `[titulo, texto]`; índice a partir de 0, índice negativo não dá erro (o "0" lia o último), `pop()` renumera | Campo 01 (1b.1), Ciclos 07 e 08 |
| Funções e escopo | Que atribuir a um nome dentro da função não altera a lista do chamador | `artigos = [...]` dentro de `apagar` criava lista local e não apagava; `artigos.pop(i)` altera o mesmo objeto | Ciclo 10 (itens 4 e 5) |
| Recursividade | Que a recursão tem limite de profundidade | Busca linear recursiva quebra com 999 artigos (`RecursionError`); a divisão ao meio resolve com profundidade ~log2(n) | Ciclo 11, Campo 06c |

**7c. Conceitos que precisei corrigir ao longo do ciclo — onde eu estava equivocado e o que o corrigiu:**

1. **Equívoco:** Eu não sabia se o valor de `input()` vinha como texto ou número — **Correção:** vem sempre como `str`, e por isso o menu compara `op == "1"`, e o número do artigo precisa de `int()` **depois** de validar. **O que corrigiu:** leitura do cap. 2 do *Pense em Python* (Campo 02) e o erro de índice do Ciclo 07.
2. **Equívoco:** Eu achava que cada artigo precisaria de variáveis próprias — **Correção:** uma lista de linhas `[titulo, texto]` guarda qualquer quantidade e permite um `for` em vez de 5 blocos repetidos. **O que corrigiu:** estudo de listas (Ciclo 07) e a comparação 187 → 100 linhas com saídas idênticas.
3. **Equívoco:** **[CONFIRME que isso foi mesmo seu: "Eu esperava que apagar com `artigos = [...]` dentro de uma função alterasse a lista original"]** — **Correção:** o nome é local; é preciso alterar o objeto (`pop`). **O que corrigiu:** o teste do Ciclo 10 e o tutorial sobre escopo.

**7d. Transferência — como este aprendizado se aplica a um contexto diferente do problema trabalhado (ao menos 1 exemplo concreto da área de formação):**

> Em Engenharia de Software, a mesma ideia de recursão com caso base serve para percorrer a árvore de pastas de um projeto e listar todos os arquivos `.py`: o caso base é um arquivo, o caso recursivo é uma subpasta. Como a profundidade de pastas é pequena, o limite de 1000 chamadas não é problema, ao contrário da lista com milhares de artigos que eu testei. E a lição de validar a entrada antes de usá-la como índice vale para qualquer API que receba posições ou identificadores do usuário: sem validar, "0" lê o último item e "999" derruba o programa.

**7e. Avaliação honesta do próprio percurso — o que ainda não domino e preciso aprofundar após este ciclo:**

> Não sei persistir dados em arquivo, então tudo se perde ao fechar o programa (plano no Campo 6b). Não escrevi testes automáticos: meus testes foram manuais, comparando saídas antes e depois. Também ainda não domino tratamento de exceções com `try/except`, que usei só de leitura ao revisar o código do Joás, e não entendo bem o custo (complexidade) de juntar listas na recursão da busca.
# 🏁 DEFESA TÉCNICA — quarta 18/11

<details>
<summary>📘 Orientações para a Defesa Técnica e preparação</summary>

**A Defesa é antes dos prazos dos Grupos 2 e 3.** Você será arguido sobre o que já estiver registrado e commitado. Priorize, até **terça 17/11**:
- [ ] **Grupo 1 entregue** (prazo 16/11): Identificação, Registros 01 a 04, Campos 01 e 02.
- [ ] **Campo 04 (IA)** e **Campo 03** ao menos em rascunho, para sustentar as perguntas sobre decisões (critérios 2 e 5).
- [ ] **Campo 06c** (pergunta da banca e resposta) e **rascunho de 7a e 7b**, para sustentar a evolução conceitual (critério 3).
- [ ] Registros dos Ciclos já feitos, mesmo que ainda não "entregues" no prazo do grupo.
- [ ] `README.md`, `docs/` e CRUD rodando.
- [ ] Você consegue explicar **cada linha** do seu código e **cada decisão** registrada.
- Os demais itens seguem com os prazos dos grupos (21/11 e 26/11). A banca pode consultar o histórico do Git.

**A Defesa Técnica é individual.** Você será arguido sobre o que registrou. Cada aluno recebe pelo menos **1 questão** nos níveis de **Avaliação** ou **Criação** (taxonomia de Bloom).

**Como a Rubrica se liga ao seu Logbook:**

| Critério da Rubrica | Onde você prepara a evidência |
|---|---|
| 1. Domínio dos objetos de conhecimento | Campos 01, 02 e 07b |
| 2. Aplicação do conteúdo à solução ⚠️ *inegociável* | Registros dos ciclos (itens 3 e 5), Campo 03c e Campo 05e |
| 3. Evolução conceitual ⚠️ *inegociável* | Campo 01 → Campo 07 (7a, 7b e 7c; leve o rascunho) |
| 4. Capacidade de transferência | Campo 07d |
| 5. Argumentação sob pressão | Campo 06c e Campo 04e |
| 6. Autonomia intelectual e coerência com o Logbook | Todo o Logbook (principalmente Campos 04 e 06a) |

**Treino:** peça a um colega que faça 3 perguntas "imprevistas" sobre o seu CRUD e responda **sem consultar** o Logbook. Se não conseguir, volte ao Campo 06b.
</details>

## 🧩 RUBRICA DE DEFESA TÉCNICA (revisada)
*Avaliação individual de cada membro na Semana 16. Cada membro recebe ao menos 1 questão nos níveis de Avaliação ou Criação da Taxonomia de Bloom. Critérios revisados para medir aprendizagem, aplicação, evolução e transferência do conteúdo.*

| | |
|---|---|
| **Nome** | _…_ |
| **Curso / Time / Função** | _…_ |

<details>
<summary>🔒 Uso do professor — rubrica completa</summary>

| CRITÉRIO | EXCELENTE (4,0) | SATISFATÓRIO (3,0) | INSATISFATÓRIO (2,0) | AUSENTE (0) |
|---|---|---|---|---|
| **1. DOMÍNIO DOS OBJETOS DE CONHECIMENTO** — Responde com precisão técnica, sem apoio dos colegas, demonstrando aprendizagem do conteúdo. | Responde com precisão e profundidade, nomeando os objetos de conhecimento mobilizados sem hesitação. | Responde com precisão, com imprecisões pontuais que não comprometem o raciocínio. | Responde de forma vaga, com erros conceituais relevantes ou dependendo dos colegas. | Não responde ou demonstra desconhecimento total. |
| **2. APLICAÇÃO DO CONTEÚDO À SOLUÇÃO** — Demonstra como os objetos de conhecimento fundamentaram as decisões do processo. | Explicita com precisão qual objeto de conhecimento fundamentou cada decisão relevante do processo investigativo, citando referência e demonstrando por que aquele conhecimento era o mais adequado. | Estabelece a relação conteúdo-decisão na maioria das perguntas, com alguma imprecisão pontual. | Não consegue explicitar a relação entre o conteúdo e as decisões do processo investigativo com clareza. | Não demonstra nenhuma relação entre os objetos de conhecimento e as decisões tomadas. |
| **3. EVOLUÇÃO CONCEITUAL** — Demonstra aprendizagem em relação ao que sabia no início do ciclo. | Identifica com precisão o que aprendeu, o que corrigiu e como o conhecimento evoluiu ao longo do ciclo. | Demonstra evolução em parte dos conceitos trabalhados, com alguma dificuldade de articular a trajetória. | Dificuldade em identificar diferenças entre o que sabia no início e o que domina agora. | Não demonstra nenhuma percepção de evolução conceitual ao longo do ciclo. |
| **4. CAPACIDADE DE TRANSFERÊNCIA** — Aplica o conhecimento a um contexto diferente do problema trabalhado. | Consegue transferir o aprendizado para um contexto novo com fundamentação técnica precisa. | Realiza a transferência com imprecisões que não comprometem a lógica do raciocínio. | Demonstra dificuldade em aplicar o conhecimento a contextos diferentes do problema original. | Não consegue realizar nenhuma transferência do conhecimento para contexto diferente. |
| **5. ARGUMENTAÇÃO SOB PRESSÃO** — Mantém coerência técnica diante de questionamentos imprevistos. | Mantém raciocínio coerente, reconhece limites com honestidade e reformula com fundamentação. | Mantém coerência na maior parte, com hesitações pontuais sem perda do fio técnico. | Fragilidade técnica diante de questionamentos imprevistos. | Não sustenta argumentação técnica diante de nenhum questionamento. |
| **6. AUTONOMIA INTELECTUAL E COERÊNCIA COM O LOGBOOK** — Defende o que registrou com consciência e sem depender do grupo. | Defende com precisão as decisões do Logbook, demonstrando autoria plena e independência intelectual. | Defende a maioria das decisões com coerência, com alguma imprecisão ou apoio pontual. | Depende dos colegas ou demonstra desconhecimento de parte do que registrou no próprio Logbook. | Não reconhece o que registrou ou não demonstra autonomia intelectual durante a arguição. |

**PONTUAÇÃO:** _____ / 24,0 **CONCEITO:** _____________

**Conversão:** 20–24 = Excelente (4,0) | 14–19 = Satisfatório (3,0) | 8–13 = Insatisfatório (2,0) | < 8 = Ausente (0)

> ⚠️ **Critérios 2 (Aplicação) e 3 (Evolução Conceitual) são inegociáveis — AUSENTE em qualquer um deles implica nota máxima de 2,0 na Defesa, independentemente do desempenho nos demais.**

**OBSERVAÇÕES:** _…_

**Professor(a):** _________________  **Data:** ___________
</details>

### Registro do Encerramento — 18/11
1. **O que apresentei/defendi (em 1 frase):** _…_
2. **Objeto(s) de conhecimento que a banca mais explorou:** _…_
3. **Pergunta que mais me desafiou e como respondi:** _…_
4. **O que levo deste semestre para o próximo módulo:** _…_

---

# 🆘 Estou atrasado no Logbook. E agora?

1. **Não apague nem "retroescreva" o passado.** Preencha agora e **escreva a data real** do preenchimento (ex.: *"preenchido com atraso em 12/11"*).
2. **Campo 01 e Checkpoint (sem consulta):** se perdeu a janela, registre **o que sabe hoje, sem consultar nada**, marcando-o como *preenchimento tardio*. Combine o tratamento com o professor.
3. **Priorize a ordem dos grupos:** Grupo 1 (16/11) → Defesa (18/11) → Grupo 2 (21/11) → Grupo 3 (26/11). Dentro de cada grupo, os Campos vêm antes dos Registros.
4. **Use o histórico do Git** (`git log --oneline`) para reconstruir o que fez em cada ciclo — ele é uma evidência melhor que a memória.
5. **Fale com o professor** antes do prazo, não depois.
