# Números Positivos e Negativos

Este programa em C# permite ao usuário inserir 20 números e, em seguida, identifica quantos deles são positivos e quantos são negativos. Os números positivos e negativos são exibidos separadamente no final.

## Como usar

1. Certifique-se de ter o ambiente de desenvolvimento C# configurado em sua máquina.
2. Copie o código fornecido e cole-o em um arquivo `.cs`.
3. Compile e execute o programa.
4. Siga as instruções na linha de comando para inserir os números.

## Funcionamento

O programa começa pedindo ao usuário para inserir 20 números. Para cada número inserido, ele verifica se o número é positivo, negativo ou zero. Os números positivos são armazenados em um array chamado `p`, os números negativos são armazenados em um array chamado `n`, e as contagens de números positivos (`c1`) e negativos (`c2`) são atualizadas.

No final da entrada, o programa exibirá:

- A quantidade de números positivos inseridos.
- A quantidade de números negativos inseridos.
- A lista de números positivos inseridos.

Se o usuário inserir um valor não numérico, o programa exibirá uma mensagem de erro e solicitará novamente a entrada para aquele número.

## Observações

- O programa não lida com a entrada de números maiores que 20 ou menores que -20 de forma eficaz, já que utiliza arrays de tamanho fixo.
- O programa poderia ser otimizado e melhorado para lidar com entradas fora do intervalo esperado e com tamanhos variáveis de entrada.

Este código é apenas um exemplo didático e pode ser melhorado para atender a casos mais complexos e situações de uso mais realistas.
