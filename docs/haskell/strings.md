# Strings

A string in Haskell may be represented by an array of characters `[Char]`.

```
Prelude> x = "Hello world!"
Prelude> :type x
x :: [Char]
```

Using `"abc"` is just shorthand for `['a', 'b', 'c']`

```
Prelude> "abc" == ['a', 'b', 'c']
True
```