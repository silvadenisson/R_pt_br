---
title       : Introdução
description : Neste módulo você vai aprender fazer operações matemáticas no console, criar objetos (variáveis), pedir ajuda, e os principais tipos (classes) de dados.
attachments :

--- type:NormalExercise lang:r xp:0 skills:1,3 key:bc438b12bd
## Intruções Iniciais

Na coluna ao seu lado esquerdo ficam as instruções das atividades a serem realizadas


--- type:NormalExercise lang:r xp:40 skills:1,3 key:eb2fcab07b
## Operações matemáticas

O exercício é usar o R como Calculadora 

Escreva a solução correta no scrip.R no lado direito e submeta a resposta (Submit Answer).

Obs. Linhas iniciadas com `#` no R significa que é um comentário e ele não vai ententer como uma operacao a ser relaizada.

*** =instructions
1.  Some 10 + 20
2.  Divida 20 / 5
3.  Multiplique 7 * 4
4.  Subtraia 70 - 19
*** =hint
Basta seguir as instruções ;-).

 *** =pre_exercise_code
  ```{r}
  10 + 20
  20 / 5
  7 * 4
  70 - 19
  ```
  
  *** =sample_code
  ```{r}
  # Some 10 + 20
  ```
  
  *** =solution
  ```{r}
  # Some 10 + 20
  10 + 20
  # Divida 20 / 5
  20 / 5
  # Multiplique 7 * 4
  7 * 4
  # Subtraia 70 - 19
  70 - 19
  ```
  
  *** =sct
  ```{r}
  test_error()
  test_output_contains(c("30","4","28","51"), incorrect_msg = "Resposta incorreta para pelo menos uma das operacoes, corrija e resubmeta")
  success_msg("Muito Bom! Siga para o proximo exercicio")
  ```
  
