# Elementos de Linguagem e Lógica Matemática 

## Proposições

Uma **proposição** é uma frase declarativa que pode ser classificada como:

* **Verdadeira (V)**
* **Falsa (F)**

> Ela não pode ser ambígua nem opinativa.

### Exemplos:

* “2 + 2 = 4” → Proposição (V)
* “O céu é verde” → Proposição (F)
* “Que horas são?” → Não é proposição (é pergunta)
* “Estude mais!” → Não é proposição (é ordem)

Em lógica, representamos proposições com letras:

* **p:** “Está chovendo”
* **q:** “Vou estudar”

---

## Conectivos Lógicos

Servem para **combinar proposições** e formar novas proposições.

### Negação (¬p)

* Inverte o valor lógico

Exemplo:

* p: “Está chovendo”
* ¬p: “Não está chovendo”

---

### Conjunção (p ∧ q) → “E”

Só é verdadeira quando **ambas são verdadeiras**.

Exemplo:

* p: “Estudo”
* q: “Faço exercícios”
* p ∧ q: “Estudo e faço exercícios”

---

### Disjunção (p ∨ q) → “OU”

É verdadeira quando **pelo menos uma é verdadeira**.

---

### Condicional (p → q) → “SE... ENTÃO”

Só é falsa quando:

* p é verdadeira
* q é falsa

Exemplo:

* “Se estudo, então passo”

---

### Bicondicional (p ↔ q) → “SE E SOMENTE SE”

É verdadeira quando:

* ambas são verdadeiras OU
* ambas são falsas

---

## Quantificadores

Usados quando falamos de **conjuntos** (muito comum em matemática e programação).

### Quantificador Universal (∀)

Significa: **“para todo”**

Exemplo:

* ∀x ∈ ℝ, x + 0 = x
  (Para todo número real, somar 0 não muda o valor)

---

### Quantificador Existencial (∃)

Significa: **“existe pelo menos um”**

Exemplo:

* ∃x ∈ ℝ, x² = 4
  (Existe um número real cujo quadrado é 4 → x = 2 ou -2)

---

## Condição Necessária e Suficiente

Esse é um dos pontos mais importantes — e onde muita gente confunde.

---

### Condição Suficiente

“Se A acontece, então B acontece”

 > A garante B

Exemplo:

* “Estudar é suficiente para aprender”

Forma lógica:

* A → B

---

### Condição Necessária

“Para B acontecer, A precisa acontecer”

> B depende de A

Exemplo:

* “Respirar é necessário para viver”

Forma:

* B → A

---

### Condição Necessária e Suficiente

Quando uma coisa implica a outra **nos dois sentidos**:

> A ↔ B

Exemplo clássico:

* “Um número é par **se e somente se** é divisível por 2”

---

## Resumo

* **Proposição** → frase com valor lógico (V/F)
* **Conectivos** → combinam proposições
* **Quantificadores** → falam de “todos” ou “existe”
* **Necessário vs suficiente**:

  * Suficiente → garante
  * Necessário → é obrigatório
  * Ambos → equivalência
