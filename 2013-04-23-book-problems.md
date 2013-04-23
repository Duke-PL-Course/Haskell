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
