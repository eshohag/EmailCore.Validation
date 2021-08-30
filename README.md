# EmailCore.Validation [![Build status](https://ci.appveyor.com/api/projects/status/67ubhtmijuhyhq6q?svg=true)](https://ci.appveyor.com/project/eshohag/EmailCore.Validation) [![NuGet Badge](https://buildstats.info/nuget/EmailCore.Validation)](https://www.nuget.org/packages/EmailCore.Validation)

EmailCore.Validation in C# (.NET Core) to validate Email- Syntax, Domain/MX Record and Handshake with Email server to validate Email addresses information

## Code Syntax
```csharp
using EmailCore.Validation;
namespace ConsoleApp
{
    class Program
    {
        static void Main(string[] args)
        {
            var emailInfo = EmailInfo.Validation("shohaghassan14@gmail.com");
        }
    }
}

```
