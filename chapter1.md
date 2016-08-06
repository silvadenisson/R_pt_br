---
title       : Introdução
description : Neste módulo você vai aprender fazer operações matemáticas no console, criar objetos (variáveis), pedir ajuda, e os principais tipos (classes) de dados.
attachments :

--- type:NormalExercise lang:r xp:100 skills:1,3 key:bc438b12bd
## Operaçoes matemáticas

O exercício é usar o R como Calculadora 

*** =instructions

1. Type `2^5` in the editor to calculate 2 to the power 5.
2. Type `17%%4` to calculate 17 modulo 4.
3. Click Submit Answer and have a look at the R output in the console.
4. Note how we use the `#` symbol to give comments on certain lines.

*** =hint
Just follow the instructions, this should be easy ;-).

*** =sample_code
```{r eval=FALSE}
# An addition
5+5 

# A substraction
5-5 

# A multiplication
3*5

 # A division
(5+5)/2 

# Exponentiation
# Add your code here!

# Modulo
# Add your code here!
```

*** =solution
```{r eval=FALSE}
# An addition
5+5 

# A substraction
5-5 

# A multiplication
3*5

 # A division
(5+5)/2 

# Exponentiation
# Add your code here!
2^5
# Modulo
# Add your code here!
17%%4
```

*** =sct
```{r eval=FALSE}
DM.result <- code_test( c("17%%4","2^5") )
```

*** =pre_exercise_code
```{r eval=FALSE}

```
