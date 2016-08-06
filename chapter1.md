---
title       : Introdução
description : Neste módulo você vai aprender fazer operações matematica no console, criar objetos (variáveis), pedir ajuda, e os principais tipos (classes) de dados.
attachments :

--- type:NormalExercise lang:r xp:100 skills:1,3 key:bc438b12bd
## Interactive Exercise Title

This basic exercise will challenge you to assign a variable in R.

*** =instructions
- Assign `5` to the variable `x` in the editor on the right.

*** =hint
Use `<-` for assignment.

*** =pre_exercise_code
```{r}
y <- 3
```

*** =sample_code
```{r}
# Assign 5 to the variable x
```

*** =solution
```{r}
# Assign 5 to the variable x
x <- 5
```

*** =sct
```{r}
test_error()
test_object("x",
            undefined_msg = "Make sure to define `x`!",
            incorrect_msg = "Have you correctly assigned 5 to `x`!")
success_msg("Good job! Head over to the next exercise")
```

