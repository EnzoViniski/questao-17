Algoritmo "NumeroPar"

var
   n1, n2, divi:real
   
inicio
   //Entrada de dados
   escreva("Digite um número: ")
   leia(n1)
   
   escreva("Digite mais um número: ")
   leia(n2)
   
   //Verificação
   divi <- n1 % 2
   se divi > 0 entao
      escreva("O PRIMEIRO NUMERO NAO E PAR")
   senao
      enquanto (n2 > 0) faca
      escreval( n1 )
      n1 <- (n1 + 2)
      n2 <- (n2 - 1)
      fimenquanto
   fimse
fimalgoritmo
      
