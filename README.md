# C# and .NET Roadmap for Beginners

This document contains a simplified list of concepts to guide new developers through learning the basics of the C# programming language, and a brief introduction to the .NET ecosystem.

## C#

- Learn the Fundamentals
  - [Basic Syntax](https://docs.microsoft.com/en-us/dotnet/csharp/tour-of-csharp/tutorials/hello-world)
  - [Variables](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/language-specification/variables) and [Data Types](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types)
    - [String](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/reference-types)
    - [Int](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/integral-numeric-types)
    - [Boolean](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/bool)
    - [Float/Double/Decimal](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/floating-point-numeric-types)
    - [Var](https://docs.microsoft.com/en-us/dotnet/csharp/fundamentals/types/anonymous-types)
  - [Conditionals](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/statements/selection-statements)
  - [Methods](https://docs.microsoft.com/en-us/dotnet/csharp/methods)
  - [Collections](https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/concepts/collections)
    - [List](https://docs.microsoft.com/en-us/dotnet/api/system.collections.generic.list-1)
    - [Dictionary](https://docs.microsoft.com/en-us/dotnet/api/system.collections.generic.dictionary-2)
    - [Array](https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/arrays/)
  - [Loops](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/statements/iteration-statements)
  - [Namespaces](https://docs.microsoft.com/en-us/dotnet/csharp/fundamentals/types/namespaces)
  - [Using directives](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/keywords/using-directive)
  - [String Interpolation](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/tokens/interpolated)
- Object-Oriented Programming
  - Three Pillars
    - [Encapsulation](https://docs.microsoft.com/en-us/dotnet/csharp/fundamentals/object-oriented/)
      - [Classes](https://docs.microsoft.com/en-us/dotnet/csharp/fundamentals/types/classes)
      - [Structs](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/struct)
      - [Records](https://docs.microsoft.com/en-us/dotnet/csharp/fundamentals/types/records)
    - [Inheritance](https://docs.microsoft.com/en-us/dotnet/csharp/fundamentals/object-oriented/inheritance)
      - [Interfaces](https://docs.microsoft.com/en-us/dotnet/csharp/fundamentals/types/interfaces)
      - [Abstract classes](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/keywords/abstract)
    - [Polymorphism](https://docs.microsoft.com/en-us/dotnet/csharp/fundamentals/object-oriented/polymorphism)
      - [Virtual](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/keywords/virtual)
      - [Override](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/keywords/override)
      - [Using Base Classes](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/keywords/base)
  - [Access Modifiers](https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/classes-and-structs/access-modifiers)
    - [Public](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/keywords/public)
    - [Private](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/keywords/private)
    - [Internal](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/keywords/internal)
    - [Protected](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/keywords/protected)
- Intermediate
  - [Enums](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/enum)
  - [Object and Collection initializers](https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/classes-and-structs/object-and-collection-initializers)
  - [Lambdas](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/operators/lambda-expressions)
    - ["=>" Operator](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/operators/lambda-operator)
    - [Arrow Functions](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/operators/lambda-expressions)
  - [Asynchronous Programming](https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/concepts/async/)
    - [Tasks](https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/concepts/async/)
    - [Async](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/keywords/async)
    - [Await](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/operators/await)
  - [Exception Handling](https://docs.microsoft.com/en-us/dotnet/csharp/fundamentals/exceptions/exception-handling)
  - [Linq](https://docs.microsoft.com/en-us/dotnet/csharp/linq/)
  - [Generics](https://docs.microsoft.com/en-us/dotnet/csharp/fundamentals/types/generics)
  - Immutability
    - [Readonly](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/keywords/readonly)
    - [Const](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/keywords/const)
  - [Static](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/keywords/static)
  - [Tuples](https://learn.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/value-tuples)
  - [Nullability](https://learn.microsoft.com/en-us/dotnet/csharp/nullable-references)
  - [Randomness](https://learn.microsoft.com/en-us/dotnet/api/system.random?view=net-7.0)
  - [Casting](https://learn.microsoft.com/en-us/dotnet/csharp/programming-guide/types/casting-and-type-conversions)
  - [Overflow](https://learn.microsoft.com/en-us/dotnet/csharp/language-reference/statements/checked-and-unchecked)
- Advanced
  - [Extension Methods](https://learn.microsoft.com/en-us/dotnet/csharp/programming-guide/classes-and-structs/extension-methods)
  - [Expression Trees](https://learn.microsoft.com/en-us/dotnet/csharp/advanced-topics/expression-trees/)
  - [Reflection](https://learn.microsoft.com/en-us/dotnet/csharp/advanced-topics/reflection-and-attributes/)
  - [Nested Types](https://learn.microsoft.com/en-us/dotnet/csharp/programming-guide/classes-and-structs/nested-types)
  - [Events](https://learn.microsoft.com/en-us/dotnet/csharp/programming-guide/events/)
  - [Delegates](https://learn.microsoft.com/en-us/dotnet/csharp/programming-guide/delegates/)
    - [Func<>](https://learn.microsoft.com/en-us/dotnet/api/system.func-2?view=net-7.0)
    - [Action<>](https://learn.microsoft.com/it-it/dotnet/api/system.action-1?view=net-7.0)
    - [Predicate<>](https://learn.microsoft.com/it-it/dotnet/api/system.predicate-1?view=net-7.0)
   
## .NET

- [Introduction](https://learn.microsoft.com/en-us/dotnet/core/introduction)
  - [.NET Languages](https://learn.microsoft.com/en-us/dotnet/fundamentals/languages)
  - [.NET Implementations](https://learn.microsoft.com/en-us/dotnet/fundamentals/implementations)
  - [.NET Class Libraries](https://learn.microsoft.com/en-us/dotnet/standard/class-libraries)
  - [.NET Standard](https://learn.microsoft.com/en-us/dotnet/standard/net-standard?tabs=net-standard-1-0)
  - [.NET Releases](https://learn.microsoft.com/en-us/dotnet/core/releases-and-support)
  - [.NET CLI](https://learn.microsoft.com/en-us/dotnet/core/tools/)
- Runtime libraries
  - [Overview](https://learn.microsoft.com/en-us/dotnet/standard/runtime-libraries-overview)
  - [Regular Expressions](https://learn.microsoft.com/en-us/dotnet/standard/base-types/regular-expressions)
  - [Serialization](https://learn.microsoft.com/en-us/dotnet/standard/serialization/)	
  - [File and Stream I/O](https://learn.microsoft.com/en-us/dotnet/standard/io/)
  - [File globbing](https://learn.microsoft.com/en-us/dotnet/core/extensions/file-globbing)
  - [Console apps](https://learn.microsoft.com/en-us/dotnet/standard/building-console-apps)
  - [Dependency Injection](https://learn.microsoft.com/en-us/dotnet/core/extensions/dependency-injection)
  - [Configuration](https://learn.microsoft.com/en-us/dotnet/core/extensions/configuration)
  - [Logging](https://learn.microsoft.com/en-us/dotnet/core/extensions/logging?tabs=command-line)
  - [.NET Host](https://learn.microsoft.com/en-us/dotnet/core/extensions/generic-host)
  - [Networking](https://learn.microsoft.com/en-us/dotnet/fundamentals/networking/overview)
  - [Primitives](https://learn.microsoft.com/en-us/dotnet/core/extensions/primitives)
  - [Globalization and localization](https://learn.microsoft.com/en-us/dotnet/core/extensions/globalization-and-localization)
  - [Resources](https://learn.microsoft.com/en-us/dotnet/core/extensions/resources)
  - [Worker Services](https://learn.microsoft.com/en-us/dotnet/core/extensions/workers?pivots=dotnet-7-0)
  - [Caching](https://learn.microsoft.com/en-us/dotnet/core/extensions/caching)  
- MSBuild
  - [Overview](https://learn.microsoft.com/en-us/dotnet/core/project-sdk/overview)
  - [Target frameworks](https://learn.microsoft.com/en-us/dotnet/standard/frameworks)
  - [Dependency management](https://learn.microsoft.com/en-us/dotnet/core/tools/dependencies)
- Execution model
  - [Common Language Runtime or CLR](https://learn.microsoft.com/en-us/dotnet/standard/clr)
  - [Managed execution process](https://learn.microsoft.com/en-us/dotnet/standard/managed-execution-process)
  - [Assemblies](https://learn.microsoft.com/en-us/dotnet/standard/assembly/)
  - [Dependency loading](https://learn.microsoft.com/en-us/dotnet/core/dependency-loading/overview)
  - [Versioning](https://learn.microsoft.com/en-us/dotnet/core/versions/)
  - [Configuring the runtime](https://learn.microsoft.com/en-us/dotnet/core/runtime-config/)
- [Diagnostics](https://learn.microsoft.com/en-us/dotnet/core/diagnostics/)
- Advanced Topics
  - [Threads](https://learn.microsoft.com/en-us/dotnet/standard/threading/managed-threading-basics)
  - [Memory management and resource cleanup](https://learn.microsoft.com/en-us/dotnet/standard/garbage-collection/unmanaged)
    - Heap vs Stack: part [1](https://www.c-sharpcorner.com/article/C-Sharp-heaping-vs-stacking-in-net-part-i)-[2](https://www.c-sharpcorner.com/article/C-Sharp-heaping-vs-stacking-in-net-part-ii)-[3](https://www.c-sharpcorner.com/article/C-Sharp-heaping-vs-stacking-in-net-part-iii)-[4](https://www.c-sharpcorner.com/article/C-Sharp-heaping-vs-stacking-in-net-part-iv)

## Going on ...

Continue on @Elfocrash's [.NET Backend Developer roadmap](https://github.com/Elfocrash/.NET-Backend-Developer-Roadmap)


