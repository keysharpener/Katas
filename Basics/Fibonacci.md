# The [Fibonacci](https://en.wikipedia.org/wiki/Fibonacci_number) sequence

### Code an algorithm returning the first n numbers of the fibonacci sequence

The fibonacci sequence is a series of number, initialized with 1 and 1, which returns the sum of the two previous values.

Your goal is to code a method with an n parameter, returning a given number of terms.

```csharp
IEnumerable<int> GetFibonacciSequence(int numberOfTerms) {...}
```

For example : 
```csharp
var result = GetFibonacciSequence(7);
result == [1, 1, 2, 3, 5, 8, 13];
```
