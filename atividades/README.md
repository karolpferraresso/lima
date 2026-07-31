# Exercícios Práticos de XML – Correção de Erros

## Exercício 1 – Cadastro de Livro

### O que foi corrigido

Neste exercício, a tag `<titulo>` não havia sido fechada corretamente. Foi adicionada a tag de fechamento `</titulo>`, garantindo que todas as tags abertas fossem encerradas de forma correta.

**Conceito trabalhado:**

* Fechamento correto das tags.

---

## Exercício 2 – Cadastro de Aluno

### O que foi corrigido

Foram corrigidos dois problemas:

* O atributo `matricula` recebeu aspas, conforme a sintaxe do XML.
* A tag `<idade=20>` foi substituída pela estrutura correta `<idade>20</idade>`.

**Conceitos trabalhados:**

* Atributos devem possuir valores entre aspas.
* Os dados devem ficar entre a tag de abertura e a de fechamento.

---

## Exercício 3 – Empresa

### O que foi corrigido

A declaração XML foi ajustada, colocando aspas corretamente no atributo `version`. Além disso, o caractere especial `&` presente no nome da empresa foi substituído por `&amp;`, que é a forma correta de representar esse símbolo em XML.

**Conceitos trabalhados:**

* Sintaxe correta da declaração XML.
* Utilização de caracteres especiais.

---

## Exercício 4 – Pedido de Venda

### O que foi corrigido

As tags estavam fechadas em uma ordem diferente da abertura, causando erro na estrutura do documento. Foi reorganizada a hierarquia para que cada elemento fosse fechado corretamente.

**Conceitos trabalhados:**

* Hierarquia entre elementos.
* Aninhamento correto das tags.

---

## Exercício 5 – Cadastro de Produtos

### O que foi corrigido

O nome da tag `<nome produto>` foi alterado para `<nome_produto>`, pois nomes de elementos não podem conter espaços. Também foi renomeada a tag `<1preco>` para `<preco>`, já que elementos XML não podem iniciar com números.

**Conceitos trabalhados:**

* Regras para nomeação de elementos XML.
* Identificadores válidos para tags.

---

## Exercício 6 – Sistema Escolar (Desafio)

### O que foi corrigido

Foram realizados diversos ajustes:

* Correção das aspas na declaração XML.
* Inclusão de aspas nos atributos da tag `<aluno>`.
* Substituição do caractere `&` por `&amp;`.
* Fechamento da primeira tag `<disciplina>`, que estava incompleta.

Esse exercício reuniu vários tipos de erros encontrados nos exercícios anteriores.

**Conceitos trabalhados:**

* Declaração XML.
* Uso correto de atributos.
* Caracteres especiais.
* Fechamento de tags.
* Estrutura hierárquica do documento.

