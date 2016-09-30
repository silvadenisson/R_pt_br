---
title       : Introdução
description : Neste módulo, você vai aprender a trabalhar no console do R, realizando operações matemáticas e estatísticas básicas, criando objetos (vetores, ou variáveis), pedindo ajuda e identificando os principais tipos (classes) de dados. Ao fim deste modulo, você estará apto a compreender como o R armezana os principais tipos de informações na memória, a criar e modificar objetos e a relizar operações e procedimentos matemáticos e estatísticos básicos.
attachments :


--- type:NormalExercise  key:0e15c986b4
## Apresentação

O objetivo principal deste curso é introduzir a linguagem de programação R para uso científico -- embora ele também seja útil para quem quer aprender ou se aprofundar no R. 

O curso tem uma abordagem prática: cada exercício pede um código para realizar uma tarefa. Caso a resposta não esteja certa, é possível refazer o exercício, estudar melhor as instruções e submeter novamente a resposta. No fim, cada resposta certa gerará um número de pontos, que permitem avaliar como você está se saindo.

Os principais conteúdos abordados são direcionados para o uso prático do R. Entre outros, o curso aborda como manipular variáveis numéricas, categóricas e texto, bem como resumir e examinar estas informações. Ao fim dele, esperamos que você esteja pronto para usar o R para realizar suas próprias pesquisas e análises de dados.

Agora chega de enrolação. Para começar, basta clicar no botão "Got it!", abaixo.

--- type:NormalExercise lang:r xp:5 skills:1,3 key:bc438b12bd
## Instruções Iniciais

Nesta coluna ao seu lado esquerdo ficarão as instruções das atividades a serem realizadas. Ao lado deireito desta, há mais duas abas: uma chamada "script.R", onde você vai digitar a resposta do exercício; e "R Console", que apresentará o resultado após clicar em "Submit Answer". Tudo como se você estivesse utilizando o R instalado no seu computador.

Na aba esqueda, abaixo de "Instructions", é possível pedir dicas sobre como realizar o exercício (cuidado: cada vez que você clicar nestes botões você terá pontos subtraídos; a ideia é que você tente realizar os exercícios para aprender).

Tudo o que vier seguido do símbolo "#" no script.R é um comentário, ou seja, não será interpredado como parte do seu código. Observe isto no script.R

Para começar a aprender e pular para o próximo exercício, basta clicar em "Submit Answer".

*** =sample_code
  ```{r}
# No R, toda linha em um scrip iniciado por # e' um comentario.


# Isto significa que tudo o que vier depois de # nao sera' executado. Comentários:

# - Ajudam a organizar o codigo;
# - Permitem comentar o que cada parte do codigo faz;
# - Facilitam a tarefa de replicar e publicizar um codigo.

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
  
