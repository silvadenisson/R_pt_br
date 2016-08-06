---
title       : Introdução
description : Neste módulo você vai aprender fazer operações matemáticas no console, criar objetos (variáveis), pedir ajuda, e os principais tipos (classes) de dados.
attachments :

--- type:NormalExercise lang:r xp:10 skills:1,3 key:bc438b12bd
## Operaçoes matemáticas

O exercício é usar o R como Calculadora 

*** =instructions

1.  Some 10 + 20
*** =hint
Just follow the instructions, this should be easy ;-).

 *** =pre_exercise_code
  ```{r}
  10 + 20
 +10 / 2
  ```
  
  *** =sample_code
  ```{r}
  # Some 10 + 20
 +# divida 10 / 2
  ```
  
  *** =solution
  ```{r}
  # Some 10 + 20
  10 + 20
 +20 / 2
  ```
  
  *** =sct
  ```{r}
  test_error()
 -test_operator("+", not_called_msg = "O perador matemátematico para soma errado", ncorrect_msg = "O perador matemátematico para soma não é este")
 -
 -
 -
 -success_msg("Good job! Head over to the next exercise")
 +success_msg("Muito Bom! Siga para o próximo exercício")
  ```
