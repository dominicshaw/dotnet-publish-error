# dotnet-publish-error

clone project and go to command line at the root and enter 
```
dotnet publish PublishError.csproj /p:OutputPath=c:\temp_pub\ -p:PublishProfile=ClickOnceProfile
```
yields error 
```
MSBuild version 17.4.0+18d5aef85 for .NET
  Determining projects to restore...
  All projects are up-to-date for restore.
C:\Program Files\dotnet\sdk\7.0.100\Microsoft.Common.CurrentVersion.targets(4149,5): error MSB4062: The "Microsoft.Build.Tasks.RequiresFr
amework35SP1Assembly" task could not be loaded from the assembly Microsoft.Build.Tasks.Core, Version=15.1.0.0, Culture=neutral, PublicKey
Token=b03f5f7f11d50a3a.  Confirm that the <UsingTask> declaration is correct, that the assembly and all its dependencies are available, a
nd that the task contains a public class that implements Microsoft.Build.Framework.ITask. [C:\Users\shawd\source\repos\PublishError\Publi
shError\PublishError.csproj]
```