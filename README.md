# Estudos: Git

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

#  Estudos: Algoritmos

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