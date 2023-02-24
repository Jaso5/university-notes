# Arrays

Arrays are declared with the `[]` syntax:

```
x = [1, 2, 3, 4, 5, 6]
y = [1..10] -- [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]
z = "Look Dad, I'm an array too!" -- See Strings section for more information
```

## Array Operations

To get a certain element from an array, use the `!!` operator:

```
Prelude> x = [1..10]
Prelude> x!!5
6
```

You can join arrays using the `++` operator:

```
Prelude> [1, 2, 3] ++ [4, 5, 6]
[1,2,3,4,5,6]
```
## For-Each Array Operations
### Map

Map is used to perform an operation on each element in a function:

```
Prelude> x = [1..10]
Prelude> map (*2) x
[2,4,6,8,10,12,14,16,18,20]
```

### Filter

This is similar to map, however it runs a check, and if that check returns false it removes the element.
Here is an example which only return even elements

```
Prelude> x = [1..10]
Prelude> filter even x -- Even is a function from the standard library, which return true if a number is even
[2,4,6,8,10]
```