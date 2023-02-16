## Basic Operators | Connectives

> `Negative`, `NOT` => `┐`, `~`, `not`

> `AND` => `^`, `&`, `&&`, `and`
 
> `OR` => `v`, `|`, `or`   (Disjunction)
 
> `XOR` => `⊕`, `xor`

## Atomic Propositions
These are the most core **truths** we have, and **cannot be broken down**:

> The Apple is Red

> 1 + 2 = 3

We also have **boolean** propositions:

> `t, T, 1, T` => **True**

> `f, F, 0, ┴` => **False**

## Compound Propositions

Built from **Connectives**, we can create more complex statements.

Given:
> `A: Is a Honda Civic`

> `B: Is colored Silver`

We can then say that:

> `X: A ^ B`

therefore: *`X` ***is*** silver ***and a*** Honda Civic*

We also have ***equality***:

> `(p v q) ^ q ≡ q`

In this statement, we can assert that the left side evaluates to `q`, so they are equal and may be shortened.

## Implication

> If `X` then `Y` ...

This is not a `if X then Y else Z` as that would be a boolean proposition, this is instead a **Process**

> `p -> q`

|  X  |  Y  |  Result  |
| :-: | :-: |   :--:   |
|  0  |  0  |    1     |
|  1  |  0  |    0     |
|  0  |  1  |    1     |
|  1  |  1  |    1     |

<br>
Based on the truth table you can see:

> Base result is `True`  
> If `X` is true, it **overrides the result** with `Y`

## Propositions

Lets start with a basic proposition and break it down:
> `a(x): x => a(x) is x`


`a(x):` => `a(x)` is equal to `Expression`  
`x =>`  => x