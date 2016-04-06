# bccploya


Descrição: O objetivo deste programa é calcular o resultado aproximado, ou exato da raiz quadrada.


Abaixo segue o código em .C

#include<stdio.h>
#include<stdlib.h>
#include<math.h>
int main(){
   int a;
   float b;
   printf("Digite o valor: ");
   scanf("%d",&a);
   b = sqrt(a);
   printf("A raiz de %d = %.2f",a,b);
   getchar();
  getchar();
}



Abaixo segue a solução em Português Estruturado (Portugol)

Algoritmo "Calcula raiz quadrada"
//  
//  
// Descrição   : O objetivo deste programa é calcular o resultado aproximado, ou exato da raiz quadrada.
// Autor    : Thiago Barbosa Torres Brasil
// Data atual  : 06/04/2016
Var
// Seção de Declarações das variáveis 
   a: real
   b: inteiro

Inicio
// Seção de Comandos, procedimento, funções, operadores, etc... 

   escreval ("==============================================")
   escreval ("======                                  ======")
   escreval ("======  Algoritmo Calcula raiz quadrada ======")
   escreval ("======                                  ======")
   escreval ("==============================================")
   escreval ("")
   escreva("         Digite o valor: ")
   leia(a)
   escreva("         A raiz quadrada de ", a, " = ", raizq(a): 1:2)

Fimalgoritmo



Abaixo, segue a justificativa do uso do termo "polya" no nome do repositório.

Polya formulou quatro etapas essenciais para a resolução de problemas, onde baseia-se em: 

*Compreender o problema;

*Traçar um plano;

*Colocar o plano em prática;

*Comprovar os resultados.

Resumindo, todo o esforço que foi feita para resovler o exercício passado foi feito em cima da ideia de George Polya.
tivemos que compreender o que foi passado, traçamos um plano de como resolver o exercício, colcoamos o plano em prática por meio dos testes realizados e, por fim, comprovamos os resultados compilando o código.

