# Haskell

## Day 1: Logical

### Find

* [The Haskell wiki](http://www.haskell.org/haskellwiki/Haskell)
* A Haskell online group supporting your compiler of choice

    [GHCI](http://www.haskell.org/haskellwiki/GHC/GHCi)

### Do

* How many different ways can you find to write allEven?
* Write a function that takes a list and returns the same list in reverse.
* Write a function that builds two-tuples with all possible combinations of two of the colors black, white, blue, yellow, and red. Note that you should include only one of (black, blue) and (blue, black).
* Write a list comprehension to build a childhood multiplication table. The table would be a list of three-tuples where the first two are integers from 1–12 and the third is the product of the first two.
* Solve the map-coloring problem using Haskell.

    In Prolog

    ```Prolog
    different(red, green). different(red, blue).
    different(green, red). different(green, blue).
    different(blue, red). different(blue, green).

    coloring(Alabama, Mississippi, Georgia, Tennessee, Florida) :- 
      different(Mississippi, Tennessee),
      different(Mississippi, Alabama),
      different(Alabama, Tennessee),
      different(Alabama, Mississippi),
      different(Alabama, Georgia),
      different(Alabama, Florida),
      different(Georgia, Florida),
      different(Georgia, Tennessee).
    ```

---

## Day 2: Spock's Great Strength

### Find

* Functions that you can use on lists, strings, or tuples

    [List](http://www.haskell.org/ghc/docs/latest/html/libraries/base/Data-List.html)
    [String](http://www.haskell.org/ghc/docs/latest/html/libraries/base/Data-String.html#t:String)
    [Tuple](http://www.haskell.org/ghc/docs/latest/html/libraries/base/Data-Tuple.html#t:String)

* A way to sort lists

    [`sort`](http://www.haskell.org/ghc/docs/latest/html/libraries/base/Data-List.html#g:21)
    [`sortBy`](http://www.haskell.org/ghc/docs/latest/html/libraries/base/Data-List.html#v:sortBy)

### Do

* Write a sort that takes a list and returns a sorted list.
* Write a sort that takes a list and a function that compares its two argu- ments and then returns a sorted list.
* Write a Haskell function to convert a string to a number. The string should be in the form of $2,345,678.99 and can possibly have leading zeros.
* Write a function that takes an argument x and returns a lazy sequence that has every third number, starting with x. Then, write a function that includes every fifth number, beginning with y. Combine these functions through composition to return every eighth number, beginning with x + y.
* Use a partially applied function to define a function that will return half of a number and another that will append \n to the end of any string.

### Bonus

* Write a function to determine the greatest common denominator of two integers.
* Create a lazy sequence of prime numbers.
* Break a long string into individual lines at proper word boundaries.
* Add line numbers to the previous exercise.
* To the above exercise, add functions to left, right, and fully justify the text with spaces (making both margins straight).