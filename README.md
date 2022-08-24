

# Gabriel Gava Pinheiro, Vitor Leandro Machado, Samuel Pereira Cunha, Rafael Yuki Tobaru

#Atividade 1
Descubra o maior e menor numero dentro de um um vetor

Input: [1,2,10,20,19,20]

Output: [20,1]

------------------------------------------//----------------------------

#Atividade 2

Some todos os elementos de um array 

Input [1,2,3,4]

Output: 10

R: Algoritmo "Atividade 2"
// Descrição   : Soma dos elementos de um Array de 4 elementos
// Autor(a)    : Rafael Yuki Tobaru
// Data atual  : 24/08/2022

Var
array : vetor[0..3] de inteiro
i, soma : inteiro

Inicio
soma <- 0
para i <- 0 ate 3 passo 1 faca
   escreva("Informe um Número (", i, " / 4 ): ")
   leia(array[i])
   soma <- soma + array[i]
fimpara
escreva("Soma dos Elementos do Array: ", soma)
Fimalgoritmo
------------------------------------------//----------------------------

#Atividade 3

Pife Numero divisiveis por 5 tem que ser dito pife

Input [1,2,3,4,5]

Output : 
         pife
         2
         3
         4
         pife
         
Resposta:
var
i : inteiro

inicio
// Seção de Comandos
i <- 0
enquanto (i < 100) faca
         i <- i + 1
         se (i mod 2 <> 0) entao
            escreval("PIFE!")
         senao
              escreval(i)
         fimse
fimenquanto

fimalgoritmo

------------------------------------------//----------------------------

Atividade 4 
Crie um função que retorne a area de um triangulo formula B.h/2

Resposta:
var
 altura, area, base : real
inicio
// Seção de Comandos
escreva("Digite o valor do altura: ")
    leia(altura)
    escreva("Digite o valor do base: ")
    leia(base)
    area <- base*altura/2
    escreval("O valor do area: ", area:0:6)
fimalgoritmo


------------------------------------------//----------------------------






