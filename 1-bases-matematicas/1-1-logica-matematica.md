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

> A negação de ¬p é p

---

### Conjunção (p ∧ q): “E”

Só é verdadeira quando **ambas são verdadeiras**.

Exemplo:

* p: “Estudo”
* q: “Faço exercícios”
* p ∧ q: “Estudo e faço exercícios”

> A negação de p ∧ q é (não p) *ou* (não q)

---

### Disjunção (p ∨ q): “OU”

É verdadeira quando **pelo menos uma é verdadeira**.

> A negação de p ∨ q é (não p) *e* (não q)

---

### Condicional (p ⇒ q): “SE... ENTÃO”

Só é falsa quando:

* p é verdadeira
* q é falsa

Exemplo:

* “Se estudo, então passo”

> A negação da implicação p ⇒ q é a proposição p e não q

* `q ⇒ p` é chamada de **recíproca** da proposição
* `não q ⇒ não p` é chamado de **contrapositiva**
* `não p ⇒ não q` é chamado de **inversa** da proposição

---

### Bicondicional (p ↔ q): “SE E SOMENTE SE”

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

> A negação da proposição ∀x ∈ D é verdade p(x) é a proposição ∃x ∈ ℝ, não é verdade p(x)

---

### Quantificador Existencial (∃)

Significa: **“existe pelo menos um”**

Exemplo:

* ∃x ∈ ℝ, x² = 4
  (Existe um número real cujo quadrado é 4 → x = 2 ou -2)

> A negação da proposição ∃x ∈ ℝ, é verdade p(x) é a proposição ∀x ∈ D, não é verdade p(x)

> Existe e é único: ∃!

---

### Exemplos e Contra-exemplos

|                          | “para todo“ ∀ |  ”existe“ ∃  |
|--------------------------|---------------|--------------|
|existem exemplos          | inconclusivo  |  verdadeira  |
|não existem exemplos      |       —       |    falsa     |
|existem contraexemplos    |      falsa    | inconclusivo |
|não existem contraexemplos|  verdadeira   |       —      |

---

## Condição Necessária e Suficiente

Esse é um dos pontos mais importantes — e onde muita gente confunde.

---

### Condição Suficiente

“Se p acontece, então q acontece”

 > p garante q

Exemplo:

* “Estudar é suficiente para aprender”

Forma lógica:

* p ⇒ q

---

### Condição Necessária

“Para q acontecer, p precisa acontecer”

> q depende de p

Exemplo:

* “Respirar é necessário para viver”

Forma:

* q ⇒ p

---

### Condição Necessária e Suficiente

Quando uma coisa implica a outra **nos dois sentidos**:

> p ↔ q

Exemplo clássico:

* “Um número é par **se e somente se** é divisível por 2”

---

## Demonstração

Uma **demonstração (prova)** é um raciocínio lógico que mostra que uma proposição é **sempre verdadeira**, partindo de:

* definições
* axiomas (verdades básicas)
* teoremas já provados

> Ou seja: não é “testar exemplos”, é **provar para todos os casos possíveis**.

---

### Estrutura de uma demonstração

Quase toda prova segue esse fluxo:

1. **Hipótese** (o que é dado)
2. **Objetivo** (o que você quer provar)
3. **Desenvolvimento lógico**
4. **Conclusão**

---

### Exemplo simples

Provar:
Se n é par, então n² é par.

**Prova:**

* Se n é par → n = 2k
* Então: n² = (2k)² = 4k² = 2(2k²)
* Logo, n² é par

> Conclusão: provado

---

## Principais métodos de demonstração

---

### Demonstração Direta

Você parte da hipótese e chega diretamente na conclusão.

### Estrutura:

Para demonstrar que `p ⇒ q` suponha que p é verdadeiro, e através de uma série de etapas, cada uma seguinte das anteriores, conclui-se q.

### Exemplo:

Se um número é múltiplo de 4, então é par

* n = 4k
* n = 2(2k)
* Logo, é par

---

### Demonstração por Contraposição

Usa a equivalência lógica:

Para demonstrar que `p ⇒ q`, demonstra-se que não q implica não p.

> Às vezes é mais fácil provar o “contrário invertido”.

---

### Exemplo:

Se n² é par, então n é par

Em vez de provar direto, fazemos:

* Se n **não é par** (ou seja, é ímpar)
* Então n = 2k + 1
* n² = (2k+1)² = 2(alguma coisa) + 1 → ímpar

Logo:

* Se n fosse ímpar → n² seria ímpar
* Então, se n² é par → n é par

---

### Demonstração por Contradição (Redução ao absurdo)

Demonstra que se algum enunciado fosse falso, ocorreria uma contradição lógica, e portanto o enunciado deve ser verdadeiro.

---

### Estrutura:

1. Suponha que a proposição é falsa
2. Chegue a uma contradição
3. Conclua que a proposição é verdadeira

---

### Exemplo clássico:

Provar que √2 é irracional

Ideia:

* Suponha que √2 é racional → pode ser escrito como fração
* Manipulando a equação, você chega que o número é par e ímpar ao mesmo tempo

`Contradição`

Logo, a suposição é falsa → √2 é irracional

---

### Demonstração por Indução Matemática

Usada quando a afirmação depende de números naturais.

---

### Estrutura:

1. **Base**: prova para n = 1 (ou outro inicial)
2. **Passo indutivo**:

   * assume que vale para n
   * prova que vale para n+1

---

### Exemplo:

Provar que:
1 + 2 + ... + n = n(n+1)/2

* Base: n=1 → ok
* Hipótese: vale para n
* Prova para n+1:

Somatório até n+1 =
n(n+1)/2 + (n+1)

Fatorando → (n+1)(n+2)/2

> Funciona → provado

---

### Contraexemplo

Usado para **refutar** uma afirmação universal.

Se alguém diz:

* “Todo número primo é ímpar”

Basta mostrar:

* 2 é primo e é par

> Pronto, a afirmação é falsa

---

## Dicas importantes

* Para demonstrar p ↔ q, devemos demonstrar duas implicações separadamente
* Nunca use exemplos como prova geral
* Seja rigoroso com definições
* Cada passo precisa ser justificado
* Evite “pular lógica”

---

## Resumo

* **Proposição** → frase com valor lógico (V/F)
* **Conectivos** → combinam proposições
* **Quantificadores** → falam de “todos” ou “existe”
* **Necessário vs suficiente**:
  * Suficiente → garante
  * Necessário → é obrigatório
  * Ambos → equivalência
    
* Demonstrações:

| Método        | Ideia principal               |
|---------------|-------------------------------|
| Direta        | Vai da hipótese à conclusão   |
| Contraposição | Prova o contrário equivalente |
| Contradição   | Assume falso e quebra         |
| Indução       | Prova para todos os naturais  |
| Exaustão      | Testa todos os casos          |
| Contraexemplo | Derruba uma afirmação         |
