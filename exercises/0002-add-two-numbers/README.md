**Add Two Numbers - Exercício LeetCode**

Descrição:
Dadas duas listas ligadas não vazias que representam dois números inteiros não negativos, onde os dígitos estão armazenados em ordem reversa e cada nó contém um único dígito, some os dois números e retorne o resultado como uma lista ligada.

Você pode assumir que os números não contêm zeros à esquerda, exceto o próprio número zero.

---

Exemplos:

<img src="https://assets.leetcode.com/uploads/2020/10/02/addtwonumber1.jpg">

1. Entrada: l1 = \[2,4,3], l2 = \[5,6,4]
   Saída: \[7,0,8]
   Explicação: 342 + 465 = 807

2. Entrada: l1 = \[0], l2 = \[0]
   Saída: \[0]

3. Entrada: l1 = \[9,9,9,9,9,9,9], l2 = \[9,9,9,9]
   Saída: \[8,9,9,9,0,0,0,1]

---

Restrições:

* O número de nós em cada lista está entre 1 e 100.
* Cada valor do nó está entre 0 e 9.
* A lista representa um número sem zeros à esquerda (exceto para zero).

---

Como rodar os testes:

1. Crie um arquivo `add_two_numbers.go` com a função `addTwoNumbers(l1 *ListNode, l2 *ListNode) *ListNode`.

2. Crie testes para validar sua implementação com os exemplos acima.

3. Rode os testes com:
   `go test -v`

---

Dicas para implementação:

* Use uma variável para armazenar o carry (vai-um) da soma.
* Percorra as duas listas ao mesmo tempo, somando os valores e o carry.
* Crie novos nós para o resultado com o valor da soma módulo 10.
* No final, se houver carry, crie um nó extra.

---

Esse exercício é excelente para praticar manipulação de listas ligadas e operações aritméticas básicas em Go.