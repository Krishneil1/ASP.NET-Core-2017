# ASP.NET-Core-2017
ASP.NET Core 2017

This repo is a tutorail I am taking up for my new project development using .NET core. As always start with basic. 

## 1.Install .NET SDK
To start building .NET apps you just need to download and install the .NET SDK (Software Development Kit).
https://download.microsoft.com/download/1/1/5/115B762D-2B41-4AF3-9A63-92D9680B9409/dotnet-sdk-2.1.4-win-gs-x64.exe

## 2.Create your app
Open a new command prompt and run the following commands.
```
dotnet new console -o myApp
cd myApp
```
The dotnet command will create a new application of type console for you. The -o parameter will create a directory named myApp where your app will be stored, and populates it with the required files. The cd myApp command puts you into the newly created app directory.

The main file in the myApp folder is Program.cs. By default, it already contains the necessary code to write "Hello World!" to the Console.
```
using System;

namespace myApp
{
    class Program
    {
        static void Main(string[] args)
        {
            Console.WriteLine("Hello World!");
        }
    }
}
```
## 3.Run your app
In your command prompt, run the following command:
```
dotnet run
Congratulations, you've built and run your first .NET app!
```
## 4.Get an editor
Visual Studio is a fully-featured integrated development environment (IDE) for developing .NET apps on Windows.
https://www.visualstudio.com/thank-you-downloading-visual-studio/?sku=Community&rel=15&utm_medium=clickbutton&utm_campaign=tailored_getStartDotNetCore&rid=34357&dotnetid=168964484.1519186279

Keep learning