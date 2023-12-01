# Calculadora de Expressões Matemáticas em Notação Posfixa
Este é um programa em C que implementa uma calculadora para avaliar expressões matemáticas fornecidas na notação posfixa. Além disso, o programa também traduz as expressões posfixas para a notação prefixa.

# Estrutura do Projeto
O projeto é dividido em três arquivos:

pilha.h: Este arquivo contém as definições de estruturas e protótipos de funções relacionadas às operações de pilha utilizadas no programa.

pilha.c: Aqui estão implementadas as funções definidas em "pilha.h". Estas funções são responsáveis por inicializar uma pilha, realizar operações de empilhamento e desempilhamento, limpar a memória alocada e outras operações auxiliares.

main.c: Este arquivo contém a função principal main. Aqui, são realizados testes com expressões matemáticas, avaliando-as na notação posfixa e exibindo os resultados. Além disso, o programa também traduz as expressões posfixas para a notação prefixa.

# Compilação e Execução
Para compilar o programa, utilize um compilador de C, por exemplo, o GCC:

bash
Copy code
gcc -o calculadora main.c pilha.c -lm
Em seguida, execute o programa gerado:

bash
Copy code
./calculadora
O programa contém casos de teste demonstrando o funcionamento da calculadora com diversas expressões matemáticas.
