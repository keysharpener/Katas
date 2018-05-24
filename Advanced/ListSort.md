# List Sorting

Without using Linq, write a function that returns an ordered enumerable of integers from an unordered one

Example :
```csharp
IEnumerable<int> unordered = new List<int>{1,5,2,10}();
IEnumerable<int> ordered = Sort();
ordered == [1,2,5,10]
```