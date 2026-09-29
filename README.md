# miniguia-logica-algoritmos
Caderno temático de Lógica de Programação e Algoritmos criado no NotebookLM para o desafio da DIO.

🔗 **Acesse o Caderno Temático Oficial no NotebookLM:** [Ver Caderno no NotebookLM](https://notebook.google.com/notebook/31f3447c-d5db-42d8-afc7-379724a807a5)

---

# 🚀 Miniguia de Estudos: Lógica de Programação e Algoritmos

Este repositório apresenta o desenvolvimento de um Caderno Temático utilizando o **NotebookLM**, estruturado como parte do Desafio de Projeto da DIO para a formação em Análise e Desenvolvimento de Sistemas.

---

## 🎯 1. Contexto e Objetivos

* **Assunto Escolhido:** Lógica de Programação e Algoritmos (Fundamentos de programação, estruturas condicionais, laços de repetição e manipulação de dados básicos).
* **Objetivos de Estudo:**
  1. Consolidar os conceitos fundamentais da lógica computacional através da curadoria de materiais do curso de ADS.
  2. Utilizar o NotebookLM para gerar resumos, tirar dúvidas e criar perguntas de fixação baseadas nos PDFs das aulas.
  3. Estruturar um guia prático de referência rápida para consultas futuras em projetos de desenvolvimento.

---

## 📚 2. Curadoria de Fontes

Para alimentar o Caderno Temático no NotebookLM, foram selecionados os seguintes materiais (PDFs e exercícios do curso):

1. **Apostila / Slides de Introdução à Lógica de Programação**
   * *Tipo:* PDF de Conteúdo Teórico
   * *Descrição:* Conceitos de algoritmos, fluxogramas, pseudocódigo (Português Estruturado) e variáveis.
2. **Lista de Exercícios Práticos - Estruturas Condicionais (If/Else)**
   * *Tipo:* Documento de Exercícios
   * *Descrição:* Problemas práticos envolvendo tomadas de decisão lógicas.
3. **Lista de Exercícios - Laços de Repetição (While / For)**
   * *Tipo:* Documento de Exercícios
   * *Descrição:* Exercícios focados em repetição de blocos de código e contadores.

*(Nota: Os materiais foram carregados diretamente na interface do NotebookLM para servirem como base exclusiva de consulta da inteligência artificial).*

---

## 💡 3. Engenharia de Prompts e "Cicatrizes" (Troubleshooting)

Nesta seção, documentamos a jornada de testes e refinamento das interações com o NotebookLM para extrair o melhor proveito didático dos materiais.

### Teste 1: Síntese de Conceitos Complexos
* **Prompt Utilizado:** 
  > *"Explique o que é uma estrutura de repetição."*
* **Resultado Obtido:** Uma definição muito curta e teórica que não detalhava a diferença prática entre `While` e `For`.
* **Dificuldade / Desafio:** A IA deu uma resposta genérica da internet e não focou nas especificidades trazidas pelo material da minha apostila.
* **Ajuste (Refinamento):** 
  > *"Com base estritamente nas fontes enviadas, explique a diferença prática entre as estruturas de repetição apresentadas, fornecendo um exemplo em pseudocódigo para cada uma."*
* **Resultado Final (Sucesso):** Resposta rica, alinhada diretamente com a didática do curso de ADS e com exemplos claros em pseudocódigo.

### Teste 2: Transformação de Teoria em Prática
* **Prompt Utilizado:** 
  > *"Crie um exercício para mim."*
* **Resultado Obtido:** Um exercício gerado aleatoriamente que utilizava conceitos avançados ainda não vistos nas aulas.
* **Ajuste (Refinamento):** 
  > *"Utilizando o nível de dificuldade dos exercícios da fonte de listas de exercícios, crie um desafio inédito envolvendo condicionais compostas que simule um sistema de notas escolares."*
* **Resultado Final (Sucesso):** Um exercício no formato exato do curso, ideal para treinar a lógica.

---

## 📖 4. Miniguia de Estudo (Entrega Final)

### 📝 Resumos Estruturados
* **Algoritmo:** É uma sequência finita de passos bem definidos e não ambíguos para resolver um problema ou realizar uma tarefa.
* **Variáveis e Tipos de Dados:** Espaços reservados na memória para armazenar valores temporários (inteiros, reais, caracteres, lógicos).
* **Estruturas Condicionais:** Permitem desviar o fluxo de execução do algoritmo com base em testes lógicos verdadeiro/falso (`se / então / senão`).
* **Estruturas de Repetição:** Executam um bloco de código várias vezes enquanto uma condição for verdadeira (`enquanto`, `para`).

### 🔤 Glossário de Conceitos
* **Pseudocódigo (Português Estruturado):** Forma de escrever algoritmos de forma humanizada, próxima da nossa língua natural, antes de codificar em uma linguagem de programação real.
* **Fluxograma:** Representação gráfica de um algoritmo utilizando símbolos geométricos padronizados.
* **Loop Infinito:** Erro lógico onde a condição de parada de uma repetição nunca é atingida, fazendo o programa travar ou rodar para sempre.

### 🔄 Prompts Reutilizáveis (para Revisões Futuras)
* *Para fixar um novo conceito:*
  > *"Explique o conceito de [inserir conceito, ex: vetor] de forma simples, usando uma analogia do mundo real baseada nas fontes."*
* *Para debugar um raciocínio:*
  > *"Analise este trecho de pseudocódigo abaixo e me aponte onde está o erro lógico de acordo com as boas práticas estudadas."*
