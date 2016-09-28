---
title       : Introdução
description : Neste módulo, você vai aprender a trabalhar no console do R, realizando operações matemáticas e estatísticas básicas, criando objetos (vetores, ou variáveis), pedindo ajuda e os principais tipos (classes) de dados. Ao fim deste modulo, você estará apto a compreender como o R armezana os principais tipos de informações na memória, a criar e modificar objetos e a relizar operações e procedimentos básicamos de matemática e estatística.
attachments :


--- type:VideoExercise lang:r aspect_ratio:62.5 skills:1 key:0e15c986b4
## Apresentação

*** =video_link
//player.vimeo.com/video/108225030



--- type:NormalExercise lang:r xp:5 skills:1,3 key:bc438b12bd
## Instruções Iniciais

Nesta coluna ao seu lado esquerdo ficarão as instruções das atividades a serem realizadas. Ao lado deireito desta há mais duas abas. Uma chamada "script.R" onde você vai digitar a resposta do exercício e "R Console" que vai apresentar o resultado após clicar em "Submit Answer" igual ao se você estivesse utilizanbdo o R instalado no seu computador.

Quando aparecer o símbolo "#" no script.R siginifica que é um comentário, ou seja, não será interpredado como parte do seu código.
Observe no script.R

para começar a aprender mais sobre o R basta clicar em "Submit Answer"

*** =sample_code
  ```{r}
 # No R, toda linha em um scrip iniciado por # e' um comentario.


# Isto significa que tudo o que vier depois de # nao sera' executado.

# - Eles ajudam a organizar o codigo;
# - Eles permitem comentar o que cada parte do codigo faz;
# - Eles facilitam a tarefa de replicar e publicizar um codigo.

# Sempre faca comentarios. Mas chega de comentarios por enquanto.
  ```
  
--- type:NormalExercise lang:r xp:40 skills:1,3 key:eb2fcab07b
## Operações matemáticas

O exercício é usar o R como Calculadora 

Escreva a solução correta no script.R no lado direito e submeta a resposta (Submit Answer).

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
  
