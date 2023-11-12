# CURSO LET'S CODE


# ESTUDOS: Git

## MODIFICAÇÕES

* comando git push
* comando git pull
* comando git fetch
* comando git staged
* comando git add
* comando git config
* comando git log
* comando git pull
* comando git diff
* comando git remote
* comando git commit

#  ESTUDOS: Algoritmo

## TIPOS DE DADOS

* INICIO Principal

 VAR n1: INTEIRO
 VAR n2: INTEIRO
 VAR Resultado: INTEIRO

  DEFINIR 0 -> n1
 DEFINIR 0 -> n2

 MOSTRAR "Digite o primeiro numero"
 ESPERAR_DIGITACAO -> n1
 MOSTRAR "Digite o segundo numero"
 ESPERAR_DIGITACAO -> n2
 SOMAR n1, n2 -> resultado
 MOSTRAR resultado

FIM

## DECISÃO

* INICIO

mostrar "Digite seu nome"
armazenar o nome na variável NOME
mostrar "Que Horas São?"
armazenar a hora na variável HORA_ATUAL
avaliar valor em HORA_ATUAL

0 a 12
armazenar "Bom Dia" em MENSAGEM

12 a 18
armazenar "Boa Tarde" em MENSAGEM

18 a 24
armazenar "Boa Noite" em MENSAGEM


mostrar MENSAGEM, NOME

FIM

* INICIO Principal

 VAR nome: NERO
 VAR hora: INTEIRO
 VAR mensagem: STRING

  MOSTRAR "Digite seu nome"
 ESPERAR_DIGITACAO -> nome
 MOSTRAR "Digite hora atual (somente a hora)"
 ESPERAR DIGITACAO ->

 SE (hora MAIOR_QUE 0) E (hora MENOR_QUE 12)
    DEFINIR "Bom Dia" -> mensagem
 SE (hora MAIOR_OU_IGUAL_A 12) E (hora MENOR_QUE 18)
    DEFINIR "Boa Tarde" -> mensagem
 SE (hora MAIOR_OU_IGUAL_A 18) E (hora MENOR_QUE 24)
    DEFINIR "Boa Noite" -> mensagem

 MOSTRAR mensagem, nome

FIM

## REPETIÇÃO

* INICIO Principal

 VAR soma: INTEIRO
 ARMAZENAR 0 -> soma
 ENQUANTO soma MENOR QUE 100
   MOSTRAR "Digite um numero"
   ESPERAR DIGITACAO -> numero
   SOMAR soma, numero -> soma
 FIM ENQUANTO
 MOSTRAR soma

FIM

## ARRAYS

* INICIO Principal

  VAR lista_numeros: LISTA (INTEIROS)
  VAR numero_atual: INTEIRO

  DEFINIR 1 -> numero_atual

  ENQUANTO (QUANTIDADE_ITENS(lista_numeros) MENOR QUE 20)
    SE (RESTO(DIVISAO(numero_atual, 2)) IGUAL A 0) OU (RESTO(DIVISAO(numero_atual, 5)) IGUAL A 0)
    ADICIONAR_ITEM numero_atual, lista_numeros
  FIM SE
  DEFINIR numero_atual +1 -> numero_atual

 FIM ENQUANTO

 MOSTRAR lista_numeros

  PARA CADA item EM lista_numeros
   SE (RESTO(DIVISAO(item, 2)) IGUAL A 0)
     MOSTRAR "Numero", item, " é par"
   SENAO
     MOSTRAR "Numero", item, " é impar"
   FIM SE
 FIM PARA

FIM

##  FUNÇÕES

*  INICIO principal

   VAR lista_numeros: ARRAY(INTEIROS)
   MOSTRAR "Vamos obter os números: "
   CHAMAR OBTER_NUMEROS -> lista_numeros
   MOSTRAR "Agora, mostrar os números: "
   MOSTRAR lista_numeros

FIM

 INICIO OBTER_NUMEROS
   VAR lista_numeros_func: ARRAY(INTEIROS)
   VAR numero: INTEIRO
   EQUANTO TAMANHO (lista_numeros) MENOR_QUE 10
     MOSTRAR "Digite um numero"
     ESPERAR DIGITACAO -> numero
     ADICIONAR_ITEM  numero, lista_numeros_func
   FIM ENQUANTO
   RETORNAR lista_numeros_func
FIM OBTER_NUMEROS


