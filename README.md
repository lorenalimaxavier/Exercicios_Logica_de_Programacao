algoritmo "viagemdolar"
var
   reais, dolares, taxa: Real

inicio
      Escreva("Quantos reais eu tenho? R$")
      Leia(reais)
      Escreva("Valor do dolar: ")
      Leia(taxa)
      dolares <- reais/taxa
      Escreva("Posso ter US$ ", dolares)
fimalgoritmo
