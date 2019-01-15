# lambda calculus

The lambda calculus is a minimalistic language that is in the core of functional programming.

# acknowledgements

This module is based upon by work by [Gil Mizrahi](https://github.com/soupi). 

# study

It presents a minimalistic framework to learn about many common features in functional languages.

- [Use this tutorial to learn about the lambda calculus](http://www.inf.fu-berlin.de/lehre/WS03/alpi/lambda.pdf)
- [Wikipedia article on the Lambda Calculus](https://en.wikipedia.org/wiki/Lambda_calculus)

# exercises

1. Reduce the following expressions to normal form using pen and paper

```
a. ~λx. x~
b. ~(λx. x) y~
c. ~(λx. x x) (λy. y)~
d. ~(λw. λx. λz. x w z) a (λb. λc. c b) (λd. d)~
```

2. Use eta conversion on the following expression

```
a. ~λx. f x~
b. ~λf. λy. (λx. f x) y~
```

3. Write the expression `~2 + 3~` in the lambda calculus and evaluate it using pen and paper
4. Write the expression `~factorial 5~` in the lambda calculus and evaluate it using pen and paper

Use this [Lambda Machine](http://cdparks.github.io/lambda-machine/) to check your answers
