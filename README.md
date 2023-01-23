# Case técnico da BISO para Engenheiro de Software

## Introdução:

Seja bem-vindo ao case técnico da BISO para Engenheiro de Software! Aqui você será desafiado a resolver um problema que exigirá capacidade analítica, resolução de problemas e conhecimento sobre a base da computação. Será necessário conhecimento prévio de estruturas de dados, seu funcionamento e quais problemas elas resolvem.

O case a princípio pode parecer simples, mas será que você chegará na melhor solução? (OBS: nem sempre o caminho mais simples é a melhor solução. Problemas complexos exigem soluções complexas.)

## Problema:

A mediana de um conjunto de inteiros é o valor do ponto médio do conjunto de dados para o qual um número igual de inteiros é menor e maior que o valor. Para encontrar a mediana, você deve primeiro classificar seu conjunto de números inteiros em ordem não decrescente e, em seguida:

- Se o seu conjunto contém um número ímpar de elementos, a mediana é o elemento do meio da amostra classificada. No conjunto classificado **{1, 2, 3}**, o 2 é a mediana.

- Se o seu conjunto contém um número par de elementos, a mediana é a média dos dois elementos do meio da amostra classificada. No conjunto classificado **{1, 2, 3, 4}**,  **2+3 / 2 = 2.5** é a mediana.

Dado um fluxo de entrada de **N** inteiros, execute a seguinte tarefa para cada número inteiro da entrada:

- Adicione o número inteiro a uma lista contínua de inteiros.
- Encontre a mediana da lista atualizada (ou seja, para o primeiro elemento até o N elemento adicionado a lista).
- Imprima a mediana atualizada em uma nova linha. O valor impresso deve ser um número de precisão dupla escalado para casas decimais (ou seja 12.4, formato).

### Exemplo:

**a = [7, 3, 5, 2]**

| Lista de numeros atual | Mediana |
| :-----: | :-----: |
| [7] | 7.0 |
| [3, 7] | 3+7 / 2 = 5.0 |
| [3, 5, 7] | 5.0 |
| [2, 3, 5, 7] |3+5 / 2 = 4.0 |

**OBS:** Cada um dos valores medianos é armazenado em uma matriz e a matriz é retornada para a função principal imprimir.

### Formato dos dados de entrada:
- Deve ser um arquivo de texto, onde na primeira linha contém a quantidade de números inteiros a serem processados e, nas demais linhas contém o número inteiro a ser processado.

Exemplo simples:

| Aquivo de entrada.txt | Função |
| :-----: | :-----: |
| 3 | size = 3 |
| 12 | lista de inteiros = [12, 4, 5] |
| 4 | |
| 5 | |

Saída esperada:

| Resultado |
| :-----: |
|12.0|
|8.0|
|5.0|

## Resultado final esperado:

Após resolver o case, você deve enviar um e-mail para jonathan.raphael@biso.digital e breno.berman@biso.digital contendo as seguintes informações:

Conteúdo do repositório:
- Código da solução;
- Instruções de como executar a solução;
- Arquivos para teste;
- Explicaçao da solução.

- Link do repositório (público) onde foi colocado o código final para a solução do problema.
- 
