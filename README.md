# C# and .NET Roadmap for Beginners

This document contains a simplified list of concepts to guide new developers through learning the basics of the C# and .NET ecosystem.

## Diagram

![C# and .NET Roadmap Diagram](https://raw.githubusercontent.com/gridlocdev/dotnet-learning-roadmap/main/csharp-roadmap.drawio.svg)

## C#

- Learn the Fundamentals
  - Basic Syntax
  - [Variables](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/language-specification/variables) and [Data Types](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/built-in-types)
    - [String](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/reference-types)
    - [Int](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/integral-numeric-types)
    - [Boolean](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/bool)
    - [Float/Double/Decimal](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/floating-point-numeric-types)
    - [Var](https://docs.microsoft.com/en-us/dotnet/csharp/fundamentals/types/anonymous-types)
  - [Conditionals](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/statements/selection-statements)
  - [Methods](https://docs.microsoft.com/en-us/dotnet/csharp/methods)
  - [Collections](https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/concepts/collections)
    - [Array](https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/arrays/)
    - [List](https://docs.microsoft.com/en-us/dotnet/api/system.collections.generic.list-1)
    - [Dictionary](https://docs.microsoft.com/en-us/dotnet/api/system.collections.generic.dictionary-2)
  - [Iterators](https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/concepts/iterators)
  - [Namespaces](https://docs.microsoft.com/en-us/dotnet/csharp/fundamentals/types/namespaces)
  - [Using directives](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/keywords/using-directive)
  - [String Interpolation](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/tokens/interpolated)
  - [Exception Handling](https://docs.microsoft.com/en-us/dotnet/csharp/fundamentals/exceptions/exception-handling)
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
- Going Deeper
  - [Linq](https://docs.microsoft.com/en-us/dotnet/csharp/linq/)
  - [Object and Collection initializers](https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/classes-and-structs/object-and-collection-initializers)
  - [Lambdas](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/operators/lambda-expressions)
    - ["=>" Operator](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/operators/lambda-operator)
    - [Arrow Functions](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/operators/lambda-expressions)
  - [Asynchronous Programming](https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/concepts/async/)
    - [Threads](https://docs.microsoft.com/en-us/dotnet/standard/threading/using-threads-and-threading)
    - [Tasks](https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/concepts/async/)
    - [Async](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/keywords/async)
    - [Await](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/operators/await)
  - [Generics](https://docs.microsoft.com/en-us/dotnet/csharp/fundamentals/types/generics)
  - [Serialization](https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/concepts/serialization/)
  - [Reflection](https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/concepts/reflection)
  - (Optional) Functional Techniques
    - [Pattern Matching](https://docs.microsoft.com/en-us/dotnet/csharp/fundamentals/functional/pattern-matching)
    - [Discards](https://docs.microsoft.com/en-us/dotnet/csharp/fundamentals/functional/discards)
    - [Deconstructing Tuples](https://docs.microsoft.com/en-us/dotnet/csharp/fundamentals/functional/deconstruct)

## .NET (Web Developer)

- Understanding the Ecosystem
  - .NET Framework
  - .NET Standard
  - .NET (Core)
- Tooling
  - [.NET CLI](https://docs.microsoft.com/en-us/dotnet/core/tools/)
  - NuGet
- .NET (Core) Web Projects
  - Blazor WebAssembly
  - Minimal Web API
  - Web API
  - Razor Pages
  - Blazor Server
  - MVC
- Libraries
  - ORM
    - Entity Framework, Dapper
  - Testing
    - Unit Testing
      - xUnit, NUnit, MSTest
    - [Performance Testing](https://docs.microsoft.com/en-us/aspnet/core/test/load-tests?view=aspnetcore-6.0)
    - E2E Testing
      - Selenium
  - Logging
    - NLog, Serilog
  - Other
    - AutoMapper
    - Swashbuckle / Swagger
