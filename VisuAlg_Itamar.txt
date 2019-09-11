Algoritmo "adivinhacao_da_idade"

Var
// Seção de Declarações das variáveis 
    anocorrente: inteiro
    dif250: inteiro
    resultado: real
    jafezaniversario: inteiro
Inicio
// Seção de Comandos, procedimento, funções, operadores, etc... 
   escreval ("Esta é uma brincadeira de adivinhação e só funciona para quem tem até 99 anos.")
// Perguntar ao participnte qual o ano corrente
   escreval ("Estamos em qual ano corrente (2018, 2019, ..., aaaa)?")
   leia (anocorrente)
   escreval ("Se você já fez aniversário este ano, digite 1; senão, digite 2: ")
   leia (jafezaniversario)
// Bloco de laço de repetição
   enquanto (jafezaniversario <>1) e (jafezaniversario <>2) faca
            escreval ("==> Você tem que responder 1 ou 2. <==")
            escreval ("Se você já fez aniversário este ano, digite 1; senão, digite 2: ")
            leia (jafezaniversario)
   fimenquanto
// Bloco de condição
   se (jafezaniversario) = 1 entao
      dif250 <- anocorrente - 250
   fimse
// Bloco de condição
   se jafezaniversario = 2 entao
      dif250 <- anocorrente - 251
   fimse
// Bloco das continhas
   escreval ("Chegou a hora de fazer umas continhas:")
   escreval ("Pensar um número inteiro entre 1 e 9 e anotá-lo para não esquecer.")
   escreval ("Multiplicar por 2 o número que foi pensado.")
   escreval ("Somar 5 ao resultado encontrado.")
   escreval ("Multiplicar por 50 esse novo resultado.")
   escreval ("Somar ",dif250," a esse novo total encontrado.")
   escreval ("Subtrair o ano de seu nascimento desse novo resultado encontrado.")
   escreval ("")
   escreval ("Agora, informe o resultado que você encontrou:")
   leia (resultado)
   escreval ("")
   escreval ("*** Vamos analisar o número ",resultado," que você encontrou ***")
   escreval ("")
   escreval ("=>Muito provavelmente ele contém três algarismos")
   escreval ("=>O algarismo da esquerda é o número que você pensou")
   escreval ("=>Os dois outros informam sua idade")
   escreval ("")
   escreval ("=> Acertei?")
   escreval ("")
   escreval ("*** Fim da brincadeira ***")
 
Fimalgoritmo