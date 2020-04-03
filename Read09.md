
# Refactoring

## What is functional programming?
**Functional programming is a programming paradigm — a style of building the structure and elements of computer programs — that treats 
computation as the evaluation of mathematical functions and avoids changing-state and mutable data**

### How do we know if a function is pure or not? Here is a very strict definition of purity:
* It returns the same result if given the same arguments (it is also referred as deterministic).
* It does not cause any observable side effects.
* Any function that relies on a random number generator cannot be pure.

**Observation: mutability is discouraged in functional programming.**

**Basically, if a function consistently yields the same result for the same input, it is eferentially transparent.**
### pure functions + immutable data = referential transparency

#### Functions as first-class entities can:
* refer to it from constants and variables.
* pass it as a parameter to other functions.
* return it as result from other functions.

**The map method transforms a collection by applying a function to all of its elements and building a new collection from the returned values.**

**The idea of reduce is to receive a function and a collection, and return a value created by combining the items.**

![image](https://i.ytimg.com/vi/Fevz-Kb4bxc/maxresdefault.jpg)
