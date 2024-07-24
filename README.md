# Performance Wars Benchmarking - C\#

This repository contains a collection of C# benchmarks to compare the performance of different approaches to solve the same problem.

1. [List.TrimExess() Benchmark](https://github.com/mjebrahimi/Performance-Wars-Benchmarking-CSharp/tree/master/List-TrimExess-Benchmark)
2. [for vs foreach vs ForEach() Benchmark](https://github.com/mjebrahimi/Performance-Wars-Benchmarking-CSharp/tree/master/For-ForEach-Benchmark)
3. [Reflection/Class vs NonReflection/Struct Benchmark](https://github.com/mjebrahimi/Performance-Wars-Benchmarking-CSharp/tree/master/Reflection-NonReflection-Benchmark)
4. [Normal flow vs Throw Exception Benchmark](https://github.com/mjebrahimi/Performance-Wars-Benchmarking-CSharp/tree/master/Throw-Exception-Benchmark)
5. [String Replace Benchmark](https://github.com/mjebrahimi/Performance-Wars-Benchmarking-CSharp/tree/master/String-Replace-Benchmark)
6. [Ctor Instantiate vs Lazy Instantiaten](https://github.com/mjebrahimi/Performance-Wars-Benchmarking-CSharp/tree/master/New-Lazy-Instantiate)
7. [Prometheus-net metrics Benchmark](https://github.com/mjebrahimi/Performance-Wars-Benchmarking-CSharp/tree/master/Metrics-Benchmark)
8. [PropertyGetter Benchmark](https://github.com/mjebrahimi/Performance-Wars-Benchmarking-CSharp/tree/master/Property-Getter-Benchmark)
9. [Reverse string Benchmark](https://github.com/mjebrahimi/Performance-Wars-Benchmarking-CSharp/tree/master/String-Reverse-Benchmark)
10. [Concat string Benchmark](https://github.com/mjebrahimi/Performance-Wars-Benchmarking-CSharp/tree/master/String-Concat-Benchmark)
11. [Word reverse Benchmark](https://github.com/mjebrahimi/Performance-Wars-Benchmarking-CSharp/tree/master/Word-Reverse-Benchmark)
12. [OrderBy.First/Last vs Min/Max Benchmark](https://github.com/mjebrahimi/Performance-Wars-Benchmarking-CSharp/tree/master/OrderByFirstLast-MinMax-Benchmark)
13. [Collection Shuffle Benchmark](https://github.com/mjebrahimi/Performance-Wars-Benchmarking-CSharp/tree/master/Collection-Shuffle-Benchmark)
14. [FileStream Write vs WriteAsync Benchmark](https://github.com/mjebrahimi/Performance-Wars-Benchmarking-CSharp/tree/master/FileStream-WriteAsync-Benchmark)
15. [Stream Read Bytes Benchmark](https://github.com/mjebrahimi/Performance-Wars-Benchmarking-CSharp/tree/master/Stream-Read-Bytes-Benchmark)
16. [Stream Write Bytes Benchmark](https://github.com/mjebrahimi/Performance-Wars-Benchmarking-CSharp/tree/master/Stream-Write-Bytes-Benchmark)
17. [Stream Read String Benchmark](https://github.com/mjebrahimi/Performance-Wars-Benchmarking-CSharp/tree/master/Stream-Read-String-Benchmark)
18. [Array Allocating Benchmark](https://github.com/mjebrahimi/Performance-Wars-Benchmarking-CSharp/tree/master/Array-Allocating-Benchmark)
19. [Array Resizing Benchmark](https://github.com/mjebrahimi/Performance-Wars-Benchmarking-CSharp/tree/master/Array-Resizing-Benchmark)
20. [String StartWith Benchmark](https://github.com/mjebrahimi/Performance-Wars-Benchmarking-CSharp/tree/master/String-StartWith-Benchmark)
21. [GetHashCode and Equals Benchmark](https://github.com/mjebrahimi/Performance-Wars-Benchmarking-CSharp/tree/master/GetHashCode-Equals-Benchmark)
22. [Enumerable NullOrEmpty Benchmark](https://github.com/mjebrahimi/Performance-Wars-Benchmarking-CSharp/tree/master/Enumerable-NullOrEmpty-Benchmark)
23. [.NET Collections Benchmark](https://github.com/mjebrahimi/DotNet-Collections-Benchmark/)⭐️
24. [Converting Enum To String Benchmark](https://github.com/mjebrahimi/Performance-Wars-Benchmarking-CSharp/tree/master/Convert-Enum-To-String-Benchmark)
25. [Array Copy Benchmark](https://github.com/mjebrahimi/Performance-Wars-Benchmarking-CSharp/tree/master/Array-Copy-Benchmark)
26. [String Find First Duplicate Char Benchmark](https://github.com/mjebrahimi/Performance-Wars-Benchmarking-CSharp/tree/master/String-FirstDuplicateChar-Benchmark)
27. [Convert Number To Base62 String Benchmark](https://github.com/mjebrahimi/Performance-Wars-Benchmarking-CSharp/tree/master/Convert-To-Base62-Benchmark)
28. [MediatR vs Mediator vs SlimMediator Benchmark](https://github.com/mjebrahimi/Performance-Wars-Benchmarking-CSharp/tree/master/Mediators-Benchmark)
29. [AggressiveInlining Benchmark](https://github.com/mjebrahimi/Performance-Wars-Benchmarking-CSharp/tree/master/AggressiveInlining-Benchmark)
30. [New Instantiate Benchmark](https://github.com/mjebrahimi/Performance-Wars-Benchmarking-CSharp/tree/master/New-Instantiate-Benchmark)

## TODO

Some ideas for future benchmarks:

- [ ] [SearchValues](https://learn.microsoft.com/en-us/dotnet/api/system.buffers.searchvalues-1) vs Regex and other Alternatives
- [ ] [UnsafeAccessor](https://learn.microsoft.com/en-us/dotnet/api/system.runtime.compilerservices.unsafeaccessorattribute) vs Reflection-Based Access
- [ ] [Source Generated Regex](https://learn.microsoft.com/en-us/dotnet/api/system.runtime.compilerservices.unsafeaccessorattribute) vs Regular Regex (in various manner: static, instance, compiled, ...)

## Contributing

Create an [issue](https://github.com/mjebrahimi/Performance-Wars-Benchmarking-CSharp/issues/new) or [discussion](https://github.com/mjebrahimi/Performance-Wars-Benchmarking-CSharp/discussions/new/choose) if you found a **Mistake** or have a **Suggestion**.

**Or if you want to add more benchmarks to this project:**

1. Fork it
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request

## Useful Resources

- https://github.com/martinstm/benchmarks
- https://github.com/MarkCiliaVincenti/AsyncKeyedLockBenchmarks
- https://github.com/MarkCiliaVincenti/AsyncNonKeyedLockBenchmarks
