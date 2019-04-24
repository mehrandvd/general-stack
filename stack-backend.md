# Backend

For backend we suggest:
- Platform: .NET Core
- Language: C#
- Frameworks: EntityFramework Core, Autofac, OData, SignalR

## Why this?
_[What's great about .NET Core]_

### Too Many Environments: Almost everywhere!

_[The many environments that .NET Core can run on]_


### Performance

In terms of performance there is no modern framework can compete with .NET Core. .NET Core works much faster than all commercial frameworks on Java, Node and even Go! The only commercial framework faster than .NET Core is `fasthttp` which is not a rich framework and Go developers are not using it in normal situations.

Although it is the fastest now, but it is not the most interesting point about it. The interesting point about it is its **performance growth** in recent years. You can watch how it goes up in the TechEmpower rankings in the recent rounds:

_[Issue #3: This table should be filled and referenced by TechEmpower website]_
|Best Rank|.NET Core|Node|Java|Go|
|-|-|-|-|-|
|Round 16|-|-|-|-|
|Round 15|-|-|-|-|
|Round 14|-|-|-|-|
|Round 13|-|-|-|-|
|Round 12|-|-|-|-|

The more interesting point, is the fact that best performance benchmarks of .NET Core are achieved on _Linux_! So it is recommended to use Linux for server or establish a docker based deployment.

### Roslyn: The unique magic of C#
_[Issue #4: How Roslyn makes C# unreachable for other languages]_

### WebAssembly bright future 
_[Issue #5: How C# is actively building its future with WebAssembly: Blazor, Xamarin.WebAssembly, Uno]_

### AI and IoT future
_[Issue #6: How C# is working in AI, IoT fields]_

## Risks
This stack is completely new. Since .NET Core 2.0 it is mature enough to be used in production. But EntityFramework Core 2.2 lacks some features yet. Although we are using it in our production projects but it seems it will be completely mature somewhere in version 3.*.

But the biggest risk is that it is a Microsoft product, and still there are lots of people that hate Microsoft. As this is a historical hatred usually it is so hard to convince those people as mostly there is no rationality in their reasonings. It's just a grudge that came out of Balmer's Microsoft. As .NET is completely being developed in an open source community it may make it easier to break the ice in within the process of convincing.

