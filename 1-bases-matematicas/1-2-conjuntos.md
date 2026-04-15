# Generalidades sobre Conjuntos

## Conceitos básicos

Um **conjunto** é uma coleção bem definida de elementos.

### Representação:

* Por extensão:
  A = {1, 2, 3}
* Por compreensão:
  A = {x | x é par}

### Notação:

* x ∈ A → x pertence a A
* x ∉ A → x não pertence
* ∅ → conjunto vazio

---

## Relações elementares

**Inclusão:**

* A ⊆ B → todo elemento de A está em B
* A ⊂ B → subconjunto próprio

**Igualdade:**

* A = B → têm os mesmos elementos

**Conjunto das partes:**

* 𝒫(A) → conjunto de todos os subconjuntos de A

---

### Operações com conjuntos

**União (A ∪ B)**

Elementos que estão em A **ou** B

**Interseção (A ∩ B)**

Elementos comuns

**Diferença (A - B)**

Elementos de A que não estão em B

**Complemento**

Elementos fora de A (em relação a um universo U)

---

## Conjuntos Numéricos

### Naturais, Inteiros e Racionais

* ℕ → naturais (0, 1, 2, …)
* ℤ → inteiros (..., -1, 0, 1, ...)
* ℚ → racionais (frações)

---

### Operações básicas

**Soma e multiplicação**

* Fechamento: resultado pertence ao conjunto
* Associatividade e comutatividade
* Elementos neutros:

  * 0 (soma)
  * 1 (multiplicação)

**Potenciação**

Para aⁿ:

* n > 0 → multiplicação repetida
* n = 0 → a⁰ = 1 (a ≠ 0)
* n < 0 → inverso (1/aⁿ)

---

### Princípio de Indução Finita

Base para provar propriedades em ℕ:

1. Verdade para n inicial
2. Se vale para n, então vale para n+1

> Conclusão: vale para todo n

---

## Números Reais (ℝ)

Contêm:

* racionais + irracionais

---

### Apresentação axiomática

Os reais são definidos por propriedades como:

* ordem (≤)
* completude (não há “buracos”)
* operações bem definidas

> Essa “completude” diferencia ℝ de ℚ

---

### Potenciação em ℝ

Inclui:

* expoentes fracionários → raízes
* expoentes irracionais → definidos via limites

---

### Representações dos reais

* Decimal finito: 0,5
* Decimal periódico: 0,333...
* Decimal infinito não periódico → irracional

---

### Valor absoluto

|x| = distância até o zero

**Definição:**

* |x| = x, se x ≥ 0
* |x| = -x, se x < 0

---

### Introdução à Topologia da Reta

Estuda “estrutura” dos reais:

**Conceitos:**

* Intervalos:

  * (a, b) → aberto
  * [a, b] → fechado

* Vizinhança:
  Região ao redor de um ponto

> Base para limites e continuidade

---

### Plano Cartesiano

Sistema de coordenadas (x, y)

* Eixo x → horizontal
* Eixo y → vertical

Cada ponto → par ordenado (x, y)

> Base para gráficos e geometria analítica

---

## Complementos sobre Conjuntos

### Famílias de conjuntos

Uma **família de conjuntos** é um conjunto cujos elementos são conjuntos.

Exemplo:

* 𝒜 = {A₁, A₂, A₃}

---

### Sobre índices

Usamos índices para organizar:

* A₁, A₂, ..., Aₙ
* ou Aᵢ, com i pertencendo a um conjunto índice

---

### Operações com famílias de conjuntos

**União geral:**

⋃ Aᵢ → elementos que pertencem a pelo menos um conjunto

**Interseção geral:**

⋂ Aᵢ → elementos comuns a todos

**Exemplo:**

Se:

* A₁ = {1,2}
* A₂ = {2,3}

Então:

* ⋃ = {1,2,3}
* ⋂ = {2}

---

## Resumo

* **Conjuntos** → organização de elementos
* **Operações** → união, interseção, diferença
* **Numéricos** → ℕ, ℤ, ℚ, ℝ
* **Indução** → prova para infinitos casos
* **Reais** → contínuos (sem lacunas)
* **Topologia** → estrutura da reta
* **Famílias** → conjuntos de conjuntos
