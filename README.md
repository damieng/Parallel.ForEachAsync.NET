# Parallel.ForEachAsync.NET

A port of Microsoft's Parallel.ForEachAsync from .NET 6.0 to .NET Core 3.1..

Scott Hanselman has a [great article on Parallel.ForEachAsync](https://www.hanselman.com/blog/parallelforeachasync-in-net-6).

The TL;DR; is if you have a function you want to run many times in parallel against a list of data concurrently then this is probably the class you want.

**If you are using .NET 6.0 you do not need this library - it is built in.**

For those stuck on .NET 5.0 or .NET Core 3.1 this library gives you that functionality (but you miss out on a lot of other .NET 6 task-related features so consider upgrading) without any additional functionality or dependencies along for the ride.

## How can I contribute?

This is an almost 100% port of the code from https://github.com/dotnet/runtime/ and there are no plans to add any functionality beyond what is in https://github.com/dotnet/runtime/blob/53d1d2c6ec322fd5eb3351982107d389c182ad46/src/libraries/System.Threading.Tasks.Parallel/src/System/Threading/Tasks/Parallel.ForEachAsync.cs

## License

.NET (including the runtime repo) is licensed under the [MIT](LICENSE.txt) license.
