**Two Sum - Exercício LeetCode**

Descrição:
Dado um array de inteiros `nums` e um inteiro `target`, retorne os índices dos dois números que somados resultam no valor `target`.

Cada entrada tem exatamente uma solução e você não pode usar o mesmo elemento duas vezes. A ordem dos índices na resposta pode ser qualquer uma.

---

Exemplos:

1. Entrada: nums = \[2,7,11,15], target = 9
   Saída: \[0,1]
   Explicação: nums\[0] + nums\[1] == 9

2. Entrada: nums = \[3,2,4], target = 6
   Saída: \[1,2]

3. Entrada: nums = \[3,3], target = 6
   Saída: \[0,1]

---

Restrições:

* O tamanho do array está entre 2 e 10.000.
* Os valores de nums e target podem ser negativos ou positivos, dentro do intervalo -10^9 a 10^9.
* Existe apenas uma solução válida para cada entrada.

---

Desafio adicional:
Tente implementar uma solução com complexidade menor que O(n²).

---

Como rodar os testes:

1. Crie um arquivo `two_sum.go` com a função `twoSum(nums []int, target int) []int`.

2. Crie um arquivo `two_sum_test.go` com testes automatizados que validem a função com os exemplos acima.

3. Para executar os testes, rode o comando:
   `go test -v`

---

Dicas para a implementação:
Use um mapa (hash map) para guardar os números já visitados e seus índices, assim pode buscar o complemento para o target em tempo O(1) e atingir complexidade O(n).

---

Referências:

* LeetCode: Two Sum
* Documentação oficial do Go
